---
title: CellWatchCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 180
url: /tr/aspose.cells/cellwatchcollection/
is_root: false
---
##  CellWatchCollection sınıfı
Bu çalışma sayfasındaki 'gözetleme penceresinde' izlenen hücrelerin koleksiyonunu temsil eder.



CellWatchCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [__init__](/cells/python-net/tr/aspose.cells/cellwatchcollection/__init__/#) | CellWatchCollection'ın yeni bir örneğini oluşturur|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells/cellwatchcollection/capacity) | Dizi listesinin içerebileceği öğe sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [add](/cells/python-net/tr/aspose.cells/cellwatchcollection/add/#int-int) | Satır ve sütunla birlikte [`CellWatch`](/cells/python-net/tr/aspose.cells/cellwatch)'i ekler.|
| [add](/cells/python-net/tr/aspose.cells/cellwatchcollection/add/#str) | Hücre adını içeren [`CellWatch`](/cells/python-net/tr/aspose.cells/cellwatch)'i ekler.|
| [copy_to](/cells/python-net/tr/aspose.cells/cellwatchcollection/copy_to/#list) | Hedef dizi listesinin başından başlayarak dizi listesinin tamamını uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [copy_to](/cells/python-net/tr/aspose.cells/cellwatchcollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen dizininden başlayarak, dizi listesinden bir dizi öğeyi uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [index_of](/cells/python-net/tr/aspose.cells/cellwatchcollection/index_of/#aspose.cells.CellWatch-int) | Belirtilen nesneyi arar ve belirtilen dizinden son öğeye kadar uzanan dizi listesindeki öğe aralığı içindeki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [index_of](/cells/python-net/tr/aspose.cells/cellwatchcollection/index_of/#aspose.cells.CellWatch-int-int) |Belirtilen nesneyi arar ve belirtilen dizinde başlayan ve belirtilen sayıda öğeyi içeren dizi listesindeki öğe aralığı içindeki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.CellWatch) | Belirtilen nesneyi arar ve dizi listesinin tamamındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.CellWatch-int) | Belirtilen nesneyi arar ve ilk öğeden belirtilen dizine kadar uzanan dizi listesindeki öğe aralığı içindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.CellWatch-int-int) | Belirtilen nesneyi arar ve belirtilen sayıda öğeyi içeren ve belirtilen dizinde biten dizi listesindeki öğe aralığı içindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [binary_search](/cells/python-net/tr/aspose.cells/cellwatchcollection/binary_search/#aspose.cells.CellWatch) | Varsayılan karşılaştırıcıyı kullanarak bir öğe için sıralanmış dizi listesinin tamamını arar ve öğenin sıfır tabanlı dizinini döndürür.|



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
