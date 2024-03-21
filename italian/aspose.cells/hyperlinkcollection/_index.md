---
title: HyperlinkCollection classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 850
url: /it/aspose.cells/hyperlinkcollection/
is_root: false
---
##  HyperlinkCollection classe
Incapsula una raccolta di [`Hyperlink`](/cells/python-net/it/aspose.cells/hyperlink) oggetti.



Il tipo HyperlinkCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells/hyperlinkcollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco di matrici può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [add](/cells/python-net/it/aspose.cells/hyperlinkcollection/add/#int-int-int-int-str) | Aggiunge un collegamento ipertestuale a una cella specifica o a un intervallo di celle.|
| [add](/cells/python-net/it/aspose.cells/hyperlinkcollection/add/#str-int-int-str) | Aggiunge un collegamento ipertestuale a una cella specifica o a un intervallo di celle.|
| [add](/cells/python-net/it/aspose.cells/hyperlinkcollection/add/#str-str-str-str-str) | Aggiunge un collegamento ipertestuale a una cella specifica o a un intervallo di celle.|
| [copy_to](/cells/python-net/it/aspose.cells/hyperlinkcollection/copy_to/#list) | Copia l'intero elenco di matrici in un elenco di matrici unidimensionali compatibile, a partire dall'inizio dell'elenco di matrici di destinazione.|
| [copy_to](/cells/python-net/it/aspose.cells/hyperlinkcollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di matrici a un elenco di matrici unidimensionali compatibile, a partire dall'indice specificato dell'elenco di matrici di destinazione.|
| [index_of](/cells/python-net/it/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.Hyperlink-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero della prima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che si estende dall'indice specificato all'ultimo elemento.|
| [index_of](/cells/python-net/it/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.Hyperlink-int-int) |Cerca l'oggetto specificato e restituisce l'indice in base zero della prima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che inizia in corrispondenza dell'indice specificato e contiene il numero di elementi specificato.|
| [last_index_of](/cells/python-net/it/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intero elenco di matrici.|
| [last_index_of](/cells/python-net/it/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che si estende dal primo elemento all'indice specificato.|
| [last_index_of](/cells/python-net/it/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink-int-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che contiene il numero di elementi specificato e termina con l'indice specificato.|
| [binary_search](/cells/python-net/it/aspose.cells/hyperlinkcollection/binary_search/#aspose.cells.Hyperlink) | Cerca un elemento nell'intero elenco di array ordinato utilizzando l'operatore di confronto predefinito e restituisce l'indice in base zero dell'elemento.|



###  Esempio

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Get Hyperlinks Collection
hyperlinks = worksheet.hyperlinks
# Adding a hyperlink to a URL at "A1" cell
hyperlinks.add("A1", 1, 1, "http://www.aspose.com")
# Saving the Excel file
workbook.save("book1.xls")

```

###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`Hyperlink`](/cells/python-net/it/aspose.cells/hyperlink)
