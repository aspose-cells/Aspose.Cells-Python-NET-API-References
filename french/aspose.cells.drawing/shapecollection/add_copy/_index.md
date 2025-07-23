---
title: méthode add_copy
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 90
url: /fr/aspose.cells.drawing/shapecollection/add_copy/
is_root: false
---
##  add_copy(self, source_shape, top_row, top, left_column, left) {#aspose.cells.drawing.Shape-int-int-int-int}
Ajoute et copie une forme dans la feuille de calcul.


###  Retour

Le nouvel objet [`Shape`](/cells/python-net/fr/aspose.cells.drawing/shape).


```python

def add_copy(self, source_shape, top_row, top, left_column, left):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| source_shape | [`Shape`](/cells/python-net/fr/aspose.cells.drawing/shape) | Forme de la source.|
| top_row | int |L'index de la ligne supérieure.|
| top | int | Représente le décalage vertical par rapport à sa rangée supérieure, en unité de pixel.|
| left_column | int | L'index de la colonne de gauche.|
| left | int | Représente le décalage horizontal par rapport à sa colonne de gauche, en unité de pixel.|

###  Exemple

```python

# add a shape
rectangle = shapes.add_rectangle(2, 0, 2, 0, 130, 130)
# Adds and copies a shape.
shapes.add_copy(rectangle, 7, 0, 7, 0)

```



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`Shape`](/cells/python-net/fr/aspose.cells.drawing/shape)
* classe [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection)
