---
title: text_vertical_alignment propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1020
url: /fr/aspose.cells.drawing/oval/text_vertical_alignment/
is_root: false
---
##  text_vertical_alignment propriété

Obtient et définit le type d’alignement vertical du texte de la forme.

###  Exemple

```python
from aspose.cells import TextAlignmentType

if shape.text_vertical_alignment == TextAlignmentType.BOTTOM:
    shape.text_vertical_alignment = TextAlignmentType.CENTER

```
###  Définition:
```python
@property
def text_vertical_alignment(self):
    ...
@text_vertical_alignment.setter
def text_vertical_alignment(self, value):
    ...
```

###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`Oval`](/cells/python-net/fr/aspose.cells.drawing/oval)
* classe [`TextAlignmentType`](/cells/python-net/fr/aspose.cells/textalignmenttype)
