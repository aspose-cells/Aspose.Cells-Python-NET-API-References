---
title: auto_size propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 80
url: /es/aspose.cells/comment/auto_size/
is_root: false
---
##  auto_size propiedad

Indica si el tamaño del comentario se ajusta automáticamente según su contenido.
Nota: En algunos casos especiales (como en entornos Mac), es posible que esta configuración no tenga efecto. Si no lo tiene, reemplácela con FitToTextSize().

###  Ejemplo

```python

if notcomment1.auto_size:
    # The size of the comment varies with the content
    comment1.auto_size = True

```
###  Definición:
```python
@property
def auto_size(self):
    ...
@auto_size.setter
def auto_size(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Comment`](/cells/python-net/es/aspose.cells/comment)
