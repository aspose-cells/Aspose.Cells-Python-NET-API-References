---
title: text_horizontal_overflow propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1070
url: /es/aspose.cells.drawing/listbox/text_horizontal_overflow/
is_root: false
---
##  text_horizontal_overflow propiedad

Obtiene y establece el tipo de desbordamiento horizontal del texto de la forma que contiene texto.

###  Ejemplo

```python
from aspose.cells.drawing import TextOverflowType

if shape.text_horizontal_overflow == TextOverflowType.CLIP:
    shape.text_horizontal_overflow = TextOverflowType.OVERFLOW

```
###  Definición:
```python
@property
def text_horizontal_overflow(self):
    ...
@text_horizontal_overflow.setter
def text_horizontal_overflow(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ListBox`](/cells/python-net/es/aspose.cells.drawing/listbox)
* clase [`TextOverflowType`](/cells/python-net/es/aspose.cells.drawing/textoverflowtype)
