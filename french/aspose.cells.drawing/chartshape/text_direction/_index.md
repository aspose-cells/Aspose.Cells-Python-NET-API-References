---
title: text_direction propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 970
url: /fr/aspose.cells.drawing/chartshape/text_direction/
is_root: false
---
##  text_direction propriété

Obtient/définit la direction du flux de texte pour cet objet.

###  Exemple

```python
from aspose.cells import TextDirectionType

if shape.text_direction == TextDirectionType.CONTEXT:
    shape.text_direction = TextDirectionType.LEFT_TO_RIGHT

```
###  Définition:
```python
@property
def text_direction(self):
    ...
@text_direction.setter
def text_direction(self, value):
    ...
```

###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ChartShape`](/cells/python-net/fr/aspose.cells.drawing/chartshape)
* classe [`TextDirectionType`](/cells/python-net/fr/aspose.cells/textdirectiontype)
