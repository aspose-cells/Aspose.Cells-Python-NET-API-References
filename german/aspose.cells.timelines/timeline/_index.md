---
title: Timeline Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 10
url: /de/aspose.cells.timelines/timeline/
is_root: false
---
##  Timeline Klasse
Zusammenfassende Beschreibung von Timeline Ansicht
Aufgrund von MS Excel unterstützt Excel 2003 nicht Timeline



Der Typ Timeline macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [caption](/cells/python-net/de/aspose.cells.timelines/timeline/caption) | Gibt die Beschriftung der angegebenen Zeitleiste zurück oder legt sie fest.|
| [shape](/cells/python-net/de/aspose.cells.timelines/timeline/shape) | Gibt das mit dieser Zeitleiste verknüpfte Objekt [`TimelineShape`](/cells/python-net/de/aspose.cells.drawing/timelineshape) zurück. Schreibgeschützt.|
| [name](/cells/python-net/de/aspose.cells.timelines/timeline/name) | Gibt den Namen der angegebenen Timeline zurück oder setzt ihn|
| [left_pixel](/cells/python-net/de/aspose.cells.timelines/timeline/left_pixel) | Gibt den horizontalen Versatz der Zeitleistenform von ihrer linken Spalte in Pixeln zurück oder legt ihn fest.|
| [top_pixel](/cells/python-net/de/aspose.cells.timelines/timeline/top_pixel) | Gibt den vertikalen Versatz der Zeitleistenform von ihrer obersten Zeile in Pixeln zurück oder legt ihn fest.|
| [width_pixel](/cells/python-net/de/aspose.cells.timelines/timeline/width_pixel) | Gibt die Breite der angegebenen Zeitleiste in Pixeln zurück oder legt sie fest.|
| [height_pixel](/cells/python-net/de/aspose.cells.timelines/timeline/height_pixel) | Gibt die Höhe der angegebenen Zeitleiste in Pixeln zurück oder legt sie fest.|



###  Beispiel

```python
from aspose.cells import CellsFactory, Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType
from datetime import datetime

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
# Create date style
dateStyle = CellsFactory().create_style()
dateStyle.custom = "m/d/yyyy"
cells.get(0, 1).value = "date"
cells.get(1, 1).value = datetime(2021, 2, 5)
cells.get(2, 1).value = datetime(2022, 3, 8)
cells.get(3, 1).value = datetime(2023, 4, 10)
cells.get(4, 1).value = datetime(2024, 5, 16)
# Set date style
cells.get(1, 1).set_style(dateStyle)
cells.get(2, 1).set_style(dateStyle)
cells.get(3, 1).set_style(dateStyle)
cells.get(4, 1).set_style(dateStyle)
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
pivots = sheet.pivot_tables
# Add a PivotTable
pivotIndex = pivots.add("=Sheet1!A1:C5", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "date")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Refresh PivotTable data
pivot.refresh_data()
pivot.calculate_data()
# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, 10, 5, "date")
# Get Timeline object
timelineObj = sheet.timelines[0]
# do your business
book.save("out.xlsx")

```

###  Siehe auch
* Modul [`aspose.cells.timelines`](..)
* Klasse [`TimelineShape`](/cells/python-net/de/aspose.cells.drawing/timelineshape)
