---
title: méthode add_arc
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 30
url: /fr/aspose.cells.drawing/shapecollection/add_arc/
is_root: false
---
##  add_arc(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Ajoute une forme d'arc à la feuille de calcul.


###  Retour

Un objet ArcShape.


```python

def add_arc(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| upper_left_row | int | Index de la rangée supérieure gauche.|
| top | int |Représente le décalage vertical d'ArcShape par rapport à sa ligne de gauche, en unité de pixel.|
| upper_left_column | int | Index de la colonne supérieure gauche.|
| left | int | Représente le décalage horizontal d'ArcShape par rapport à sa colonne de gauche, en unité de pixel.|
| height | int | Représente la hauteur de l'ArcShape, en unité de pixel.|
| width | int | Représente la largeur de l'ArcShape, en unité de pixel.|

###  Exemple

```python

# add a arc
arcShape = shapes.add_arc(1, 0, 1, 0, 100, 50)

```



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection)
