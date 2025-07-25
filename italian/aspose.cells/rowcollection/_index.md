---
title: RowCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1240
url: /it/aspose.cells/rowcollection/
is_root: false
---
##  RowCollection classe
Raccoglie gli oggetti [`Row`](/cells/python-net/it/aspose.cells/row) che rappresentano le singole righe in un foglio di lavoro.



Il tipo RowCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [count](/cells/python-net/it/aspose.cells/rowcollection/count) | Ottiene il numero di righe in questa raccolta.|



Ottiene un oggetto [`Row`](/cells/python-net/it/aspose.cells/row) in base all'indice di riga specificato. L'oggetto Row dell'indice di riga specificato verrà istanziato se non esisteva prima.
###  Indicizzatore
| Nome| Descrizione|
| :- | :- |
| [index] |  |


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`get_enumerator(self, reversed, sync)`](/cells/python-net/it/aspose.cells/rowcollection/get_enumerator/#bool-bool) | Ottiene un enumeratore che scorre le righe attraverso questa raccolta|
| [`get_row_by_index(self, index)`](/cells/python-net/it/aspose.cells/rowcollection/get_row_by_index/#int) | Ottiene l'oggetto riga in base alla posizione nell'elenco.|
| [`clear(self)`](/cells/python-net/it/aspose.cells/rowcollection/clear/#) | Cancella tutte le righe e le celle.|
| [`remove_at(self, index)`](/cells/python-net/it/aspose.cells/rowcollection/remove_at/#int) | Rimuove l'elemento di riga nella posizione index(position) specificata in questa raccolta.|



###  Esempio

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Get first row
row = worksheet.cells.rows[0]

```

###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`Row`](/cells/python-net/it/aspose.cells/row)
