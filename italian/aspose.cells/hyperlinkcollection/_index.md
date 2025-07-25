---
title: HyperlinkCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 830
url: /it/aspose.cells/hyperlinkcollection/
is_root: false
---
##  HyperlinkCollection classe
Incapsula una raccolta di [`Hyperlink`](/cells/python-net/it/aspose.cells/hyperlink) oggetti.



Il tipo HyperlinkCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells/hyperlinkcollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco dell'array può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`add(self, first_row, first_column, total_rows, total_columns, address)`](/cells/python-net/it/aspose.cells/hyperlinkcollection/add/#int-int-int-int-str) | Aggiunge un collegamento ipertestuale a una cella specificata o a un intervallo di celle.|
| [`add(self, cell_name, total_rows, total_columns, address)`](/cells/python-net/it/aspose.cells/hyperlinkcollection/add/#str-int-int-str) | Aggiunge un collegamento ipertestuale a una cella specificata o a un intervallo di celle.|
| [`add(self, start_cell_name, end_cell_name, address, text_to_display, screen_tip)`](/cells/python-net/it/aspose.cells/hyperlinkcollection/add/#str-str-str-str-str) | Aggiunge un collegamento ipertestuale a una cella specificata o a un intervallo di celle.|
| [`copy_to(self, array)`](/cells/python-net/it/aspose.cells/hyperlinkcollection/copy_to/#list) |Copia l'intero elenco di array in un elenco di array unidimensionale compatibile, iniziando dall'inizio dell'elenco di array di destinazione.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/it/aspose.cells/hyperlinkcollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di array a un elenco di array unidimensionale compatibile, a partire dall'indice specificato dell'elenco di array di destinazione.|
| [`index_of(self, item, index)`](/cells/python-net/it/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.hyperlink-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dall'indice specificato all'ultimo elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.hyperlink-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [`last_index_of(self, item)`](/cells/python-net/it/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.hyperlink) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intero elenco di array.|
| [`last_index_of(self, item, index)`](/cells/python-net/it/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.hyperlink-int) |Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dal primo elemento all'indice specificato.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.hyperlink-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che contiene il numero specificato di elementi e termina all'indice specificato.|
| [`binary_search(self, item)`](/cells/python-net/it/aspose.cells/hyperlinkcollection/binary_search/#aspose.cells.hyperlink) | Cerca un elemento nell'intero elenco dell'array ordinato utilizzando il comparatore predefinito e restituisce l'indice basato su zero dell'elemento.|



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
