---
title: height_in_shape propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 450
url: /fr/aspose.cells.drawing/commentshape/height_in_shape/
is_root: false
---
##  height_in_shape propriété

Représente le décalage vertical de la forme par rapport à la bordure supérieure de la forme parente, en unité de 1/4000 de la hauteur de la forme parente.

###  Remarques

S'applique uniquement lorsque cette forme se trouve dans le groupe ou le graphique.

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
* classe [`CommentShape`](/cells/python-net/fr/aspose.cells.drawing/commentshape)
