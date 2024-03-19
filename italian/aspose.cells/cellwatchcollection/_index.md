---
title: CellWatchCollection classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 180
url: /it/aspose.cells/cellwatchcollection/
is_root: false
---
##  CellWatchCollection classe
Rappresenta la raccolta di celle di questo foglio di lavoro osservate nella "finestra di controllo".



Il tipo CellWatchCollection espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [__init__](/cells/python-net/it/aspose.cells/cellwatchcollection/__init__/#) | Costruisce una nuova istanza di CellWatchCollection|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells/cellwatchcollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco di matrici può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [add](/cells/python-net/it/aspose.cells/cellwatchcollection/add/#int-int) | Aggiunge [`CellWatch`](/cells/python-net/it/aspose.cells/cellwatch) con riga e colonna.|
| [add](/cells/python-net/it/aspose.cells/cellwatchcollection/add/#str) | Aggiunge [`CellWatch`](/cells/python-net/it/aspose.cells/cellwatch) con il nome il di cell.|
| [copy_to](/cells/python-net/it/aspose.cells/cellwatchcollection/copy_to/#list) | Copia l'intero elenco di matrici in un elenco di matrici unidimensionali compatibile, a partire dall'inizio dell'elenco di matrici di destinazione.|
| [copy_to](/cells/python-net/it/aspose.cells/cellwatchcollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di matrici a un elenco di matrici unidimensionali compatibile, a partire dall'indice specificato dell'elenco di matrici di destinazione.|
| [index_of](/cells/python-net/it/aspose.cells/cellwatchcollection/index_of/#aspose.cells.CellWatch-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero della prima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che si estende dall'indice specificato all'ultimo elemento.|
| [index_of](/cells/python-net/it/aspose.cells/cellwatchcollection/index_of/#aspose.cells.CellWatch-int-int) |Cerca l'oggetto specificato e restituisce l'indice in base zero della prima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che inizia in corrispondenza dell'indice specificato e contiene il numero di elementi specificato.|
| [last_index_of](/cells/python-net/it/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.CellWatch) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intero elenco di matrici.|
| [last_index_of](/cells/python-net/it/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.CellWatch-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che si estende dal primo elemento all'indice specificato.|
| [last_index_of](/cells/python-net/it/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.CellWatch-int-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che contiene il numero di elementi specificato e termina con l'indice specificato.|
| [binary_search](/cells/python-net/it/aspose.cells/cellwatchcollection/binary_search/#aspose.cells.CellWatch) | Cerca un elemento nell'intero elenco di array ordinato utilizzando l'operatore di confronto predefinito e restituisce l'indice in base zero dell'elemento.|



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
