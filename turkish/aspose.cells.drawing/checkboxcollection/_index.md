---
title: CheckBoxCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 100
url: /tr/aspose.cells.drawing/checkboxcollection/
is_root: false
---
##  CheckBoxCollection sınıfı
Bir çalışma sayfasındaki [CheckBox](/cells/python-net/tr/aspose.cells.drawing/checkbox) nesne koleksiyonunu temsil eder.



CheckBoxCollection türü aşağıdaki üyeleri gösterir:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells.drawing/checkboxcollection/capacity) | Dizi listesinin içerebileceği öğe sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [copy_to(array)](/cells/python-net/tr/aspose.cells.drawing/checkboxcollection/copy_to/#list) | Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [copy_to(index, array, array_index, count)](/cells/python-net/tr/aspose.cells.drawing/checkboxcollection/copy_to/#int-list-int-int) |Dizi listesindeki bir dizi öğeyi, hedef dizi listesinin belirtilen dizininden başlayarak uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [index_of(item, index)](/cells/python-net/tr/aspose.cells.drawing/checkboxcollection/index_of/#CheckBox-int) | Belirtilen nesneyi arar ve belirtilen dizinden son öğeye uzanan dizi listesindeki öğelerin aralığındaki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [index_of(item, index, count)](/cells/python-net/tr/aspose.cells.drawing/checkboxcollection/index_of/#CheckBox-int-int) | Belirtilen nesneyi arar ve belirtilen dizinde başlayan ve belirtilen sayıda öğe içeren dizi listesindeki öğe aralığı içindeki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of(item)](/cells/python-net/tr/aspose.cells.drawing/checkboxcollection/last_index_of/#CheckBox) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of(item, index)](/cells/python-net/tr/aspose.cells.drawing/checkboxcollection/last_index_of/#CheckBox-int) | Belirtilen nesneyi arar ve ilk öğeden belirtilen dizine kadar uzanan dizi listesindeki öğe aralığı içindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of(item, index, count)](/cells/python-net/tr/aspose.cells.drawing/checkboxcollection/last_index_of/#CheckBox-int-int) |Belirtilen nesneyi arar ve belirtilen sayıda öğeyi içeren ve belirtilen dizinde biten dizi listesindeki öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [add(upper_left_row, upper_left_column, height, width)](/cells/python-net/tr/aspose.cells.drawing/checkboxcollection/add/#int-int-int-int) | Koleksiyona bir checkBox ekler.|
| [binary_search(item)](/cells/python-net/tr/aspose.cells.drawing/checkboxcollection/binary_search/#CheckBox) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfır tabanlı dizinini döndürür.|



###  Örnek

```python
from aspose.cells import Workbook

# Create a new Workbook.
workbook = Workbook()
# Get the first worksheet in the workbook.
sheet = workbook.worksheets[0]
index = sheet.check_boxes.add(15, 15, 20, 100)
checkBox = sheet.check_boxes[index]
checkBox.text = "Check Box 1"

```

###  Ayrıca bakınız
* modül [aspose.cells.drawing](..)
* sınıf [CheckBox](/cells/python-net/tr/aspose.cells.drawing/checkbox)
