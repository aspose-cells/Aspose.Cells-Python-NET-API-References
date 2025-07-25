---
title: Sparkline Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 270
url: /de/aspose.cells.charts/sparkline/
is_root: false
---
##  Sparkline Klasse
Eine Sparkline stellt ein kleines Diagramm oder eine Grafik in einer Arbeitsblattzelle dar, die eine visuelle Darstellung von Daten bietet.



Der Typ Sparkline macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [data_range](/cells/python-net/de/aspose.cells.charts/sparkline/data_range) | Stellt den Datenbereich der Sparkline dar.|
| [row](/cells/python-net/de/aspose.cells.charts/sparkline/row) | Ruft den Zeilenindex der Sparkline ab.|
| [column](/cells/python-net/de/aspose.cells.charts/sparkline/column) | Ruft den Spaltenindex der Sparkline ab.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`to_image(self, file_name, options)`](/cells/python-net/de/aspose.cells.charts/sparkline/to_image/#str-aspose.cells.rendering.imageorprintoptions) | Wandelt eine Sparkline in ein Bild um.|
| [`to_image(self, stream, options)`](/cells/python-net/de/aspose.cells.charts/sparkline/to_image/#io.rawiobase-aspose.cells.rendering.imageorprintoptions) | Wandelt eine Sparkline in ein Bild um.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells.charts`](..)
