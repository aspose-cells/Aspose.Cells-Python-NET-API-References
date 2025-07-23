---
title: CellWatchCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 150
url: /it/aspose.cells/cellwatchcollection/
is_root: false
---
##  CellWatchCollection classe
Rappresenta l'insieme delle celle presenti su questo foglio di lavoro che vengono osservate nella 'finestra di controllo'.



Il tipo CellWatchCollection espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self)`](/cells/python-net/it/aspose.cells/cellwatchcollection/__init__/#) | Costruisce una nuova istanza di CellWatchCollection|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells/cellwatchcollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco dell'array può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`add(self, row, column)`](/cells/python-net/it/aspose.cells/cellwatchcollection/add/#int-int) | Somma [`CellWatch`](/cells/python-net/it/aspose.cells/cellwatch) con riga e colonna.|
| [`add(self, cell_name)`](/cells/python-net/it/aspose.cells/cellwatchcollection/add/#str) | Aggiunge [`CellWatch`](/cells/python-net/it/aspose.cells/cellwatch) con il nome della cella.|
| [`copy_to(self, array)`](/cells/python-net/it/aspose.cells/cellwatchcollection/copy_to/#list) |Copia l'intero elenco di array in un elenco di array unidimensionale compatibile, iniziando dall'inizio dell'elenco di array di destinazione.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/it/aspose.cells/cellwatchcollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di array a un elenco di array unidimensionale compatibile, a partire dall'indice specificato dell'elenco di array di destinazione.|
| [`index_of(self, item, index)`](/cells/python-net/it/aspose.cells/cellwatchcollection/index_of/#aspose.cells.cellwatch-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dall'indice specificato all'ultimo elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells/cellwatchcollection/index_of/#aspose.cells.cellwatch-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [`last_index_of(self, item)`](/cells/python-net/it/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intero elenco di array.|
| [`last_index_of(self, item, index)`](/cells/python-net/it/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch-int) |Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dal primo elemento all'indice specificato.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che contiene il numero specificato di elementi e termina all'indice specificato.|
| [`get(self, cell_name)`](/cells/python-net/it/aspose.cells/cellwatchcollection/get/#str) | Ottiene e imposta [`CellWatch`](/cells/python-net/it/aspose.cells/cellwatch) in base al nome della cella.|
| [`binary_search(self, item)`](/cells/python-net/it/aspose.cells/cellwatchcollection/binary_search/#aspose.cells.cellwatch) | Cerca un elemento nell'intero elenco dell'array ordinato utilizzando il comparatore predefinito e restituisce l'indice basato su zero dell'elemento.|



###  Esempio

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet.
sheet = workbook.worksheets[0]
#  Add Cell Watch Item into the watch window
sheet.cell_watches.add("B2")

```

###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`CellWatch`](/cells/python-net/it/aspose.cells/cellwatch)
