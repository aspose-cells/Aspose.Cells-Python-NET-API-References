---
title: Sparkline klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 270
url: /sv/aspose.cells.charts/sparkline/
is_root: false
---
##  Sparkline klass
Ett miniatyrdiagram representerar ett litet diagram eller en grafik i en kalkylbladscell som ger en visuell representation av data.



Typen Sparkline avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [data_range](/cells/python-net/sv/aspose.cells.charts/sparkline/data_range) | Representerar dataintervallet för miniatyrdiagrammet.|
| [row](/cells/python-net/sv/aspose.cells.charts/sparkline/row) | Hämtar radindexet för miniatyrbilden.|
| [column](/cells/python-net/sv/aspose.cells.charts/sparkline/column) | Hämtar kolumnindexet för miniatyrbilden.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`to_image(self, file_name, options)`](/cells/python-net/sv/aspose.cells.charts/sparkline/to_image/#str-aspose.cells.rendering.imageorprintoptions) | Konverterar ett miniatyrdiagram till en bild.|
| [`to_image(self, stream, options)`](/cells/python-net/sv/aspose.cells.charts/sparkline/to_image/#io.rawiobase-aspose.cells.rendering.imageorprintoptions) | Konverterar ett miniatyrdiagram till en bild.|



###  Exempel

```python
from aspose.cells import CellArea, Workbook
from aspose.cells.charts import SparklineType
from aspose.cells.rendering import ImageOrPrintOptions

book = Workbook()
sheet = book.worksheets[0]
sheet.cells.get("A1").put_value(5)
sheet.cells.get("B1").put_value(2)
sheet.cells.get("C1").put_value(1)
sheet.cells.get("D1").put_value(3)
#  Define the CellArea
ca = CellArea()
ca.start_column = 4
ca.end_column = 4
ca.start_row = 0
ca.end_row = 0
idx = sheet.sparkline_groups.add(SparklineType.LINE, sheet.name + "!A1:D1", False, ca)
group = sheet.sparkline_groups[idx]
idx = group.sparklines.add(sheet.name + "!A1:D1", 0, 4)
line = group.sparklines[idx]
print("Saprkline data range: "  + line.data_range + ", row: "  + str(line.row) + ", column: "  + str(line.column))
line.to_image("output.png", ImageOrPrintOptions())

```

###  Se även
* modul [`aspose.cells.charts`](..)
