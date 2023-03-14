---
title: text_vertical_alignment propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1010
url: /es/aspose.cells.drawing/textbox/text_vertical_alignment/
is_root: false
---
##  text_vertical_alignment propiedad

Obtiene y establece el tipo de alineación vertical del texto de la forma.

###  Ejemplo

```python
from aspose.cells import TextAlignmentType

if shape.text_vertical_alignment == TextAlignmentType.BOTTOM:
    shape.text_vertical_alignment = TextAlignmentType.CENTER

```
###  Definición:
```python
@property
def text_vertical_alignment(self):
    ...
@text_vertical_alignment.setter
def text_vertical_alignment(self, value):
    ...
```

###  Ver también
* módulo [aspose.cells.drawing](../../)
* clase [TextAlignmentType](/cells/python-net/es/aspose.cells/textalignmenttype)
* clase [TextBox](/cells/python-net/es/aspose.cells.drawing/textbox)
