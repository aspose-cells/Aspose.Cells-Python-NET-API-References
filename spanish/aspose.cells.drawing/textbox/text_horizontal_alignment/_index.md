---
title: text_horizontal_alignment propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 990
url: /es/aspose.cells.drawing/textbox/text_horizontal_alignment/
is_root: false
---
##  text_horizontal_alignment propiedad

Obtiene y establece el tipo de alineación horizontal del texto de la forma.

###  Ejemplo

```python
from aspose.cells import TextAlignmentType

if shape.text_horizontal_alignment == TextAlignmentType.BOTTOM:
    shape.text_horizontal_alignment = TextAlignmentType.CENTER

```
###  Definición:
```python
@property
def text_horizontal_alignment(self):
    ...
@text_horizontal_alignment.setter
def text_horizontal_alignment(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`TextAlignmentType`](/cells/python-net/es/aspose.cells/textalignmenttype)
* clase [`TextBox`](/cells/python-net/es/aspose.cells.drawing/textbox)
