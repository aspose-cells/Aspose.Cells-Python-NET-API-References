---
title: provider_id propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 80
url: /es/aspose.cells.drawing/signatureline/provider_id/
is_root: false
---
##  provider_id propiedad

Obtiene o establece el identificador del proveedor de firma.

###  Observaciones

Normalmente es el CLSID del complemento com del proveedor.

###  Ejemplo

```python
from aspose.cells.drawing import SignatureLine
from uuid import uuid4

#  Create signature line object
s2 = SignatureLine()
s2.provider_id = uuid4("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx")

```
###  Definición:
```python
@property
def provider_id(self):
    ...
@provider_id.setter
def provider_id(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`SignatureLine`](/cells/python-net/es/aspose.cells.drawing/signatureline)
