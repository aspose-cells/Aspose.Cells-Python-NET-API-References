---
title: méthode add_scroll_bar
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 270
url: /fr/aspose.cells.drawing/shapecollection/add_scroll_bar/
is_root: false
---
##  add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Ajoute une barre de défilement à la feuille de calcul.


###  Retour

Un objet ScrollBar.


```python

def add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| upper_left_row | int | Index de la rangée supérieure gauche.|
| top | int |Représente le décalage vertical de ScrollBar par rapport à sa ligne de gauche, en unité de pixel.|
| upper_left_column | int | Index de la colonne supérieure gauche.|
| left | int | Représente le décalage horizontal de ScrollBar par rapport à sa colonne de gauche, en unité de pixel.|
| height | int | Représente la hauteur de la barre de défilement, en unité de pixel.|
| width | int | Représente la largeur de la barre de défilement, en unité de pixel.|

###  Exemple

```python

# add a scroll bar
scrollBar = shapes.add_scroll_bar(1, 0, 1, 0, 100, 20)

```



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection)
