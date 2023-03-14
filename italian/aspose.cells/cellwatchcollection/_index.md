---
title: classe CellWatchCollection
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 170
url: /it/aspose.cells/cellwatchcollection/
is_root: false
---
##  classe CellWatchCollection
Rappresenta la raccolta di celle di questo foglio di lavoro che viene osservata nella "finestra di controllo".



Il tipo CellWatchCollection espone i membri seguenti:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [CellWatchCollection()](/cells/python-net/it/aspose.cells/cellwatchcollection/__init__/#) | Costruisce una nuova istanza di CellWatchCollection|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells/cellwatchcollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco di matrici può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [add(row, column)](/cells/python-net/it/aspose.cells/cellwatchcollection/add/#int-int) | Aggiunge [CellWatch](/cells/python-net/it/aspose.cells/cellwatch) con riga e colonna.|
| [add(cell_name)](/cells/python-net/it/aspose.cells/cellwatchcollection/add/#str) | Aggiunge [CellWatch](/cells/python-net/it/aspose.cells/cellwatch) con il nome del cell.|
| [copy_to(array)](/cells/python-net/it/aspose.cells/cellwatchcollection/copy_to/#list) | Copia l'intero elenco di matrici in un elenco di matrici unidimensionale compatibile, a partire dall'inizio dell'elenco di matrici di destinazione.|
| [copy_to(index, array, array_index, count)](/cells/python-net/it/aspose.cells/cellwatchcollection/copy_to/#int-list-int-int) |Copia un intervallo di elementi dall'elenco di matrici a un elenco di matrici unidimensionale compatibile, a partire dall'indice specificato dell'elenco di matrici di destinazione.|
| [index_of(item, index)](/cells/python-net/it/aspose.cells/cellwatchcollection/index_of/#CellWatch-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero della prima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrici che si estende dall'indice specificato all'ultimo elemento.|
| [index_of(item, index, count)](/cells/python-net/it/aspose.cells/cellwatchcollection/index_of/#CellWatch-int-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero della prima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrici che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [last_index_of(item)](/cells/python-net/it/aspose.cells/cellwatchcollection/last_index_of/#CellWatch) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intero elenco di matrici.|
| [last_index_of(item, index)](/cells/python-net/it/aspose.cells/cellwatchcollection/last_index_of/#CellWatch-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrici che si estende dal primo elemento all'indice specificato.|
| [last_index_of(item, index, count)](/cells/python-net/it/aspose.cells/cellwatchcollection/last_index_of/#CellWatch-int-int) |Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrici che contiene il numero specificato di elementi e termina con l'indice specificato.|
| [binary_search(item)](/cells/python-net/it/aspose.cells/cellwatchcollection/binary_search/#CellWatch) | Cerca un elemento nell'intero elenco di matrici ordinate utilizzando l'operatore di confronto predefinito e restituisce l'indice in base zero dell'elemento.|



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
* modulo [aspose.cells](..)
* classe [CellWatch](/cells/python-net/it/aspose.cells/cellwatch)
