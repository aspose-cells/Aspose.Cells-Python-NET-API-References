---
title: ConditionalFormattingIconCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 300
url: /tr/aspose.cells/conditionalformattingiconcollection/
is_root: false
---
##  ConditionalFormattingIconCollection sınıfı
[`ConditionalFormattingIcon`](/cells/python-net/tr/aspose.cells/conditionalformattingicon) nesneden oluşan bir koleksiyonu temsil eder.



ConditionalFormattingIconCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells/conditionalformattingiconcollection/capacity) | Dizi listesinin içerebileceği eleman sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add(self, type, index)`](/cells/python-net/tr/aspose.cells/conditionalformattingiconcollection/add/#aspose.cells.iconsettype-int) | [`ConditionalFormattingIcon`](/cells/python-net/tr/aspose.cells/conditionalformattingicon) nesnesini ekler.|
| [`add(self, cficon)`](/cells/python-net/tr/aspose.cells/conditionalformattingiconcollection/add/#aspose.cells.conditionalformattingicon) | [`ConditionalFormattingIcon`](/cells/python-net/tr/aspose.cells/conditionalformattingicon) nesnesini ekler.|
| [`copy_to(self, array)`](/cells/python-net/tr/aspose.cells/conditionalformattingiconcollection/copy_to/#list) |Hedef dizi listesinin başından başlayarak tüm dizi listesini uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/tr/aspose.cells/conditionalformattingiconcollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen indeksinden başlayarak, dizi listesindeki bir dizi öğeyi uyumlu tek boyutlu bir dizi listesine kopyalar.|
| [`index_of(self, item, index)`](/cells/python-net/tr/aspose.cells/conditionalformattingiconcollection/index_of/#aspose.cells.conditionalformattingicon-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının, belirtilen indeksten son elemana kadar uzanan ilk oluşumunun sıfırdan başlayan indeksini döndürür.|
| [`index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells/conditionalformattingiconcollection/index_of/#aspose.cells.conditionalformattingicon-int-int) | Belirtilen nesneyi arar ve dizi listesindeki eleman aralığında belirtilen indeksten başlayıp belirtilen sayıda eleman içeren ilk oluşumun sıfırdan başlayan indeksini döndürür.|
| [`last_index_of(self, item)`](/cells/python-net/tr/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.conditionalformattingicon) | Belirtilen nesneyi arar ve tüm dizi listesindeki son oluşumun sıfırdan başlayan dizinini döndürür.|
| [`last_index_of(self, item, index)`](/cells/python-net/tr/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.conditionalformattingicon-int) |Belirtilen nesneyi arar ve dizi listesindeki eleman aralığının ilk elemanından belirtilen dizine kadar uzanan son oluşumun sıfır tabanlı dizinini döndürür.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/tr/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.conditionalformattingicon-int-int) | Belirtilen nesneyi arar ve dizi listesindeki belirtilen sayıda öğeyi içeren ve belirtilen dizinde sona eren öğe aralığındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [`binary_search(self, item)`](/cells/python-net/tr/aspose.cells/conditionalformattingiconcollection/binary_search/#aspose.cells.conditionalformattingicon) | Varsayılan karşılaştırıcıyı kullanarak sıralanmış dizi listesinin tamamında bir öğe arar ve öğenin sıfırdan başlayan dizinini döndürür.|



###  Örnek

```python
from aspose.cells import CellArea, FormatConditionType, IconSetType, Workbook

# Instantiating a Workbook object
workbook = Workbook()
sheet = workbook.worksheets[0]
# Get Conditional Formatting
cformattings = sheet.conditional_formattings
# Adds an empty conditional formatting
index = cformattings.add()
# Get newly added Conditional formatting
fcs = cformattings[index]
# Sets the conditional format range.
ca = CellArea()
ca.start_row = 0
ca.end_row = 0
ca.start_column = 0
ca.end_column = 0
fcs.add_area(ca)
ca = CellArea()
ca.start_row = 1
ca.end_row = 1
ca.start_column = 1
ca.end_column = 1
fcs.add_area(ca)
# Sets condition
idx = fcs.add_condition(FormatConditionType.ICON_SET)
cond = fcs[idx]
# Sets condition's type
cond.icon_set.type = IconSetType.ARROWS_GRAY3
# Add custom iconset condition.
cfIcon = cond.icon_set.cf_icons[0]
cfIcon.type = IconSetType.ARROWS3
cfIcon.index = 0
cfIcon1 = cond.icon_set.cf_icons[1]
cfIcon1.type = IconSetType.ARROWS_GRAY3
cfIcon1.index = 1
cfIcon2 = cond.icon_set.cf_icons[2]
cfIcon2.type = IconSetType.BOXES5
cfIcon2.index = 2
# Saving the Excel file
workbook.save("output.xls")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`ConditionalFormattingIcon`](/cells/python-net/tr/aspose.cells/conditionalformattingicon)
