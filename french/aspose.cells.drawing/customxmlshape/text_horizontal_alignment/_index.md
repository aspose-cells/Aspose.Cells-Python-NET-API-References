---
title: text_horizontal_alignment propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 970
url: /fr/aspose.cells.drawing/customxmlshape/text_horizontal_alignment/
is_root: false
---
##  text_horizontal_alignment propriété

Obtient et définit le type d’alignement horizontal du texte de la forme.

###  Exemple

```python
from aspose.cells import TextAlignmentType

if shape.text_horizontal_alignment == TextAlignmentType.BOTTOM:
    shape.text_horizontal_alignment = TextAlignmentType.CENTER

```
###  Définition:
```python
@property
def text_horizontal_alignment(self):
    ...
@text_horizontal_alignment.setter
def text_horizontal_alignment(self, value):
    ...
```

###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`CustomXmlShape`](/cells/python-net/fr/aspose.cells.drawing/customxmlshape)
* classe [`TextAlignmentType`](/cells/python-net/fr/aspose.cells/textalignmenttype)
