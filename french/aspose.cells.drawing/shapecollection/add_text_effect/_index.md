---
title: méthode add_text_effect
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 360
url: /fr/aspose.cells.drawing/shapecollection/add_text_effect/
is_root: false
---
##  add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.MsoPresetTextEffect-str-str-int-bool-bool-int-int-int-int-int-int}
Insère un objet WordArt.


###  Retour

Renvoie un objet Shape qui représente le nouvel objet WordArt.


```python

def add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| effect | [`MsoPresetTextEffect`](/cells/python-net/fr/aspose.cells.drawing/msopresettexteffect) | Le type d'effet de texte prédéfini mso.|
| text | str | Le texte WordArt.|
| font_name | str | Le nom de la police.|
| size | int | La taille de la police|
| font_bold | bool | Indique si la police est en gras.|
| font_italic | bool | Indique si la police est en italique.|
| upper_left_row | int | Index de la rangée supérieure gauche.|
| top | int | Représente le décalage vertical de la forme par rapport à sa rangée de gauche, en unité de pixel.|
| upper_left_column | int | Index de la colonne supérieure gauche.|
| left | int |Représente le décalage horizontal de la forme par rapport à sa colonne de gauche, en unité de pixel.|
| height | int | Représente la hauteur de la forme, en unité de pixel.|
| width | int | Représente la largeur de la forme, en unité de pixel.|

###  Exemple

```python
from aspose.cells.drawing import MsoPresetTextEffect

# add a WordArt
wordArt1 = shapes.add_text_effect(MsoPresetTextEffect.TEXT_EFFECT10, "WordArt", "arial", 18, False, False, 3, 0, 3, 0, 200, 50)

```



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection)
