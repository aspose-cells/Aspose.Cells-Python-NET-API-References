---
title: text_vertical_overflow propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1040
url: /fr/aspose.cells.drawing/smartartshape/text_vertical_overflow/
is_root: false
---
##  text_vertical_overflow propriété

Obtient et définit le type de débordement vertical du texte de la forme qui contient le texte.

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
* classe [`SmartArtShape`](/cells/python-net/fr/aspose.cells.drawing/smartartshape)
* classe [`TextOverflowType`](/cells/python-net/fr/aspose.cells.drawing/textoverflowtype)
