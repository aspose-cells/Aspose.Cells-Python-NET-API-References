---
title: preferred_parsers proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 330
url: /it/aspose.cells/txtloadoptions/preferred_parsers/
is_root: false
---
##  preferred_parsers proprietà

Ottiene e imposta i parser dei valori preferiti per il caricamento del file di testo.

###  Osservazioni

parsers[0] è il parser che verrà utilizzato per la prima colonna nel file modello di testo,
parsers[1] è il parser che verrà utilizzato per la seconda colonna, ...ecc.
L'ultimo (parsers[parsers.length-1]) verrà utilizzato per tutte le altre colonne a partire da parsers.length-1.
Se un elemento è nullo, la colonna corrispondente verrà analizzata dal parser predefinito Aspose.Cells.
###  Definizione:
```python
@property
def preferred_parsers(self):
    ...
@preferred_parsers.setter
def preferred_parsers(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`TxtLoadOptions`](/cells/python-net/it/aspose.cells/txtloadoptions)
