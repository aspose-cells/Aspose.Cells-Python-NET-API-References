---
title: ChartCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 60
url: /it/aspose.cells.charts/chartcollection/
is_root: false
---
##  ChartCollection classe
Incapsula una raccolta di [`Chart`](/cells/python-net/it/aspose.cells.charts/chart) oggetti.



Il tipo ChartCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells.charts/chartcollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco dell'array può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`add(self, type, upper_left_row, upper_left_column, lower_right_row, lower_right_column)`](/cells/python-net/it/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-int-int-int-int) | Aggiunge un grafico alla raccolta.|
| [`add(self, type, data_range, top_row, left_column, right_row, bottom_column)`](/cells/python-net/it/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-str-int-int-int-int) | Aggiunge un grafico alla raccolta.|
| [`add(self, data, data_range, is_vertical, top_row, left_column, right_row, bottom_column)`](/cells/python-net/it/aspose.cells.charts/chartcollection/add/#bytes-str-bool-int-int-int-int) | Aggiunge un grafico con modello preimpostato.|
| [`add(self, type, data_range, is_vertical, top_row, left_column, right_row, bottom_column)`](/cells/python-net/it/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-str-bool-int-int-int-int) | Aggiunge un grafico alla raccolta.|
| [`get(self, index)`](/cells/python-net/it/aspose.cells.charts/chartcollection/get/#int) | Aggiungi API for Python tramite .Net poiché questo [indice int] non è supportato|
| [`get(self, name)`](/cells/python-net/it/aspose.cells.charts/chartcollection/get/#str) | Aggiungi API for Python tramite .Net poiché questo [string Chart] non è supportato|
| [`copy_to(self, array)`](/cells/python-net/it/aspose.cells.charts/chartcollection/copy_to/#list) |Copia l'intero elenco di array in un elenco di array unidimensionale compatibile, iniziando dall'inizio dell'elenco di array di destinazione.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/it/aspose.cells.charts/chartcollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di array a un elenco di array unidimensionale compatibile, a partire dall'indice specificato dell'elenco di array di destinazione.|
| [`index_of(self, item, index)`](/cells/python-net/it/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.chart-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dall'indice specificato all'ultimo elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.chart-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [`last_index_of(self, item)`](/cells/python-net/it/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intero elenco di array.|
| [`last_index_of(self, item, index)`](/cells/python-net/it/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart-int) |Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dal primo elemento all'indice specificato.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che contiene il numero specificato di elementi e termina all'indice specificato.|
| [`add_floating_chart(self, type, left, top, width, height)`](/cells/python-net/it/aspose.cells.charts/chartcollection/add_floating_chart/#aspose.cells.charts.charttype-int-int-int-int) | Aggiunge un grafico alla raccolta.|
| [`binary_search(self, item)`](/cells/python-net/it/aspose.cells.charts/chartcollection/binary_search/#aspose.cells.charts.chart) | Cerca un elemento nell'intero elenco dell'array ordinato utilizzando il comparatore predefinito e restituisce l'indice basato su zero dell'elemento.|



###  Esempio

```python
from aspose.cells import Workbook

workbook = Workbook()
charts = workbook.worksheets[0].charts

```

###  Guarda anche
* modulo [`aspose.cells.charts`](..)
* classe [`Chart`](/cells/python-net/it/aspose.cells.charts/chart)
