---
title: ListColumn Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 10
url: /de/aspose.cells.tables/listcolumn/
is_root: false
---
##  ListColumn Klasse
Stellt eine Spalte in einer Tabelle dar.



Der Typ ListColumn macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [name](/cells/python-net/de/aspose.cells.tables/listcolumn/name) | Ruft den Namen der Spalte ab und legt ihn fest.|
| [totals_calculation](/cells/python-net/de/aspose.cells.tables/listcolumn/totals_calculation) | Ruft den Berechnungstyp in der Zeile „Summen“ der Listenspalte ab und legt ihn fest.|
| [range](/cells/python-net/de/aspose.cells.tables/listcolumn/range) | Ruft den Bereich dieser Listenspalte ab.|
| [is_array_formula](/cells/python-net/de/aspose.cells.tables/listcolumn/is_array_formula) | Gibt an, ob es sich bei der Formel um eine Arrayformel handelt.|
| [formula](/cells/python-net/de/aspose.cells.tables/listcolumn/formula) | Ruft die Formel der Listenspalte ab und legt sie fest.|
| [totals_row_label](/cells/python-net/de/aspose.cells.tables/listcolumn/totals_row_label) | Ruft die Anzeigebeschriftungen der Gesamtzeile ab und legt sie fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`get_custom_totals_row_formula(self, is_r1c1, is_local)`](/cells/python-net/de/aspose.cells.tables/listcolumn/get_custom_totals_row_formula/#bool-bool) | Ruft die Formel der Summenzeile dieser Listenspalte ab.|
| [`set_custom_totals_row_formula(self, formula, is_r1c1, is_local)`](/cells/python-net/de/aspose.cells.tables/listcolumn/set_custom_totals_row_formula/#str-bool-bool) | Ruft die Formel der Summenzeile dieser Listenspalte ab.|
| [`get_custom_calculated_formula(self, is_r1c1, is_local)`](/cells/python-net/de/aspose.cells.tables/listcolumn/get_custom_calculated_formula/#bool-bool) | Ruft die Formel dieser Listenspalte ab.|
| [`set_custom_calculated_formula(self, formula, is_r1c1, is_local)`](/cells/python-net/de/aspose.cells.tables/listcolumn/set_custom_calculated_formula/#str-bool-bool) | Legt die Formel für diese Listenspalte fest.|
| [`get_data_style(self)`](/cells/python-net/de/aspose.cells.tables/listcolumn/get_data_style/#) | Ruft den Stil der Daten in dieser Spalte der Tabelle ab.|
| [`set_data_style(self, style)`](/cells/python-net/de/aspose.cells.tables/listcolumn/set_data_style/#aspose.cells.style) | Legt den Stil der Daten in dieser Spalte der Tabelle fest.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells.tables`](..)
