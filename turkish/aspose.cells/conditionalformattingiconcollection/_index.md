---
title: ConditionalFormattingIconCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 330
url: /tr/aspose.cells/conditionalformattingiconcollection/
is_root: false
---
##  ConditionalFormattingIconCollection sınıfı
[`ConditionalFormattingIcon`](/cells/python-net/tr/aspose.cells/conditionalformattingicon) nesneden oluşan bir koleksiyonu temsil eder.



ConditionalFormattingIconCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [capacity](/cells/python-net/tr/aspose.cells/conditionalformattingiconcollection/capacity) | Dizi listesinin içerebileceği öğe sayısını alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [add](/cells/python-net/tr/aspose.cells/conditionalformattingiconcollection/add/#aspose.cells.IconSetType-int) | [`ConditionalFormattingIcon`](/cells/python-net/tr/aspose.cells/conditionalformattingicon) nesnesini ekler.|
| [add](/cells/python-net/tr/aspose.cells/conditionalformattingiconcollection/add/#aspose.cells.ConditionalFormattingIcon) | [`ConditionalFormattingIcon`](/cells/python-net/tr/aspose.cells/conditionalformattingicon) nesnesini ekler.|
| [copy_to](/cells/python-net/tr/aspose.cells/conditionalformattingiconcollection/copy_to/#list) | Hedef dizi listesinin başından başlayarak dizi listesinin tamamını uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [copy_to](/cells/python-net/tr/aspose.cells/conditionalformattingiconcollection/copy_to/#int-list-int-int) | Hedef dizi listesinin belirtilen dizininden başlayarak, dizi listesinden bir dizi öğeyi uyumlu bir tek boyutlu dizi listesine kopyalar.|
| [index_of](/cells/python-net/tr/aspose.cells/conditionalformattingiconcollection/index_of/#aspose.cells.ConditionalFormattingIcon-int) | Belirtilen nesneyi arar ve belirtilen dizinden son öğeye kadar uzanan dizi listesindeki öğe aralığı içindeki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [index_of](/cells/python-net/tr/aspose.cells/conditionalformattingiconcollection/index_of/#aspose.cells.ConditionalFormattingIcon-int-int) |Belirtilen nesneyi arar ve belirtilen dizinde başlayan ve belirtilen sayıda öğeyi içeren dizi listesindeki öğe aralığı içindeki ilk oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.ConditionalFormattingIcon) | Belirtilen nesneyi arar ve dizi listesinin tamamındaki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.ConditionalFormattingIcon-int) | Belirtilen nesneyi arar ve ilk öğeden belirtilen dizine kadar uzanan dizi listesindeki öğe aralığı içindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [last_index_of](/cells/python-net/tr/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.ConditionalFormattingIcon-int-int) | Belirtilen nesneyi arar ve belirtilen sayıda öğeyi içeren ve belirtilen dizinde biten dizi listesindeki öğe aralığı içindeki son oluşumun sıfır tabanlı dizinini döndürür.|
| [binary_search](/cells/python-net/tr/aspose.cells/conditionalformattingiconcollection/binary_search/#aspose.cells.ConditionalFormattingIcon) | Varsayılan karşılaştırıcıyı kullanarak bir öğe için sıralanmış dizi listesinin tamamını arar ve öğenin sıfır tabanlı dizinini döndürür.|



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
