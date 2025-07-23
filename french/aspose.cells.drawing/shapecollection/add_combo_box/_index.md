---
title: méthode add_combo_box
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 80
url: /fr/aspose.cells.drawing/shapecollection/add_combo_box/
is_root: false
---
##  add_combo_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Ajoute une ComboBox à la feuille de calcul.


###  Retour

Un objet ComboBox.


```python

def add_combo_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| upper_left_row | int | Index de la rangée supérieure gauche.|
| top | int | Représente le décalage vertical de ComboBox par rapport à sa ligne de gauche, en unité de pixel.|
| upper_left_column | int | Index de la colonne supérieure gauche.|
| left | int | Représente le décalage horizontal de ComboBox par rapport à sa colonne de gauche, en unité de pixel.|
| height | int | Représente la hauteur de ComboBox, en unité de pixel.|
| width | int | Représente la largeur de ComboBox, en unité de pixel.|

###  Exemple

```python

# add a combo box
comboBox = shapes.add_combo_box(1, 0, 1, 0, 100, 50)

```



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection)
