---
title: DataBar sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 390
url: /tr/aspose.cells/databar/
is_root: false
---
##  DataBar sınıfı
 DataBar koşullu biçimlendirme kuralını açıklayın.
Bu koşullu biçimlendirme kuralı, derecelendirilmiş bir biçimlendirme görüntüler
hücre aralığındaki veri çubuğu.



DataBar türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [axis_color](/cells/python-net/tr/aspose.cells/databar/axis_color) | Koşullu biçimlendirme uygulanmış veri çubukları için eksenin rengini alır.|
| [axis_position](/cells/python-net/tr/aspose.cells/databar/axis_position) | Koşullu biçimlendirme kuralı tarafından belirtilen veri çubuklarının ekseninin konumunu alır veya ayarlar.|
| [bar_fill_type](/cells/python-net/tr/aspose.cells/databar/bar_fill_type) | Bir veri çubuğunun renkle nasıl doldurulacağını alır veya ayarlar.|
| [direction](/cells/python-net/tr/aspose.cells/databar/direction) | Veri çubuğunun görüntülenme yönünü alır veya ayarlar.|
| [bar_border](/cells/python-net/tr/aspose.cells/databar/bar_border) | Bir veri çubuğunun sınırını belirten bir nesne alır.|
| [negative_bar_format](/cells/python-net/tr/aspose.cells/databar/negative_bar_format) | Bir veri çubuğu koşullu biçimlendirme kuralıyla ilişkili NegativeBarFormat nesnesini alır.|
| [min_cfvo](/cells/python-net/tr/aspose.cells/databar/min_cfvo) | Bu DataBar'ın en düşük değer nesnesini al veya ayarla.<br/> FormatConditionValueType.Max türünde null veya CFValueObject değeri ayarlanamaz.|
| [max_cfvo](/cells/python-net/tr/aspose.cells/databar/max_cfvo) | Bu DataBar'ın maksimum değer nesnesini al veya ayarla.<br/> FormatConditionValueType.Min türünde null veya CFValueObject değeri ayarlanamaz.|
| [color](/cells/python-net/tr/aspose.cells/databar/color) | Bu DataBar'ın Rengini al veya ayarla.|
| [min_length](/cells/python-net/tr/aspose.cells/databar/min_length) | Veri çubuğunun minimum uzunluğunu temsil eder.|
| [max_length](/cells/python-net/tr/aspose.cells/databar/max_length) | Veri çubuğunun maksimum uzunluğunu temsil eder.|
| [show_value](/cells/python-net/tr/aspose.cells/databar/show_value) |Bu veri çubuğunun uygulandığı hücrelerin değerlerinin gösterilip gösterilmeyeceğini belirten bayrağı alın veya ayarlayın.<br/> Varsayılan değer doğrudur.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`to_image(self, cell, img_opts)`](/cells/python-net/tr/aspose.cells/databar/to_image/#aspose.cells.cell-aspose.cells.rendering.imageorprintoptions) | Hücredeki veri çubuğunu görüntü bayt dizisine dönüştür.|



###  Örnek

```python
from aspose.cells import CellArea, DataBarAxisPosition, DataBarBorderType, DataBarFillType, DataBarNegativeColorType, FormatConditionType, FormatConditionValueType, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
sheet = workbook.worksheets[0]
# Adds an empty conditional formatting
index = sheet.conditional_formattings.add()
fcs = sheet.conditional_formattings[index]
# Sets the conditional format range.
ca = CellArea()
ca.start_row = 0
ca.end_row = 2
ca.start_column = 0
ca.end_column = 0
fcs.add_area(ca)
# Adds condition.
idx = fcs.add_condition(FormatConditionType.DATA_BAR)
fcs.add_area(ca)
cond = fcs[idx]
# Get Databar
dataBar = cond.data_bar
dataBar.color = Color.orange
# Set Databar properties
dataBar.min_cfvo.type = FormatConditionValueType.PERCENTILE
dataBar.min_cfvo.value = 30
dataBar.show_value = False
dataBar.bar_border.type = DataBarBorderType.SOLID
dataBar.bar_border.color = Color.plum
dataBar.bar_fill_type = DataBarFillType.SOLID
dataBar.axis_color = Color.red
dataBar.axis_position = DataBarAxisPosition.MIDPOINT
dataBar.negative_bar_format.color_type = DataBarNegativeColorType.COLOR
dataBar.negative_bar_format.color = Color.white
dataBar.negative_bar_format.border_color_type = DataBarNegativeColorType.COLOR
dataBar.negative_bar_format.border_color = Color.yellow
# Put Cell Values
cell1 = sheet.cells.get("A1")
cell1.put_value(10)
cell2 = sheet.cells.get("A2")
cell2.put_value(120)
cell3 = sheet.cells.get("A3")
cell3.put_value(260)
# Saving the Excel file
workbook.save("book1.xlsx")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
