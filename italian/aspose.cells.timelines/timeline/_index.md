---
title: Timeline classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 10
url: /it/aspose.cells.timelines/timeline/
is_root: false
---
##  Timeline classe
Descrizione riassuntiva di Timeline Visualizza
A causa di MS Excel, Excel 2003 non supporta Timeline



Il tipo Timeline espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [caption](/cells/python-net/it/aspose.cells.timelines/timeline/caption) | Restituisce o imposta la didascalia della sequenza temporale specificata.|
| [shape](/cells/python-net/it/aspose.cells.timelines/timeline/shape) | Restituisce l'oggetto [`TimelineShape`](/cells/python-net/it/aspose.cells.drawing/timelineshape) associato a questa linea temporale. Di sola lettura.|
| [name](/cells/python-net/it/aspose.cells.timelines/timeline/name) | Restituisce o imposta il nome della linea temporale specificata|
| [left_pixel](/cells/python-net/it/aspose.cells.timelines/timeline/left_pixel) | Restituisce o imposta lo scostamento orizzontale della forma della sequenza temporale dalla sua colonna di sinistra, in pixel.|
| [top_pixel](/cells/python-net/it/aspose.cells.timelines/timeline/top_pixel) | Restituisce o imposta lo scostamento verticale della forma della sequenza temporale dalla sua riga superiore, in pixel.|
| [width_pixel](/cells/python-net/it/aspose.cells.timelines/timeline/width_pixel) | Restituisce o imposta la larghezza della sequenza temporale specificata, in pixel.|
| [height_pixel](/cells/python-net/it/aspose.cells.timelines/timeline/height_pixel) | Restituisce o imposta l'altezza della sequenza temporale specificata, in pixel.|



###  Esempio

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

###  Guarda anche
* modulo [`aspose.cells.timelines`](..)
* classe [`TimelineShape`](/cells/python-net/it/aspose.cells.drawing/timelineshape)
