---
title: TimelineCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells.timelines/timelinecollection/
is_root: false
---
##  TimelineCollection classe
Specifica la raccolta di tutti gli oggetti Timeline nel foglio di lavoro specificato.
A causa di MS Excel, Excel 2003 non supporta la sequenza temporale.



Il tipo TimelineCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells.timelines/timelinecollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco dell'array può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`add(self, pivot, row, column, base_field_name)`](/cells/python-net/it/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-int-int-str) | Aggiungi una nuova sequenza temporale utilizzando la tabella pivot come origine dati|
| [`add(self, pivot, dest_cell_name, base_field_name)`](/cells/python-net/it/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-str-str) | Aggiungi una nuova sequenza temporale utilizzando la tabella pivot come origine dati|
| [`add(self, pivot, row, column, base_field_index)`](/cells/python-net/it/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-int-int-int) | Aggiungi una nuova sequenza temporale utilizzando la tabella pivot come origine dati|
| [`add(self, pivot, dest_cell_name, base_field_index)`](/cells/python-net/it/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-str-int) | Aggiungi una nuova sequenza temporale utilizzando la tabella pivot come origine dati|
| [`add(self, pivot, row, column, base_field)`](/cells/python-net/it/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-int-int-aspose.cells.pivot.pivotfield) | Aggiungi una nuova sequenza temporale utilizzando la tabella pivot come origine dati|
| [`add(self, pivot, dest_cell_name, base_field)`](/cells/python-net/it/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-str-aspose.cells.pivot.pivotfield) | Aggiungi una nuova sequenza temporale utilizzando la tabella pivot come origine dati|
| [`copy_to(self, array)`](/cells/python-net/it/aspose.cells.timelines/timelinecollection/copy_to/#list) |Copia l'intero elenco di array in un elenco di array unidimensionale compatibile, iniziando dall'inizio dell'elenco di array di destinazione.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/it/aspose.cells.timelines/timelinecollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di array a un elenco di array unidimensionale compatibile, a partire dall'indice specificato dell'elenco di array di destinazione.|
| [`index_of(self, item, index)`](/cells/python-net/it/aspose.cells.timelines/timelinecollection/index_of/#aspose.cells.timelines.timeline-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dall'indice specificato all'ultimo elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.timelines/timelinecollection/index_of/#aspose.cells.timelines.timeline-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [`last_index_of(self, item)`](/cells/python-net/it/aspose.cells.timelines/timelinecollection/last_index_of/#aspose.cells.timelines.timeline) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intero elenco di array.|
| [`last_index_of(self, item, index)`](/cells/python-net/it/aspose.cells.timelines/timelinecollection/last_index_of/#aspose.cells.timelines.timeline-int) |Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dal primo elemento all'indice specificato.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.timelines/timelinecollection/last_index_of/#aspose.cells.timelines.timeline-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che contiene il numero specificato di elementi e termina all'indice specificato.|
| [`get(self, name)`](/cells/python-net/it/aspose.cells.timelines/timelinecollection/get/#str) | Ottiene la Timeline in base al nome della Timeline.|
| [`binary_search(self, item)`](/cells/python-net/it/aspose.cells.timelines/timelinecollection/binary_search/#aspose.cells.timelines.timeline) | Cerca un elemento nell'intero elenco dell'array ordinato utilizzando il comparatore predefinito e restituisce l'indice basato su zero dell'elemento.|



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
# do your business
book.save("out.xlsx")

```

###  Guarda anche
* modulo [`aspose.cells.timelines`](..)
