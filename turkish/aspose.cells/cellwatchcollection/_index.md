---
title: CellWatchCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 170
url: /tr/aspose.cells/cellwatchcollection/
is_root: false
---
##  CellWatchCollection sınıfı
Bu çalışma sayfasındaki 'izleme penceresinde' izlenen hücre koleksiyonunu temsil eder.



CellWatchCollection türü aşağıdaki üyeleri gösterir:

###  İnşaatçılar
| Yapıcı| Tanım|
| :- | :- |
| [CellWatchCollection()](/cells/python-net/tr/aspose.cells/cellwatchcollection/__init__/#) | CellWatchCollection'ın yeni bir örneğini oluşturur|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells/cellwatchcollection/capacity) | Dizi listesinin içerebileceği öğe sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [add(row, column)](/cells/python-net/tr/aspose.cells/cellwatchcollection/add/#int-int) | Satır ve sütun ile [CellWatch](/cells/python-net/tr/aspose.cells/cellwatch) ekler.|
| [add(cell_name)](/cells/python-net/tr/aspose.cells/cellwatchcollection/add/#str) | Hücrenin adı ile [CellWatch](/cells/python-net/tr/aspose.cells/cellwatch) ekler.|
| [copy_to(array)](/cells/python-net/tr/aspose.cells/cellwatchcollection/copy_to/#list) | Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [copy_to(index, array, array_index, count)](/cells/python-net/tr/aspose.cells/cellwatchcollection/copy_to/#int-list-int-int) |Dizi listesindeki bir dizi öğeyi, hedef dizi listesinin belirtilen dizininden başlayarak uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [index_of(item, index)](/cells/python-net/tr/aspose.cells/cellwatchcollection/index_of/#CellWatch-int) | Belirtilen nesneyi arar ve belirtilen dizinden son öğeye uzanan dizi listesindeki öğelerin aralığındaki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [index_of(item, index, count)](/cells/python-net/tr/aspose.cells/cellwatchcollection/index_of/#CellWatch-int-int) | Belirtilen nesneyi arar ve belirtilen dizinde başlayan ve belirtilen sayıda öğe içeren dizi listesindeki öğe aralığı içindeki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of(item)](/cells/python-net/tr/aspose.cells/cellwatchcollection/last_index_of/#CellWatch) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of(item, index)](/cells/python-net/tr/aspose.cells/cellwatchcollection/last_index_of/#CellWatch-int) | Belirtilen nesneyi arar ve ilk öğeden belirtilen dizine kadar uzanan dizi listesindeki öğe aralığı içindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of(item, index, count)](/cells/python-net/tr/aspose.cells/cellwatchcollection/last_index_of/#CellWatch-int-int) |Belirtilen nesneyi arar ve belirtilen sayıda öğeyi içeren ve belirtilen dizinde biten dizi listesindeki öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [binary_search(item)](/cells/python-net/tr/aspose.cells/cellwatchcollection/binary_search/#CellWatch) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfır tabanlı dizinini döndürür.|



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
* modül [aspose.cells](..)
* sınıf [CellWatch](/cells/python-net/tr/aspose.cells/cellwatch)
