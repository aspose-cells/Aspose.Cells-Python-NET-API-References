---
title: CheckBoxCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 100
url: /it/aspose.cells.drawing/checkboxcollection/
is_root: false
---
##  CheckBoxCollection classe
Rappresenta una raccolta di [`CheckBox`](/cells/python-net/it/aspose.cells.drawing/checkbox) oggetti in un foglio di lavoro.



Il tipo CheckBoxCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells.drawing/checkboxcollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco dell'array può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/it/aspose.cells.drawing/checkboxcollection/copy_to/#list) |Copia l'intero elenco di array in un elenco di array unidimensionale compatibile, iniziando dall'inizio dell'elenco di array di destinazione.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/it/aspose.cells.drawing/checkboxcollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di array a un elenco di array unidimensionale compatibile, a partire dall'indice specificato dell'elenco di array di destinazione.|
| [`index_of(self, item, index)`](/cells/python-net/it/aspose.cells.drawing/checkboxcollection/index_of/#aspose.cells.drawing.checkbox-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dall'indice specificato all'ultimo elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.drawing/checkboxcollection/index_of/#aspose.cells.drawing.checkbox-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [`last_index_of(self, item)`](/cells/python-net/it/aspose.cells.drawing/checkboxcollection/last_index_of/#aspose.cells.drawing.checkbox) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intero elenco di array.|
| [`last_index_of(self, item, index)`](/cells/python-net/it/aspose.cells.drawing/checkboxcollection/last_index_of/#aspose.cells.drawing.checkbox-int) |Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dal primo elemento all'indice specificato.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.drawing/checkboxcollection/last_index_of/#aspose.cells.drawing.checkbox-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che contiene il numero specificato di elementi e termina all'indice specificato.|
| [`add(self, upper_left_row, upper_left_column, height, width)`](/cells/python-net/it/aspose.cells.drawing/checkboxcollection/add/#int-int-int-int) | Aggiunge un checkBox alla raccolta.|
| [`binary_search(self, item)`](/cells/python-net/it/aspose.cells.drawing/checkboxcollection/binary_search/#aspose.cells.drawing.checkbox) | Cerca un elemento nell'intero elenco dell'array ordinato utilizzando il comparatore predefinito e restituisce l'indice basato su zero dell'elemento.|



###  Esempio

```python
from aspose.cells import Workbook

# Create a new Workbook.
workbook = Workbook()
# Get the first worksheet in the workbook.
sheet = workbook.worksheets[0]
index = sheet.check_boxes.add(15, 15, 20, 100)
checkBox = sheet.check_boxes[index]
checkBox.text = "Check Box 1"

```

###  Guarda anche
* modulo [`aspose.cells.drawing`](..)
* classe [`CheckBox`](/cells/python-net/it/aspose.cells.drawing/checkbox)
