---
title: PivotTableCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 250
url: /it/aspose.cells.pivot/pivottablecollection/
is_root: false
---
##  PivotTableCollection classe
Rappresenta la raccolta di tutti gli oggetti tabella pivot nel foglio di lavoro specificato.



Il tipo PivotTableCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco dell'array può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`add(self, source_data, dest_cell_name, table_name)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/add/#str-str-str) | Aggiunge una nuova tabella pivot.|
| [`add(self, source_data, dest_cell_name, table_name, use_same_source)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/add/#str-str-str-bool) | Aggiunge una nuova tabella pivot.|
| [`add(self, source_data, row, column, table_name)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str) | Aggiunge una nuova tabella pivot.|
| [`add(self, source_data, row, column, table_name, use_same_source)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str-bool) | Aggiunge una nuova tabella pivot.|
| [`add(self, source_data, row, column, table_name, use_same_source, is_xls_classic)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str-bool-bool) | Aggiunge una nuova tabella pivot.|
| [`add(self, source_data, cell, table_name, use_same_source, is_xls_classic)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/add/#str-str-str-bool-bool) | Aggiunge una nuova tabella pivot.|
| [`add(self, pivot_table, dest_cell_name, table_name)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/add/#aspose.cells.pivot.pivottable-str-str) | Aggiunge una nuova tabella pivot basata su un'altra tabella pivot.|
| [`add(self, pivot_table, row, column, table_name)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/add/#aspose.cells.pivot.pivottable-int-int-str) | Aggiunge una nuova tabella pivot basata su un'altra tabella pivot.|
| [`add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/add/#list-bool-aspose.cells.pivot.pivotpagefields-str-str) | Aggiunge un nuovo oggetto tabella pivot alla raccolta con più intervalli di consolidamento come origine dati.|
| [`add(self, source_data, is_auto_page, page_fields, row, column, table_name)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/add/#list-bool-aspose.cells.pivot.pivotpagefields-int-int-str) | Aggiunge un nuovo oggetto tabella pivot alla raccolta con più intervalli di consolidamento come origine dati.|
| [`copy_to(self, array)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/copy_to/#list) |Copia l'intero elenco di array in un elenco di array unidimensionale compatibile, iniziando dall'inizio dell'elenco di array di destinazione.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di array a un elenco di array unidimensionale compatibile, a partire dall'indice specificato dell'elenco di array di destinazione.|
| [`index_of(self, item, index)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/index_of/#aspose.cells.pivot.pivottable-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dall'indice specificato all'ultimo elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/index_of/#aspose.cells.pivot.pivottable-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [`last_index_of(self, item)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.pivottable) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intero elenco di array.|
| [`last_index_of(self, item, index)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.pivottable-int) |Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dal primo elemento all'indice specificato.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.pivottable-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che contiene il numero specificato di elementi e termina all'indice specificato.|
| [`get(self, name)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/get/#str) | Ottiene il report della tabella pivot in base al nome della tabella pivot.|
| [`remove_pivot_table(self, pivot_table)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/remove_pivot_table/#aspose.cells.pivot.pivottable) | Elimina la tabella pivot specificata ed elimina i dati della tabella pivot|
| [`remove_pivot_table_data(self, pivot_table, keep_data)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/remove_pivot_table_data/#aspose.cells.pivot.pivottable-bool) | Elimina la tabella pivot specificata|
| [`remove_by_index(self, index)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/remove_by_index/#int) | Elimina la tabella pivot all'indice specificato ed elimina i dati della tabella pivot|
| [`remove_at(self, index, keep_data)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/remove_at/#int-bool) | Elimina la tabella pivot all'indice specificato|
| [`binary_search(self, item)`](/cells/python-net/it/aspose.cells.pivot/pivottablecollection/binary_search/#aspose.cells.pivot.pivottable) | Cerca un elemento nell'intero elenco dell'array ordinato utilizzando il comparatore predefinito e restituisce l'indice basato su zero dell'elemento.|



###  Esempio

```python
from aspose.cells import FormatConditionType, OperatorType, Workbook
from aspose.cells.pivot import PivotFieldType, PivotFilterType, PivotTableStyleType
from aspose.pydrawing import Color

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Change PivotField's attributes
rowField = pivot.row_fields[0]
rowField.display_name = "custom display name"
# Add PivotFilter
index = pivot.pivot_filters.add(0, PivotFilterType.COUNT)
filter = pivot.pivot_filters[index]
filter.auto_filter.filter_top10(0, False, False, 2)
# Add PivotFormatCondition
formatIndex = pivot.pivot_format_conditions.add()
pfc = pivot.pivot_format_conditions[formatIndex]
fcc = pfc.format_conditions
fcc.add_area(pivot.data_body_range)
idx = fcc.add_condition(FormatConditionType.CELL_VALUE)
fc = fcc[idx]
fc.formula1 = "100"
fc.operator = OperatorType.GREATER_OR_EQUAL
fc.style.background_color = Color.red
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  Guarda anche
* modulo [`aspose.cells.pivot`](..)
