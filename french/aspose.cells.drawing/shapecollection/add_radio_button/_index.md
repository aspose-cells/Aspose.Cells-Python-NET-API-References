---
title: méthode add_radio_button
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 250
url: /fr/aspose.cells.drawing/shapecollection/add_radio_button/
is_root: false
---
##  add_radio_button(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Ajoute un RadioButton à la feuille de calcul.


###  Retour

Un objet RadioButton.


```python

def add_radio_button(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| upper_left_row | int | Index de la rangée supérieure gauche.|
| top | int | Représente le décalage vertical de RadioButton par rapport à sa rangée de gauche, en unité de pixel.|
| upper_left_column | int | Index de la colonne supérieure gauche.|
| left | int | Représente le décalage horizontal de RadioButton par rapport à sa colonne de gauche, en unité de pixel.|
| height | int | Représente la hauteur du RadioButton, en unité de pixel.|
| width | int | Représente la largeur du RadioButton, en unité de pixel.|

###  Exemple

```python

# add a radio button
radioButton = shapes.add_radio_button(1, 0, 1, 0, 100, 50)

```



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection)
