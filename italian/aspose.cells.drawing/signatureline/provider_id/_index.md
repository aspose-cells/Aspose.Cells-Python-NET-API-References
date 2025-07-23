---
title: provider_id proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 80
url: /it/aspose.cells.drawing/signatureline/provider_id/
is_root: false
---
##  provider_id proprietà

Ottiene o imposta l'ID del fornitore della firma.

###  Osservazioni

In genere è il CLSID del componente aggiuntivo com del provider.

###  Esempio

```python
from aspose.cells.drawing import SignatureLine
from uuid import uuid4

#  Create signature line object
s2 = SignatureLine()
s2.provider_id = uuid4("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx")

```
###  Definizione:
```python
@property
def provider_id(self):
    ...
@provider_id.setter
def provider_id(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`SignatureLine`](/cells/python-net/it/aspose.cells.drawing/signatureline)
