---
title: DataBar klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 400
url: /sv/aspose.cells/databar/
is_root: false
---
##  DataBar klass
 Beskriv DataBar villkorlig formateringsregel.
Denna regel för villkorlig formatering visar en graderad
datafältet i cellintervallet.



Typen DataBar avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [axis_color](/cells/python-net/sv/aspose.cells/databar/axis_color) | Får färgen på axeln för celler med villkorlig formatering som datafält.|
| [axis_position](/cells/python-net/sv/aspose.cells/databar/axis_position) | Hämtar eller ställer in positionen för axeln för datastaplarna som anges av en villkorlig formateringsregel.|
| [bar_fill_type](/cells/python-net/sv/aspose.cells/databar/bar_fill_type) | Hämtar eller ställer in hur ett datafält fylls med färg.|
| [direction](/cells/python-net/sv/aspose.cells/databar/direction) |Hämtar eller ställer in riktningen som datafältet visas.|
| [bar_border](/cells/python-net/sv/aspose.cells/databar/bar_border) | Hämtar ett objekt som anger gränsen för ett datafält.|
| [negative_bar_format](/cells/python-net/sv/aspose.cells/databar/negative_bar_format) | Hämtar NegativeBarFormat-objektet som är kopplat till en regel för villkorlig formatering av datafält.|
| [min_cfvo](/cells/python-net/sv/aspose.cells/databar/min_cfvo) | Hämta eller ställ in denna DataBars minvärdeobjekt.<br/> Det går inte att ställa in null eller CFValueObject med typen FormatConditionValueType.Max.|
| [max_cfvo](/cells/python-net/sv/aspose.cells/databar/max_cfvo) | Hämta eller ställ in denna DataBars maxvärdeobjekt.<br/> Det går inte att ställa in null eller CFValueObject med typen FormatConditionValueType.Min.|
| [color](/cells/python-net/sv/aspose.cells/databar/color) | Skaffa eller ställ in denna DataBars färg.|
| [min_length](/cells/python-net/sv/aspose.cells/databar/min_length) | Representerar den minsta längden på datafältet.|
| [max_length](/cells/python-net/sv/aspose.cells/databar/max_length) | Representerar den maximala längden på datafältet.|
| [show_value](/cells/python-net/sv/aspose.cells/databar/show_value) | Hämta eller ställ in flaggan som indikerar om värdena för cellerna som denna datafält används på ska visas.<br/> Standardvärdet är sant.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [to_image(cell, img_opts)](/cells/python-net/sv/aspose.cells/databar/to_image/#Cell-aspose.cells.rendering.ImageOrPrintOptions) | Rendera datafältet i cell till bildbyte-array.|



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
* modul [aspose.cells](..)
