---
title: placement propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 880
url: /fr/aspose.cells.drawing/spinner/placement/
is_root: false
---
##  placement propriété

Représente la manière dont l'objet de dessin est attaché aux cellules situées en dessous.
La propriété contrôle le placement d'un objet sur une feuille de calcul.

###  Exemple

```python
from aspose.cells.drawing import PlacementType

if shape.placement == PlacementType.MOVE:
    shape.placement = PlacementType.MOVE_AND_SIZE

```
###  Définition:
```python
@property
def placement(self):
    ...
@placement.setter
def placement(self, value):
    ...
```

###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`PlacementType`](/cells/python-net/fr/aspose.cells.drawing/placementtype)
* classe [`Spinner`](/cells/python-net/fr/aspose.cells.drawing/spinner)
