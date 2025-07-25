---
title: anchor_type propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 320
url: /fr/aspose.cells.drawing/oleobject/anchor_type/
is_root: false
---
##  anchor_type propriété

Obtient et définit le type de l'espace réservé d'ancrage de forme.

###  Exemple

```python
from aspose.cells.drawing import ShapeAnchorType

if shape.anchor_type == ShapeAnchorType.ONE_CELL_ANCHOR:
    shape.anchor_type = ShapeAnchorType.TWO_CELL_ANCHOR

```
###  Définition:
```python
@property
def anchor_type(self):
    ...
@anchor_type.setter
def anchor_type(self, value):
    ...
```

###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`OleObject`](/cells/python-net/fr/aspose.cells.drawing/oleobject)
* classe [`ShapeAnchorType`](/cells/python-net/fr/aspose.cells.drawing/shapeanchortype)
