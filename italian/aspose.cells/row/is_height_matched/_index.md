---
title: is_height_matched proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 190
url: /it/aspose.cells/row/is_height_matched/
is_root: false
---
##  is_height_matched proprietà

Indica se l'altezza della riga corrisponde all'impostazione predefinita del carattere della cartella di lavoro.
Il fatto che questa proprietà sia vera indica anche che l'altezza della riga è "automatica" senza che l'utente imposti un valore di altezza personalizzato.

###  Osservazioni

Quando questa proprietà è vera, se il contenuto di questa riga cambia,
in genere l'altezza della riga deve essere ricalcolata (ad esempio con [`Worksheet.auto_fit_rows`](/cells/python-net/it/aspose.cells/worksheet/auto_fit_rows))
per ottenere lo stesso risultato mostrato in ms excel quando si apre la cartella di lavoro al suo interno.
###  Definizione:
```python
@property
def is_height_matched(self):
    ...
@is_height_matched.setter
def is_height_matched(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Row`](/cells/python-net/it/aspose.cells/row)
