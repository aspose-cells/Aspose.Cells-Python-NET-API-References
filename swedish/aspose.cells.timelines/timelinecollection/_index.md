---
title: TimelineCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells.timelines/timelinecollection/
is_root: false
---
##  TimelineCollection klass
Anger samlingen av alla tidslinjeobjekt på det angivna kalkylbladet.
På grund av MS Excel stöder inte Excel 2003 tidslinje.



Typen TimelineCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [capacity](/cells/python-net/sv/aspose.cells.timelines/timelinecollection/capacity) | Hämtar eller anger antalet element som arraylistan kan innehålla.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`add(self, pivot, row, column, base_field_name)`](/cells/python-net/sv/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-int-int-str) | Lägg till en ny tidslinje med hjälp av pivottabell som datakälla|
| [`add(self, pivot, dest_cell_name, base_field_name)`](/cells/python-net/sv/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-str-str) | Lägg till en ny tidslinje med hjälp av pivottabell som datakälla|
| [`add(self, pivot, row, column, base_field_index)`](/cells/python-net/sv/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-int-int-int) | Lägg till en ny tidslinje med hjälp av pivottabell som datakälla|
| [`add(self, pivot, dest_cell_name, base_field_index)`](/cells/python-net/sv/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-str-int) | Lägg till en ny tidslinje med hjälp av pivottabell som datakälla|
| [`add(self, pivot, row, column, base_field)`](/cells/python-net/sv/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-int-int-aspose.cells.pivot.pivotfield) | Lägg till en ny tidslinje med hjälp av pivottabell som datakälla|
| [`add(self, pivot, dest_cell_name, base_field)`](/cells/python-net/sv/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-str-aspose.cells.pivot.pivotfield) | Lägg till en ny tidslinje med hjälp av pivottabell som datakälla|
| [`copy_to(self, array)`](/cells/python-net/sv/aspose.cells.timelines/timelinecollection/copy_to/#list) |Kopierar hela arraylistan till en kompatibel endimensionell arraylista, med början i början av målarraylistan.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/sv/aspose.cells.timelines/timelinecollection/copy_to/#int-list-int-int) | Kopierar ett elementområde från arraylistan till en kompatibel endimensionell arraylista, med början vid det angivna indexet för målarraylistan.|
| [`index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.timelines/timelinecollection/index_of/#aspose.cells.timelines.timeline-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som sträcker sig från det angivna indexet till det sista elementet.|
| [`index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.timelines/timelinecollection/index_of/#aspose.cells.timelines.timeline-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom elementintervallet i arraylistan som börjar vid det angivna indexet och innehåller det angivna antalet element.|
| [`last_index_of(self, item)`](/cells/python-net/sv/aspose.cells.timelines/timelinecollection/last_index_of/#aspose.cells.timelines.timeline) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom hela arraylistan.|
| [`last_index_of(self, item, index)`](/cells/python-net/sv/aspose.cells.timelines/timelinecollection/last_index_of/#aspose.cells.timelines.timeline-int) |Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som sträcker sig från det första elementet till det angivna indexet.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/sv/aspose.cells.timelines/timelinecollection/last_index_of/#aspose.cells.timelines.timeline-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom elementintervallet i arraylistan som innehåller det angivna antalet element och slutar vid det angivna indexet.|
| [`get(self, name)`](/cells/python-net/sv/aspose.cells.timelines/timelinecollection/get/#str) | Hämtar tidslinjen efter tidslinjens namn.|
| [`binary_search(self, item)`](/cells/python-net/sv/aspose.cells.timelines/timelinecollection/binary_search/#aspose.cells.timelines.timeline) | Söker igenom hela den sorterade arraylistan efter ett element med hjälp av standardjämföraren och returnerar elementets nollbaserade index.|



###  Exempel

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
# do your business
book.save("out.xlsx")

```

###  Se även
* modul [`aspose.cells.timelines`](..)
