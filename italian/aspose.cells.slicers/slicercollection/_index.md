---
title: SlicerCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 50
url: /it/aspose.cells.slicers/slicercollection/
is_root: false
---
##  SlicerCollection classe
Specifica la raccolta di tutti gli oggetti Slicer nel foglio di lavoro specificato.



Il tipo SlicerCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells.slicers/slicercollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco dell'array può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`add(self, pivot, dest_cell_name, base_field_name)`](/cells/python-net/it/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-str-str) | Aggiungi un nuovo Slicer utilizzando la tabella pivot come origine dati|
| [`add(self, pivot, row, column, base_field_name)`](/cells/python-net/it/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-int-int-str) | Aggiungi un nuovo Slicer utilizzando la tabella pivot come origine dati|
| [`add(self, pivot, row, column, base_field_index)`](/cells/python-net/it/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-int-int-int) | Aggiungi un nuovo Slicer utilizzando la tabella pivot come origine dati|
| [`add(self, pivot, dest_cell_name, base_field_index)`](/cells/python-net/it/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-str-int) | Aggiungi un nuovo Slicer utilizzando la tabella pivot come origine dati|
| [`add(self, pivot, row, column, base_field)`](/cells/python-net/it/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-int-int-aspose.cells.pivot.pivotfield) | Aggiungi un nuovo Slicer utilizzando la tabella pivot come origine dati|
| [`add(self, pivot, dest_cell_name, base_field)`](/cells/python-net/it/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-str-aspose.cells.pivot.pivotfield) | Aggiungi un nuovo Slicer utilizzando la tabella pivot come origine dati|
| [`add(self, table, index, dest_cell_name)`](/cells/python-net/it/aspose.cells.slicers/slicercollection/add/#aspose.cells.tables.listobject-int-str) | Aggiungi un nuovo Slicer utilizzando ListObjet come origine dati|
| [`add(self, table, list_column, dest_cell_name)`](/cells/python-net/it/aspose.cells.slicers/slicercollection/add/#aspose.cells.tables.listobject-aspose.cells.tables.listcolumn-str) | Aggiungi un nuovo Slicer utilizzando ListObjet come origine dati|
| [`add(self, table, list_column, row, column)`](/cells/python-net/it/aspose.cells.slicers/slicercollection/add/#aspose.cells.tables.listobject-aspose.cells.tables.listcolumn-int-int) | Aggiungi un nuovo Slicer utilizzando ListObjet come origine dati|
| [`copy_to(self, array)`](/cells/python-net/it/aspose.cells.slicers/slicercollection/copy_to/#list) |Copia l'intero elenco di array in un elenco di array unidimensionale compatibile, iniziando dall'inizio dell'elenco di array di destinazione.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/it/aspose.cells.slicers/slicercollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di array a un elenco di array unidimensionale compatibile, a partire dall'indice specificato dell'elenco di array di destinazione.|
| [`index_of(self, item, index)`](/cells/python-net/it/aspose.cells.slicers/slicercollection/index_of/#aspose.cells.slicers.slicer-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dall'indice specificato all'ultimo elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.slicers/slicercollection/index_of/#aspose.cells.slicers.slicer-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [`last_index_of(self, item)`](/cells/python-net/it/aspose.cells.slicers/slicercollection/last_index_of/#aspose.cells.slicers.slicer) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intero elenco di array.|
| [`last_index_of(self, item, index)`](/cells/python-net/it/aspose.cells.slicers/slicercollection/last_index_of/#aspose.cells.slicers.slicer-int) |Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dal primo elemento all'indice specificato.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.slicers/slicercollection/last_index_of/#aspose.cells.slicers.slicer-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che contiene il numero specificato di elementi e termina all'indice specificato.|
| [`get(self, name)`](/cells/python-net/it/aspose.cells.slicers/slicercollection/get/#str) | Ottiene lo Slicer in base al nome dello Slicer.|
| [`binary_search(self, item)`](/cells/python-net/it/aspose.cells.slicers/slicercollection/binary_search/#aspose.cells.slicers.slicer) | Cerca un elemento nell'intero elenco dell'array ordinato utilizzando il comparatore predefinito e restituisce l'indice basato su zero dell'elemento.|



###  Esempio

```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType

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
pivot.refresh_data()
pivot.calculate_data()
slicers = sheet.slicers
tableIndex = sheet.list_objects.add("A1", "C9", True)
table = sheet.list_objects[tableIndex]
# do your business
book.save("out.xlsx")

```

###  Guarda anche
* modulo [`aspose.cells.slicers`](..)
