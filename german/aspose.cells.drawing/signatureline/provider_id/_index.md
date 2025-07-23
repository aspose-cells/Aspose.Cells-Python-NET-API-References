---
title: provider_id Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 80
url: /de/aspose.cells.drawing/signatureline/provider_id/
is_root: false
---
##  provider_id Eigentum

Ruft die ID des Signaturanbieters ab oder legt sie fest.

###  Bemerkungen

Normalerweise handelt es sich dabei um die CLSID des Provider-Com-Add-Ins.

###  Beispiel

```python
from aspose.cells.drawing import SignatureLine
from uuid import uuid4

#  Create signature line object
s2 = SignatureLine()
s2.provider_id = uuid4("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx")

```
###  Definition:
```python
@property
def provider_id(self):
    ...
@provider_id.setter
def provider_id(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`SignatureLine`](/cells/python-net/de/aspose.cells.drawing/signatureline)
