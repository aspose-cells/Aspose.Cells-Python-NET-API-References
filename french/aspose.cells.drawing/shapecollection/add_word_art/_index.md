---
title: méthode add_word_art
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 380
url: /fr/aspose.cells.drawing/shapecollection/add_word_art/
is_root: false
---
##  add_word_art(self, style, text, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.PresetWordArtStyle-str-int-int-int-int-int-int}
Ajoute des éléments WordArt prédéfinis depuis Excel 2007.


###  Retour




```python

def add_word_art(self, style, text, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| style | [`PresetWordArtStyle`](/cells/python-net/fr/aspose.cells.drawing/presetwordartstyle) | Le style WordArt prédéfini.|
| text | str | Le texte.|
| upper_left_row | int | Index de la rangée supérieure gauche.|
| top | int | Représente le décalage vertical de la forme par rapport à sa rangée de gauche, en unité de pixel.|
| upper_left_column | int | Index de la colonne supérieure gauche.|
| left | int |Représente le décalage horizontal de la forme par rapport à sa colonne de gauche, en unité de pixel.|
| height | int | Représente la hauteur de la forme, en unité de pixel.|
| width | int | Représente la largeur de la forme, en unité de pixel.|

###  Exemple

```python
from aspose.cells.drawing import PresetWordArtStyle

# add a WordArt
wordArt2 = shapes.add_word_art(PresetWordArtStyle.WORD_ART_STYLE1, "WordArt", 3, 0, 3, 0, 50, 200)

```



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection)
