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
Bir çalışma sayfasındaki [`CheckBox`](/cells/python-net/tr/aspose.cells.drawing/checkbox) nesneden oluşan bir koleksiyonu temsil eder.



CheckBoxCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells.drawing/checkboxcollection/capacity) | Dizi listesinin içerebileceği eleman sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/tr/aspose.cells.drawing/checkboxcollection/copy_to/#list) |Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/tr/aspose.cells.drawing/checkboxcollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen indeksinden başlayarak, dizi listesindeki bir dizi öğeyi uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.drawing/checkboxcollection/index_of/#aspose.cells.drawing.checkbox-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının, belirtilen indeksten son elemana kadar uzanan ilk oluşumunun sıfırdan başlayan indeksini döndürür.|
| [`index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.drawing/checkboxcollection/index_of/#aspose.cells.drawing.checkbox-int-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığında belirtilen indeksten başlayıp belirtilen sayıda eleman içeren ilk oluşumun sıfırdan başlayan indeksini döndürür.|
| [`last_index_of(self, item)`](/cells/python-net/tr/aspose.cells.drawing/checkboxcollection/last_index_of/#aspose.cells.drawing.checkbox) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfırdan başlayan dizinini döndürür.|
| [`last_index_of(self, item, index)`](/cells/python-net/tr/aspose.cells.drawing/checkboxcollection/last_index_of/#aspose.cells.drawing.checkbox-int) |Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının ilk elemanından belirtilen dizine kadar uzanan son oluşumun sıfır tabanlı dizinini döndürür.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells.drawing/checkboxcollection/last_index_of/#aspose.cells.drawing.checkbox-int-int) | Belirtilen nesneyi arar ve dizi listesindeki belirtilen sayıda öğeyi içeren ve belirtilen dizinde sona eren öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [`add(self, upper_left_row, upper_left_column, height, width)`](/cells/python-net/tr/aspose.cells.drawing/checkboxcollection/add/#int-int-int-int) | Koleksiyona bir checkBox ekler.|
| [`binary_search(self, item)`](/cells/python-net/tr/aspose.cells.drawing/checkboxcollection/binary_search/#aspose.cells.drawing.checkbox) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfırdan başlayan dizinini döndürür.|



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
* modül [`aspose.cells.drawing`](..)
* sınıf [`CheckBox`](/cells/python-net/tr/aspose.cells.drawing/checkbox)
