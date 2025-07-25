---
title: méthode add_freeform
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 120
url: /fr/aspose.cells.drawing/shapecollection/add_freeform/
is_root: false
---
##  add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths) {#int-int-int-int-int-int-list}
Ajoute une forme libre à la feuille de calcul.


###  Retour

Une forme libre.


```python

def add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| upper_left_row | int | Index de la rangée supérieure gauche.|
| top | int | Représente le décalage vertical de la forme libre par rapport à sa rangée de gauche, en unité de pixel.|
| upper_left_column | int | Index de la colonne supérieure gauche.|
| left | int | Représente le décalage horizontal de la forme libre par rapport à sa colonne de gauche, en unité de pixel.|
| height | int | Représente la hauteur de la forme libre, en unité de pixel.|
| width | int | Représente la largeur de la forme libre, en unité de pixel.|
| paths | list | Représente un chemin défini par l'utilisateur|
###  Remarques

Remarque : La largeur et la hauteur des paramètres peuvent être des valeurs entières positives, et non la largeur et la hauteur totales du tableau ShapePath spécifié par « chemins ». La relation entre ces valeurs est une relation d'échelle-remplissage, c'est-à-dire que chaque objet ShapePath est mis à l'échelle en fonction de sa largeur et de sa hauteur. Par conséquent, lorsque plusieurs objets sont présents dans les « chemins », chaque objet ShapePath doit être conçu de manière à répondre aux attentes. Lorsqu'il n'y a qu'un seul objet ShapePath et qu'il n'y a pas d'autres exigences, passer la largeur et la hauteur de l'objet comme valeurs de paramètre est une bonne solution.
###  Exemple


```python
from aspose.cells.drawing import ShapePath

# Custom figure
shapePath = ShapePath()
shapePath.move_to(60, 45)
shapePath.arc_to(25, 25, 0, 270)
shapePath.close()
shapePath.move_to(60, 20)
shapePath.line_to(110, 70)
shapePath.line_to(125, 155.5)
shapePath.arc_to(35.5, 35.5, 0, 270)
shapePath.close()
shapePath.move_to(150, 45)
shapePath.arc_to(25, 25, 0, 270)
shapePathW = shapePath.width_pixel
shapePathH = shapePath.height_pixel
shapePath1 = ShapePath()
shapePath1.move_to(0, 0)
shapePath1.cubic_bezier_to(48.24997, 0.6844,                                 96.5, -7.148871,                                 130, 11.517795)
shapePath1.cubic_bezier_to(163.5, 30.18446,                                 182.24997, 75.351,                                 201, 120.517795)
shapePath1.move_to(150, 80)
shapePath1.arc_to(25, 25, 0, 270)
if shapePath1.width_pixel > shapePathW:
    shapePathW = shapePath1.width_pixel
if shapePath1.height_pixel > shapePathH:
    shapePathH = shapePath1.height_pixel
# Notice: shapePathH and shapePathH can be any positive integer values, here we just simply set them.
# Insert custom figure into worksheet
shapes.add_freeform(1, 0, 1, 0, shapePathH, shapePathW, [shapePath, shapePath1])

```



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection)
