---
title: DataBar klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 390
url: /sv/aspose.cells/databar/
is_root: false
---
##  DataBar klass
 Beskriv regeln för villkorlig formatering DataBar.
Denna regel för villkorlig formatering visar en graderad
datafältet i cellområdet.



Typen DataBar avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [axis_color](/cells/python-net/sv/aspose.cells/databar/axis_color) | Hämtar färgen på axeln för celler med villkorsstyrd formatering som databaster.|
| [axis_position](/cells/python-net/sv/aspose.cells/databar/axis_position) | Hämtar eller anger positionen för axeln i datastapeln som anges av en villkorsstyrd formateringsregel.|
| [bar_fill_type](/cells/python-net/sv/aspose.cells/databar/bar_fill_type) | Hämtar eller anger hur en datastapel fylls med färg.|
| [direction](/cells/python-net/sv/aspose.cells/databar/direction) | Hämtar eller anger i vilken riktning datafältet visas.|
| [bar_border](/cells/python-net/sv/aspose.cells/databar/bar_border) | Hämtar ett objekt som anger kanten för en datastapel.|
| [negative_bar_format](/cells/python-net/sv/aspose.cells/databar/negative_bar_format) | Hämtar NegativeBarFormat-objektet som är associerat med en villkorsstyrd formateringsregel för datafållen.|
| [min_cfvo](/cells/python-net/sv/aspose.cells/databar/min_cfvo) | Hämta eller ange detta DataBars minvärdeobjekt.<br/> Det går inte att ange null eller CFValueObject med typen FormatConditionValueType.Max.|
| [max_cfvo](/cells/python-net/sv/aspose.cells/databar/max_cfvo) | Hämta eller ange detta DataBars maxvärdeobjekt.<br/> Det går inte att ange null eller CFValueObject med typen FormatConditionValueType.Min.|
| [color](/cells/python-net/sv/aspose.cells/databar/color) | Hämta eller ställ in färgen på denna datafält.|
| [min_length](/cells/python-net/sv/aspose.cells/databar/min_length) | Representerar datastapelns minsta längd.|
| [max_length](/cells/python-net/sv/aspose.cells/databar/max_length) | Representerar den maximala längden på datastapeln.|
| [show_value](/cells/python-net/sv/aspose.cells/databar/show_value) |Hämta eller ställ in flaggan som anger om värdena för de celler där den här datafältet tillämpas ska visas.<br/> Standardvärdet är sant.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`to_image(self, cell, img_opts)`](/cells/python-net/sv/aspose.cells/databar/to_image/#aspose.cells.cell-aspose.cells.rendering.imageorprintoptions) | Rendera datastapeln i cellen till bildens byte-array.|



###  Exempel

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

###  Se även
* modul [`aspose.cells`](..)
