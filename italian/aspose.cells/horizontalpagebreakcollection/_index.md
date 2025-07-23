---
title: HorizontalPageBreakCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 770
url: /it/aspose.cells/horizontalpagebreakcollection/
is_root: false
---
##  HorizontalPageBreakCollection classe
Incapsula una raccolta di [`HorizontalPageBreak`](/cells/python-net/it/aspose.cells/horizontalpagebreak) oggetti.



Il tipo HorizontalPageBreakCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells/horizontalpagebreakcollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco dell'array può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`add(self, row, start_column, end_column)`](/cells/python-net/it/aspose.cells/horizontalpagebreakcollection/add/#int-int-int) | Aggiunge un'interruzione di pagina orizzontale alla raccolta.|
| [`add(self, row)`](/cells/python-net/it/aspose.cells/horizontalpagebreakcollection/add/#int) | Aggiunge un'interruzione di pagina orizzontale alla raccolta.|
| [`add(self, row, column)`](/cells/python-net/it/aspose.cells/horizontalpagebreakcollection/add/#int-int) | Aggiunge un'interruzione di pagina orizzontale alla raccolta.|
| [`add(self, cell_name)`](/cells/python-net/it/aspose.cells/horizontalpagebreakcollection/add/#str) | Aggiunge un'interruzione di pagina orizzontale alla raccolta.|
| [`copy_to(self, array)`](/cells/python-net/it/aspose.cells/horizontalpagebreakcollection/copy_to/#list) |Copia l'intero elenco di array in un elenco di array unidimensionale compatibile, iniziando dall'inizio dell'elenco di array di destinazione.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/it/aspose.cells/horizontalpagebreakcollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di array a un elenco di array unidimensionale compatibile, a partire dall'indice specificato dell'elenco di array di destinazione.|
| [`index_of(self, item, index)`](/cells/python-net/it/aspose.cells/horizontalpagebreakcollection/index_of/#aspose.cells.horizontalpagebreak-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dall'indice specificato all'ultimo elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells/horizontalpagebreakcollection/index_of/#aspose.cells.horizontalpagebreak-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [`last_index_of(self, item)`](/cells/python-net/it/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.horizontalpagebreak) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intero elenco di array.|
| [`last_index_of(self, item, index)`](/cells/python-net/it/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.horizontalpagebreak-int) |Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dal primo elemento all'indice specificato.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.horizontalpagebreak-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che contiene il numero specificato di elementi e termina all'indice specificato.|
| [`get(self, cell_name)`](/cells/python-net/it/aspose.cells/horizontalpagebreakcollection/get/#str) | Ottiene l'elemento [`HorizontalPageBreak`](/cells/python-net/it/aspose.cells/horizontalpagebreak) con il nome della cella specificato.|
| [`binary_search(self, item)`](/cells/python-net/it/aspose.cells/horizontalpagebreakcollection/binary_search/#aspose.cells.horizontalpagebreak) | Cerca un elemento nell'intero elenco dell'array ordinato utilizzando il comparatore predefinito e restituisce l'indice basato su zero dell'elemento.|



###  Esempio

```python
from aspose.cells import Workbook

excel = Workbook()
# Add a pagebreak at G5
excel.worksheets[0].horizontal_page_breaks.add("G5")
excel.worksheets[0].vertical_page_breaks.add("G5")

```

###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`HorizontalPageBreak`](/cells/python-net/it/aspose.cells/horizontalpagebreak)
