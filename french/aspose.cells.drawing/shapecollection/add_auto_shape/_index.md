---
title: méthode add_auto_shape
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 40
url: /fr/aspose.cells.drawing/shapecollection/add_auto_shape/
is_root: false
---
##  add_auto_shape(self, type, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.AutoShapeType-int-int-int-int-int-int}
Ajoute une forme automatique à la feuille de calcul.


###  Retour

Un objet Forme.


```python

def add_auto_shape(self, type, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| type | [`AutoShapeType`](/cells/python-net/fr/aspose.cells.drawing/autoshapetype) | Type de forme automatique.|
| upper_left_row | int | Index de la rangée supérieure gauche.|
| top | int | Représente le décalage vertical de la forme par rapport à sa rangée de gauche, en unité de pixel.|
| upper_left_column | int | Index de la colonne supérieure gauche.|
| left | int | Représente le décalage horizontal de la forme par rapport à sa colonne de gauche, en unité de pixel.|
| height | int | Représente la hauteur de la forme, en unité de pixel.|
| width | int | Représente la largeur de la forme, en unité de pixel.|
###  Remarques

Le type ne peut pas être Graphique/Commentaire/Image/OleObject/Polygone/DialogBox
###  Exemple


```python
from aspose.cells.drawing import AutoShapeType

# Adds a AutoShape to the worksheet.
autoShape = shapes.add_auto_shape(AutoShapeType.CUBE, 1, 0, 1, 0, 100, 50)

```



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection)
