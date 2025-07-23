---
title: PictureCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 440
url: /it/aspose.cells.drawing/picturecollection/
is_root: false
---
##  PictureCollection classe
Incapsula una raccolta di [`Picture`](/cells/python-net/it/aspose.cells.drawing/picture) oggetti.



Il tipo PictureCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells.drawing/picturecollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco dell'array può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream)`](/cells/python-net/it/aspose.cells.drawing/picturecollection/add/#int-int-int-int-io.rawiobase) | Aggiunge un'immagine alla raccolta.|
| [`add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name)`](/cells/python-net/it/aspose.cells.drawing/picturecollection/add/#int-int-int-int-str) | Aggiunge un'immagine alla raccolta.|
| [`add(self, upper_left_row, upper_left_column, stream)`](/cells/python-net/it/aspose.cells.drawing/picturecollection/add/#int-int-io.rawiobase) | Aggiunge un'immagine alla raccolta.|
| [`add(self, upper_left_row, upper_left_column, file_name)`](/cells/python-net/it/aspose.cells.drawing/picturecollection/add/#int-int-str) | Aggiunge un'immagine alla raccolta.|
| [`add(self, upper_left_row, upper_left_column, stream, width_scale, height_scale)`](/cells/python-net/it/aspose.cells.drawing/picturecollection/add/#int-int-io.rawiobase-int-int) | Aggiunge un'immagine alla raccolta.|
| [`add(self, upper_left_row, upper_left_column, file_name, width_scale, height_scale)`](/cells/python-net/it/aspose.cells.drawing/picturecollection/add/#int-int-str-int-int) | Aggiunge un'immagine alla raccolta.|
| [`copy_to(self, array)`](/cells/python-net/it/aspose.cells.drawing/picturecollection/copy_to/#list) |Copia l'intero elenco di array in un elenco di array unidimensionale compatibile, iniziando dall'inizio dell'elenco di array di destinazione.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/it/aspose.cells.drawing/picturecollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di array a un elenco di array unidimensionale compatibile, a partire dall'indice specificato dell'elenco di array di destinazione.|
| [`index_of(self, item, index)`](/cells/python-net/it/aspose.cells.drawing/picturecollection/index_of/#aspose.cells.drawing.picture-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dall'indice specificato all'ultimo elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.drawing/picturecollection/index_of/#aspose.cells.drawing.picture-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [`last_index_of(self, item)`](/cells/python-net/it/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intero elenco di array.|
| [`last_index_of(self, item, index)`](/cells/python-net/it/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture-int) |Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dal primo elemento all'indice specificato.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che contiene il numero specificato di elementi e termina all'indice specificato.|
| [`camera(self, row, column, range)`](/cells/python-net/it/aspose.cells.drawing/picturecollection/camera/#int-int-str) | Scatta una foto del poligono di tiro.|
| [`binary_search(self, item)`](/cells/python-net/it/aspose.cells.drawing/picturecollection/binary_search/#aspose.cells.drawing.picture) | Cerca un elemento nell'intero elenco dell'array ordinato utilizzando il comparatore predefinito e restituisce l'indice basato su zero dell'elemento.|



###  Esempio

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# get PictureCollection
pictures = workbook.worksheets[0].pictures
# do your business
# Save the excel file.
workbook.save("result.xlsx")

```

###  Guarda anche
* modulo [`aspose.cells.drawing`](..)
* classe [`Picture`](/cells/python-net/it/aspose.cells.drawing/picture)
