---
title: CommentCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 270
url: /it/aspose.cells/commentcollection/
is_root: false
---
##  CommentCollection classe
Incapsula una raccolta di [`Comment`](/cells/python-net/it/aspose.cells/comment) oggetti.



Il tipo CommentCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells/commentcollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco dell'array può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`add_threaded_comment(self, row, column, text, author)`](/cells/python-net/it/aspose.cells/commentcollection/add_threaded_comment/#int-int-str-aspose.cells.threadedcommentauthor) | Aggiunge un commento concatenato.|
| [`add_threaded_comment(self, cell_name, text, author)`](/cells/python-net/it/aspose.cells/commentcollection/add_threaded_comment/#str-str-aspose.cells.threadedcommentauthor) | Aggiunge un commento concatenato.|
| [`get_threaded_comments(self, row, column)`](/cells/python-net/it/aspose.cells/commentcollection/get_threaded_comments/#int-int) | Ottiene i commenti suddivisi in base all'indice di riga e di colonna.|
| [`get_threaded_comments(self, cell_name)`](/cells/python-net/it/aspose.cells/commentcollection/get_threaded_comments/#str) | Ottiene i commenti ordinati in base al nome della cella.|
| [`add(self, row, column)`](/cells/python-net/it/aspose.cells/commentcollection/add/#int-int) | Aggiunge un commento alla raccolta.|
| [`add(self, cell_name)`](/cells/python-net/it/aspose.cells/commentcollection/add/#str) | Aggiunge un commento alla raccolta.|
| [`get(self, row, column)`](/cells/python-net/it/aspose.cells/commentcollection/get/#int-int) | Aggiungi API for Python tramite .Net. poiché questo [int, int] non è supportato|
| [`get(self, index)`](/cells/python-net/it/aspose.cells/commentcollection/get/#int) | Ottiene l'elemento [`Comment`](/cells/python-net/it/aspose.cells/comment) all'indice specificato.|
| [`get(self, cell_name)`](/cells/python-net/it/aspose.cells/commentcollection/get/#str) | Ottiene l'elemento [`Comment`](/cells/python-net/it/aspose.cells/comment) nella cella specificata.|
| [`remove_at(self, cell_name)`](/cells/python-net/it/aspose.cells/commentcollection/remove_at/#str) | Rimuove il commento della cella specifica.|
| [`remove_at(self, row, column)`](/cells/python-net/it/aspose.cells/commentcollection/remove_at/#int-int) | Rimuove il commento della cella specifica.|
| [`copy_to(self, array)`](/cells/python-net/it/aspose.cells/commentcollection/copy_to/#list) |Copia l'intero elenco di array in un elenco di array unidimensionale compatibile, iniziando dall'inizio dell'elenco di array di destinazione.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/it/aspose.cells/commentcollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di array a un elenco di array unidimensionale compatibile, a partire dall'indice specificato dell'elenco di array di destinazione.|
| [`index_of(self, item, index)`](/cells/python-net/it/aspose.cells/commentcollection/index_of/#aspose.cells.comment-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dall'indice specificato all'ultimo elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells/commentcollection/index_of/#aspose.cells.comment-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [`last_index_of(self, item)`](/cells/python-net/it/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intero elenco di array.|
| [`last_index_of(self, item, index)`](/cells/python-net/it/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment-int) |Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dal primo elemento all'indice specificato.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che contiene il numero specificato di elementi e termina all'indice specificato.|
| [`binary_search(self, item)`](/cells/python-net/it/aspose.cells/commentcollection/binary_search/#aspose.cells.comment) | Cerca un elemento nell'intero elenco dell'array ordinato utilizzando il comparatore predefinito e restituisce l'indice basato su zero dell'elemento.|



###  Esempio

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments

```

###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`Comment`](/cells/python-net/it/aspose.cells/comment)
