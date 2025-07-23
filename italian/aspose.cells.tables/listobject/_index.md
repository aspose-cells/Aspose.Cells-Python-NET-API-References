---
title: ListObject classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 30
url: /it/aspose.cells.tables/listobject/
is_root: false
---
##  ListObject classe
Rappresenta un oggetto elenco in un foglio di lavoro.
 L'oggetto ListObject è un membro della raccolta ListObjects.
La raccolta ListObjects contiene tutti gli oggetti elenco presenti in un foglio di lavoro.



Il tipo ListObject espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [start_row](/cells/python-net/it/aspose.cells.tables/listobject/start_row) | Ottiene la riga iniziale dell'intervallo.|
| [start_column](/cells/python-net/it/aspose.cells.tables/listobject/start_column) | Ottiene la colonna iniziale dell'intervallo.|
| [end_row](/cells/python-net/it/aspose.cells.tables/listobject/end_row) | Ottiene la riga finale dell'intervallo.|
| [end_column](/cells/python-net/it/aspose.cells.tables/listobject/end_column) | Ottiene la colonna finale dell'intervallo.|
| [list_columns](/cells/python-net/it/aspose.cells.tables/listobject/list_columns) | Ottiene ListColumns di ListObject.|
| [show_header_row](/cells/python-net/it/aspose.cells.tables/listobject/show_header_row) | Ottiene e imposta se questo ListObject mostra la riga di intestazione.|
| [show_totals](/cells/python-net/it/aspose.cells.tables/listobject/show_totals) | Ottiene e imposta se questo ListObject mostra la riga totale.|
| [data_range](/cells/python-net/it/aspose.cells.tables/listobject/data_range) | Ottiene l'intervallo di dati di ListObject.|
| [query_table](/cells/python-net/it/aspose.cells.tables/listobject/query_table) | Ottiene la QueryTable collegata.|
| [data_source_type](/cells/python-net/it/aspose.cells.tables/listobject/data_source_type) |Ottiene il tipo di origine dati della tabella.|
| [auto_filter](/cells/python-net/it/aspose.cells.tables/listobject/auto_filter) | Ottiene il filtro automatico.|
| [display_name](/cells/python-net/it/aspose.cells.tables/listobject/display_name) | Ottiene e imposta il nome visualizzato.|
| [comment](/cells/python-net/it/aspose.cells.tables/listobject/comment) | Ottiene e imposta il commento della tabella.|
| [show_table_style_first_column](/cells/python-net/it/aspose.cells.tables/listobject/show_table_style_first_column) | Indica se lo stile deve essere applicato alla prima colonna della tabella.|
| [show_table_style_last_column](/cells/python-net/it/aspose.cells.tables/listobject/show_table_style_last_column) | Indica se applicare lo stile all'ultima colonna della tabella.|
| [show_table_style_row_stripes](/cells/python-net/it/aspose.cells.tables/listobject/show_table_style_row_stripes) | Indica se viene applicata la formattazione a strisce di riga.|
| [show_table_style_column_stripes](/cells/python-net/it/aspose.cells.tables/listobject/show_table_style_column_stripes) | Indica se viene applicata la formattazione a strisce di colonna.|
| [table_style_type](/cells/python-net/it/aspose.cells.tables/listobject/table_style_type) | Ottiene e lo stile della tabella incorporato.|
| [table_style_name](/cells/python-net/it/aspose.cells.tables/listobject/table_style_name) | Ottiene e imposta il nome dello stile della tabella.|
| [xml_map](/cells/python-net/it/aspose.cells.tables/listobject/xml_map) | Ottiene un [`ListObject.xml_map`](/cells/python-net/it/aspose.cells.tables/listobject#xml_map) utilizzato per questa lista.|
| [alternative_text](/cells/python-net/it/aspose.cells.tables/listobject/alternative_text) | Ottiene e imposta il testo alternativo.|
| [alternative_description](/cells/python-net/it/aspose.cells.tables/listobject/alternative_description) | Ottiene e imposta la descrizione alternativa.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`put_cell_value(self, row_offset, column_offset, value)`](/cells/python-net/it/aspose.cells.tables/listobject/put_cell_value/#int-int-any) | Inserisci il valore nella cella.|
| [`put_cell_value(self, row_offset, column_offset, value, is_totals_row_label)`](/cells/python-net/it/aspose.cells.tables/listobject/put_cell_value/#int-int-any-bool) | Inserisci il valore nella cella.|
| [`put_cell_formula(self, row_offset, column_offset, formula)`](/cells/python-net/it/aspose.cells.tables/listobject/put_cell_formula/#int-int-str) | Inserisci la formula nella cella della tabella.|
| [`put_cell_formula(self, row_offset, column_offset, formula, is_totals_row_formula)`](/cells/python-net/it/aspose.cells.tables/listobject/put_cell_formula/#int-int-str-bool) | Inserisci la formula nella cella della tabella.|
| [`convert_to_range(self)`](/cells/python-net/it/aspose.cells.tables/listobject/convert_to_range/#) | Converti la tabella in intervallo.|
| [`convert_to_range(self, options)`](/cells/python-net/it/aspose.cells.tables/listobject/convert_to_range/#aspose.cells.tables.tabletorangeoptions) | Converti la tabella in intervallo.|
| [`resize(self, start_row, start_column, end_row, end_column, has_headers)`](/cells/python-net/it/aspose.cells.tables/listobject/resize/#int-int-int-int-bool) | Ridimensiona l'intervallo dell'oggetto elenco.|
| [`update_column_name(self)`](/cells/python-net/it/aspose.cells.tables/listobject/update_column_name/#) | Aggiorna i nomi di tutte le colonne dell'elenco dal foglio di lavoro.|
| [`filter(self)`](/cells/python-net/it/aspose.cells.tables/listobject/filter/#) | Filtra la tabella.|
| [`apply_style_to_range(self)`](/cells/python-net/it/aspose.cells.tables/listobject/apply_style_to_range/#) | Applica lo stile tabella all'intervallo.|



###  Esempio

```python
from aspose.cells import CellsHelper, Workbook
from aspose.cells.tables import TotalsCalculation

workbook = Workbook()
cells = workbook.worksheets[0].cells
for i in range(5):
    cells.get(0, i).put_value(CellsHelper.column_index_to_name(i))
for row in range(1, 10):
    for column in range(5):
        cells.get(row, column).put_value(row * column)
tables = workbook.worksheets[0].list_objects
index = tables.add(0, 0, 9, 4, True)
table = tables[0]
table.show_totals = True
table.list_columns[4].totals_calculation = TotalsCalculation.SUM
workbook.save(r"Book1.xlsx")

```

###  Guarda anche
* modulo [`aspose.cells.tables`](..)
