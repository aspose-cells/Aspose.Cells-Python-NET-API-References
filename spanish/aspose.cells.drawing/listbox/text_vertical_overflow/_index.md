---
title: text_vertical_overflow propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1120
url: /es/aspose.cells.drawing/listbox/text_vertical_overflow/
is_root: false
---
##  text_vertical_overflow propiedad

Obtiene y establece el tipo de desbordamiento vertical del texto de la forma que contiene texto.

###  Ejemplo

```python
from aspose.cells.drawing import TextOverflowType

if shape.text_vertical_overflow == TextOverflowType.CLIP:
    shape.text_vertical_overflow = TextOverflowType.OVERFLOW

```
###  Definición:
```python
@property
def text_vertical_overflow(self):
    ...
@text_vertical_overflow.setter
def text_vertical_overflow(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ListBox`](/cells/python-net/es/aspose.cells.drawing/listbox)
* clase [`TextOverflowType`](/cells/python-net/es/aspose.cells.drawing/textoverflowtype)
