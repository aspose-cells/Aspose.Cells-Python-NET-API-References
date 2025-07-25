---
title: ListColumn classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 10
url: /it/aspose.cells.tables/listcolumn/
is_root: false
---
##  ListColumn classe
Rappresenta una colonna in una tabella.



Il tipo ListColumn espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [name](/cells/python-net/it/aspose.cells.tables/listcolumn/name) | Ottiene e imposta il nome della colonna.|
| [totals_calculation](/cells/python-net/it/aspose.cells.tables/listcolumn/totals_calculation) | Ottiene e imposta il tipo di calcolo nella riga Totali della colonna elenco.|
| [range](/cells/python-net/it/aspose.cells.tables/listcolumn/range) | Ottiene l'intervallo di questa colonna dell'elenco.|
| [is_array_formula](/cells/python-net/it/aspose.cells.tables/listcolumn/is_array_formula) | Indica se la formula è una formula matriciale.|
| [formula](/cells/python-net/it/aspose.cells.tables/listcolumn/formula) | Ottiene e imposta la formula della colonna dell'elenco.|
| [totals_row_label](/cells/python-net/it/aspose.cells.tables/listcolumn/totals_row_label) | Ottiene e imposta le etichette di visualizzazione della riga totale.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`get_custom_totals_row_formula(self, is_r1c1, is_local)`](/cells/python-net/it/aspose.cells.tables/listcolumn/get_custom_totals_row_formula/#bool-bool) | Ottiene la formula della riga dei totali di questa colonna dell'elenco.|
| [`set_custom_totals_row_formula(self, formula, is_r1c1, is_local)`](/cells/python-net/it/aspose.cells.tables/listcolumn/set_custom_totals_row_formula/#str-bool-bool) | Ottiene la formula della riga dei totali di questa colonna dell'elenco.|
| [`get_custom_calculated_formula(self, is_r1c1, is_local)`](/cells/python-net/it/aspose.cells.tables/listcolumn/get_custom_calculated_formula/#bool-bool) | Ottiene la formula di questa colonna dell'elenco.|
| [`set_custom_calculated_formula(self, formula, is_r1c1, is_local)`](/cells/python-net/it/aspose.cells.tables/listcolumn/set_custom_calculated_formula/#str-bool-bool) | Imposta la formula per questa colonna dell'elenco.|
| [`get_data_style(self)`](/cells/python-net/it/aspose.cells.tables/listcolumn/get_data_style/#) | Ottiene lo stile dei dati in questa colonna della tabella.|
| [`set_data_style(self, style)`](/cells/python-net/it/aspose.cells.tables/listcolumn/set_data_style/#aspose.cells.style) | Imposta lo stile dei dati in questa colonna della tabella.|



###  Esempio

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

###  Guarda anche
* modulo [`aspose.cells.tables`](..)
