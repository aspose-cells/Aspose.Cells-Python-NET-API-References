---
title: méthode add_check_box
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 70
url: /fr/aspose.cells.drawing/shapecollection/add_check_box/
is_root: false
---
##  add_check_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Ajoute une case à cocher à la feuille de calcul.


###  Retour

Le nouvel index d'objet CheckBox.


```python

def add_check_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| upper_left_row | int | Index de la rangée supérieure gauche.|
| top | int | Représente le décalage vertical de la case à cocher par rapport à sa rangée supérieure, en unité de pixel.|
| upper_left_column | int | Index de la colonne supérieure gauche.|
| left | int | Représente le décalage horizontal de la zone de texte par rapport à sa colonne de gauche, en unité de pixel.|
| height | int | Hauteur de la zone de texte, en unité de pixel.|
| width | int | Largeur de la zone de texte, en unité de pixel.|

###  Exemple

```python

# add a CheckBox
checkBox = shapes.add_check_box(1, 0, 1, 0, 100, 50)

```



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection)
