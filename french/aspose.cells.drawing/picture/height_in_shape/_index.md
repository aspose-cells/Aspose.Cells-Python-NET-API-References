---
title: height_in_shape propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 520
url: /fr/aspose.cells.drawing/picture/height_in_shape/
is_root: false
---
##  height_in_shape propriété

Représente le décalage vertical de la forme par rapport à la bordure supérieure de la forme parent, en unité de 1/4 000 de la hauteur de la forme parent.

###  Remarques

S'applique uniquement lorsque cette forme fait partie du groupe ou du graphique.

###  Exemple

```python

if shape.is_in_group and shape.height_in_shape == 4000:
    shape.height_in_shape = 2000

```
###  Définition:
```python
@property
def height_in_shape(self):
    ...
@height_in_shape.setter
def height_in_shape(self, value):
    ...
```

###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`Picture`](/cells/python-net/fr/aspose.cells.drawing/picture)
