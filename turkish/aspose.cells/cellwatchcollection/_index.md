---
title: CellWatchCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 150
url: /tr/aspose.cells/cellwatchcollection/
is_root: false
---
##  CellWatchCollection sınıfı
Bu çalışma sayfasındaki 'izleme penceresinde' izlenen hücre koleksiyonunu temsil eder.



CellWatchCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells/cellwatchcollection/__init__/#) | CellWatchCollection'ın yeni bir örneğini oluşturur|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells/cellwatchcollection/capacity) | Dizi listesinin içerebileceği eleman sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add(self, row, column)`](/cells/python-net/tr/aspose.cells/cellwatchcollection/add/#int-int) | [`CellWatch`](/cells/python-net/tr/aspose.cells/cellwatch) satır ve sütununu ekler.|
| [`add(self, cell_name)`](/cells/python-net/tr/aspose.cells/cellwatchcollection/add/#str) | Hücrenin adı olan [`CellWatch`](/cells/python-net/tr/aspose.cells/cellwatch)'i ekler.|
| [`copy_to(self, array)`](/cells/python-net/tr/aspose.cells/cellwatchcollection/copy_to/#list) |Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/tr/aspose.cells/cellwatchcollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen indeksinden başlayarak, dizi listesindeki bir dizi öğeyi uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`index_of(self, item, index)`](/cells/python-net/tr/aspose.cells/cellwatchcollection/index_of/#aspose.cells.cellwatch-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının, belirtilen indeksten son elemana kadar uzanan ilk oluşumunun sıfırdan başlayan indeksini döndürür.|
| [`index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells/cellwatchcollection/index_of/#aspose.cells.cellwatch-int-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığında belirtilen indeksten başlayıp belirtilen sayıda eleman içeren ilk oluşumun sıfırdan başlayan indeksini döndürür.|
| [`last_index_of(self, item)`](/cells/python-net/tr/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfırdan başlayan dizinini döndürür.|
| [`last_index_of(self, item, index)`](/cells/python-net/tr/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch-int) |Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının ilk elemanından belirtilen dizine kadar uzanan son oluşumun sıfır tabanlı dizinini döndürür.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch-int-int) | Belirtilen nesneyi arar ve dizi listesindeki belirtilen sayıda öğeyi içeren ve belirtilen dizinde sona eren öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [`get(self, cell_name)`](/cells/python-net/tr/aspose.cells/cellwatchcollection/get/#str) | Hücrenin adına göre [`CellWatch`](/cells/python-net/tr/aspose.cells/cellwatch) değerini alır ve ayarlar.|
| [`binary_search(self, item)`](/cells/python-net/tr/aspose.cells/cellwatchcollection/binary_search/#aspose.cells.cellwatch) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfırdan başlayan dizinini döndürür.|



###  Örnek

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet.
sheet = workbook.worksheets[0]
#  Add Cell Watch Item into the watch window
sheet.cell_watches.add("B2")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`CellWatch`](/cells/python-net/tr/aspose.cells/cellwatch)
