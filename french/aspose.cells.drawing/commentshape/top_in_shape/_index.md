---
title: top_in_shape propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1090
url: /fr/aspose.cells.drawing/commentshape/top_in_shape/
is_root: false
---
##  top_in_shape propriété

 Représente le décalage vertical de la forme par rapport à la bordure supérieure de la forme parent.
en unité de 1/4000 de hauteur de la forme parent.

###  Remarques

S'applique uniquement lorsque cette forme fait partie du groupe ou du graphique.

###  Exemple

```python

if shape.is_in_group and shape.top_in_shape == 8000:
    shape.top_in_shape = 4000

```
###  Définition:
```python
@property
def top_in_shape(self):
    ...
@top_in_shape.setter
def top_in_shape(self, value):
    ...
```

###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`CommentShape`](/cells/python-net/fr/aspose.cells.drawing/commentshape)
