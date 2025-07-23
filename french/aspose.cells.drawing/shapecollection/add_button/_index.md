---
title: méthode add_button
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 60
url: /fr/aspose.cells.drawing/shapecollection/add_button/
is_root: false
---
##  add_button(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Ajoute un bouton à la feuille de calcul.


###  Retour

Un objet Bouton.


```python

def add_button(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| upper_left_row | int | Index de la rangée supérieure gauche.|
| top | int | Représente le décalage vertical du bouton par rapport à sa rangée de gauche, en unité de pixel.|
| upper_left_column | int | Index de la colonne supérieure gauche.|
| left | int |Représente le décalage horizontal du bouton par rapport à sa colonne de gauche, en unité de pixel.|
| height | int | Représente la hauteur du bouton, en unité de pixel.|
| width | int | Représente la largeur du bouton, en unité de pixel.|

###  Exemple

```python

# add a button
button = shapes.add_button(1, 0, 1, 0, 100, 50)

```



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection)
