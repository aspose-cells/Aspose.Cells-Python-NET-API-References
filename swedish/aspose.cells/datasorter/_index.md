---
title: DataSorter klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 410
url: /sv/aspose.cells/datasorter/
is_root: false
---
##  DataSorter klass
Sammanfattande beskrivning för DataSorter.



Typen DataSorter avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [keys](/cells/python-net/sv/aspose.cells/datasorter/keys) | Hämtar nyckellistan för datasorteraren.|
| [has_headers](/cells/python-net/sv/aspose.cells/datasorter/has_headers) | Representerar om intervallet har rubriker.|
| [key1](/cells/python-net/sv/aspose.cells/datasorter/key1) | Representerar första sorterade kolumnindex (absolut position, kolumn A är 0, B är 1, ...).|
| [order1](/cells/python-net/sv/aspose.cells/datasorter/order1) | Representerar sorteringsordningen för den första nyckeln.|
| [key2](/cells/python-net/sv/aspose.cells/datasorter/key2) | Representerar den andra sorterade kolumnindexet (absolut position, kolumn A är 0, B är 1, ...).|
| [order2](/cells/python-net/sv/aspose.cells/datasorter/order2) | Representerar sorteringsordningen för den andra nyckeln.|
| [key3](/cells/python-net/sv/aspose.cells/datasorter/key3) | Representerar tredje sorterade kolumnindex (absolut position, kolumn A är 0, B är 1, ...).|
| [order3](/cells/python-net/sv/aspose.cells/datasorter/order3) | Representerar sorteringsordningen för den tredje nyckeln.|
| [sort_left_to_right](/cells/python-net/sv/aspose.cells/datasorter/sort_left_to_right) |Sant betyder att sorteringsorienteringen är från vänster till höger.<br/>Falskt betyder att sorteringsorienteringen är från topp till botten.<br/> Standardvärdet är falskt.|
| [case_sensitive](/cells/python-net/sv/aspose.cells/datasorter/case_sensitive) | Hämtar och anger om det är skiftlägeskänsligt vid jämförelse av strängar.|
| [sort_as_number](/cells/python-net/sv/aspose.cells/datasorter/sort_as_number) | Anger om sortering av något som ser ut som ett tal.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`add_key(self, key, order)`](/cells/python-net/sv/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder) | Lägger till sorterat kolumnindex och sorteringsordning.|
| [`add_key(self, key, order, custom_list)`](/cells/python-net/sv/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder-str) | Lägger till sorterat kolumnindex och sorteringsordning med anpassad sorteringslista.|
| [`add_key(self, key, type, order, custom_list)`](/cells/python-net/sv/aspose.cells/datasorter/add_key/#int-aspose.cells.sortontype-aspose.cells.sortorder-any) | Lägger till sorterat kolumnindex och sorteringsordning med anpassad sorteringslista.|
| [`add_key(self, key, order, custom_list)`](/cells/python-net/sv/aspose.cells/datasorter/add_key/#int-aspose.cells.sortorder-list) | Lägger till sorterat kolumnindex och sorteringsordning med anpassad sorteringslista.|
| [`sort(self, cells, start_row, start_column, end_row, end_column)`](/cells/python-net/sv/aspose.cells/datasorter/sort/#aspose.cells.cells-int-int-int-int) | Sorterar områdets data.|
| [`sort(self, cells, area)`](/cells/python-net/sv/aspose.cells/datasorter/sort/#aspose.cells.cells-aspose.cells.cellarea) | Sortera områdets data.|
| [`sort(self)`](/cells/python-net/sv/aspose.cells/datasorter/sort/#) | Sortera informationen inom intervallet.|
| [`clear(self)`](/cells/python-net/sv/aspose.cells/datasorter/clear/#) | Rensa alla inställningar.|
| [`add_color_key(self, key, type, order, color)`](/cells/python-net/sv/aspose.cells/datasorter/add_color_key/#int-aspose.cells.sortontype-aspose.cells.sortorder-aspose.pydrawing.color) | Lägger till färgsorteringsnyckel.|



###  Exempel

```python
from aspose.cells import CellArea, SortOrder, Workbook

# Instantiate a new Workbook object.
workbook = Workbook("Book1.xls")
# Get the workbook datasorter object.
sorter = workbook.data_sorter
# Set the first order for datasorter object.
sorter.order1 = SortOrder.DESCENDING
# Define the first key.
sorter.key1 = 0
# Set the second order for datasorter object.
sorter.order2 = SortOrder.ASCENDING
# Define the second key.
sorter.key2 = 1
# Create a cells area (range).
ca = CellArea()
# Specify the start row index.
ca.start_row = 0
# Specify the start column index.
ca.start_column = 0
# Specify the last row index.
ca.end_row = 13
# Specify the last column index.
ca.end_column = 1
# Sort data in the specified data range (A1:B14)
sorter.sort(workbook.worksheets[0].cells, ca)
# Save the excel file.
workbook.save("outBook.xls")

```

###  Se även
* modul [`aspose.cells`](..)
