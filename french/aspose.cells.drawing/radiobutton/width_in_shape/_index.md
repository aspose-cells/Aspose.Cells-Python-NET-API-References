---
title: width_in_shape propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1230
url: /fr/aspose.cells.drawing/radiobutton/width_in_shape/
is_root: false
---
##  width_in_shape propriété

Représente la largeur de la forme, en unité de 1/4000 de la forme parent.

###  Remarques

S'applique uniquement lorsque cette forme se trouve dans le groupe ou le graphique.

###  Exemple

```python

if shape.is_in_group and shape.width_in_shape == 2000:
    shape.width_in_shape = 4000

```
###  Définition:
```python
@property
def width_in_shape(self):
    ...
@width_in_shape.setter
def width_in_shape(self, value):
    ...
```

###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`RadioButton`](/cells/python-net/fr/aspose.cells.drawing/radiobutton)
