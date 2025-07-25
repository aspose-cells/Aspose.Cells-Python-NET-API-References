---
title: ListColumn klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 10
url: /sv/aspose.cells.tables/listcolumn/
is_root: false
---
##  ListColumn klass
Representerar en kolumn i en tabell.



Typen ListColumn avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [name](/cells/python-net/sv/aspose.cells.tables/listcolumn/name) | Hämtar och anger namnet på kolumnen.|
| [totals_calculation](/cells/python-net/sv/aspose.cells.tables/listcolumn/totals_calculation) | Hämtar och anger beräkningstypen på raden Totaler i listkolumnen.|
| [range](/cells/python-net/sv/aspose.cells.tables/listcolumn/range) | Hämtar intervallet för den här listkolumnen.|
| [is_array_formula](/cells/python-net/sv/aspose.cells.tables/listcolumn/is_array_formula) | Anger om formeln är en arrayformel.|
| [formula](/cells/python-net/sv/aspose.cells.tables/listcolumn/formula) | Hämtar och ställer in formeln för listkolumnen.|
| [totals_row_label](/cells/python-net/sv/aspose.cells.tables/listcolumn/totals_row_label) | Hämtar och ställer in visningsetiketterna för den totala raden.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`get_custom_totals_row_formula(self, is_r1c1, is_local)`](/cells/python-net/sv/aspose.cells.tables/listcolumn/get_custom_totals_row_formula/#bool-bool) | Hämtar formeln för totalraden i den här listkolumnen.|
| [`set_custom_totals_row_formula(self, formula, is_r1c1, is_local)`](/cells/python-net/sv/aspose.cells.tables/listcolumn/set_custom_totals_row_formula/#str-bool-bool) | Hämtar formeln för totalraden i den här listkolumnen.|
| [`get_custom_calculated_formula(self, is_r1c1, is_local)`](/cells/python-net/sv/aspose.cells.tables/listcolumn/get_custom_calculated_formula/#bool-bool) | Hämtar formeln för den här listkolumnen.|
| [`set_custom_calculated_formula(self, formula, is_r1c1, is_local)`](/cells/python-net/sv/aspose.cells.tables/listcolumn/set_custom_calculated_formula/#str-bool-bool) | Anger formeln för den här listkolumnen.|
| [`get_data_style(self)`](/cells/python-net/sv/aspose.cells.tables/listcolumn/get_data_style/#) | Hämtar formatet för data i den här kolumnen i tabellen.|
| [`set_data_style(self, style)`](/cells/python-net/sv/aspose.cells.tables/listcolumn/set_data_style/#aspose.cells.style) | Anger formatet för data i den här kolumnen i tabellen.|



###  Exempel

```python
from aspose.cells import CellsHelper, Workbook
from aspose.cells.tables import TotalsCalculation

workbook = Workbook()
cells = workbook.worksheets[0].cells
for i in range(5):
    cells.get(0, i).put_value(CellsHelper.column_index_to_name(i))
for row in range(1, 10):
    for column in range(4):
        cells.get(row, column).put_value(row * column)
tables = workbook.worksheets[0].list_objects
index = tables.add(0, 0, 9, 4, True)
table = tables[0]
table.show_totals = True
listColumn = table.list_columns[4]
listColumn.totals_calculation = TotalsCalculation.SUM
listColumn.formula = "=[A]"
workbook.save(r"Book1.xlsx")

```

###  Se även
* modul [`aspose.cells.tables`](..)
