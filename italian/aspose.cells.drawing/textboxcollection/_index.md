---
title: TextBoxCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 670
url: /it/aspose.cells.drawing/textboxcollection/
is_root: false
---
##  TextBoxCollection classe
Incapsula una raccolta di [`TextBox`](/cells/python-net/it/aspose.cells.drawing/textbox) oggetti.



Il tipo TextBoxCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells.drawing/textboxcollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco dell'array può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/it/aspose.cells.drawing/textboxcollection/copy_to/#list) |Copia l'intero elenco di array in un elenco di array unidimensionale compatibile, iniziando dall'inizio dell'elenco di array di destinazione.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/it/aspose.cells.drawing/textboxcollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di array a un elenco di array unidimensionale compatibile, a partire dall'indice specificato dell'elenco di array di destinazione.|
| [`index_of(self, item, index)`](/cells/python-net/it/aspose.cells.drawing/textboxcollection/index_of/#aspose.cells.drawing.textbox-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dall'indice specificato all'ultimo elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.drawing/textboxcollection/index_of/#aspose.cells.drawing.textbox-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [`last_index_of(self, item)`](/cells/python-net/it/aspose.cells.drawing/textboxcollection/last_index_of/#aspose.cells.drawing.textbox) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intero elenco di array.|
| [`last_index_of(self, item, index)`](/cells/python-net/it/aspose.cells.drawing/textboxcollection/last_index_of/#aspose.cells.drawing.textbox-int) |Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dal primo elemento all'indice specificato.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.drawing/textboxcollection/last_index_of/#aspose.cells.drawing.textbox-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che contiene il numero specificato di elementi e termina all'indice specificato.|
| [`get(self, name)`](/cells/python-net/it/aspose.cells.drawing/textboxcollection/get/#str) | Ottiene l'elemento [`TextBox`](/cells/python-net/it/aspose.cells.drawing/textbox) tramite il nome.|
| [`add(self, upper_left_row, upper_left_column, height, width)`](/cells/python-net/it/aspose.cells.drawing/textboxcollection/add/#int-int-int-int) | Aggiunge una casella di testo alla raccolta.|
| [`binary_search(self, item)`](/cells/python-net/it/aspose.cells.drawing/textboxcollection/binary_search/#aspose.cells.drawing.textbox) | Cerca un elemento nell'intero elenco dell'array ordinato utilizzando il comparatore predefinito e restituisce l'indice basato su zero dell'elemento.|



###  Esempio

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# get collection object
textBoxCollection = workbook.worksheets[0].text_boxes
# add a textbox
textBoxCollection.add(1, 1, 50, 100)
for tbox in textBoxCollection:
    pass

```

###  Guarda anche
* modulo [`aspose.cells.drawing`](..)
* classe [`TextBox`](/cells/python-net/it/aspose.cells.drawing/textbox)
