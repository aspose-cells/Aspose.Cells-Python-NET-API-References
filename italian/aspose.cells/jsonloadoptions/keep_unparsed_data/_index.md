---
title: keep_unparsed_data proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 120
url: /it/aspose.cells/jsonloadoptions/keep_unparsed_data/
is_root: false
---
##  keep_unparsed_data proprietà

Mantenere in memoria i dati non analizzati per la cartella di lavoro quando viene caricata dal file modello. Il valore predefinito è true.

###  Osservazioni

Per scenari in cui l'utente deve solo leggere alcuni contenuti dal file modello e non ha bisogno di salvare nuovamente la cartella di lavoro,
impostare questa proprietà su false può migliorare le prestazioni, soprattutto se utilizzata insieme a qualche tipo di LoadFilter,
###  Definizione:
```python
@property
def keep_unparsed_data(self):
    ...
@keep_unparsed_data.setter
def keep_unparsed_data(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`JsonLoadOptions`](/cells/python-net/it/aspose.cells/jsonloadoptions)
