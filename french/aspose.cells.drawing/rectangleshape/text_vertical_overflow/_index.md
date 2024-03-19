---
title: text_vertical_overflow propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1030
url: /fr/aspose.cells.drawing/rectangleshape/text_vertical_overflow/
is_root: false
---
##  text_vertical_overflow propriété

Obtient et définit le type de débordement vertical de texte de la forme qui contient du texte.

###  Exemple

```python
from aspose.cells.drawing import TextOverflowType

if shape.text_vertical_overflow == TextOverflowType.CLIP:
    shape.text_vertical_overflow = TextOverflowType.OVERFLOW

```
###  Définition:
```python
@property
def text_vertical_overflow(self):
    ...
@text_vertical_overflow.setter
def text_vertical_overflow(self, value):
    ...
```

###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`RectangleShape`](/cells/python-net/fr/aspose.cells.drawing/rectangleshape)
* classe [`TextOverflowType`](/cells/python-net/fr/aspose.cells.drawing/textoverflowtype)
