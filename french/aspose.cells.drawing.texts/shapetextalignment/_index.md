---
title: ShapeTextAlignment classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 70
url: /fr/aspose.cells.drawing.texts/shapetextalignment/
is_root: false
---
##  ShapeTextAlignment classe
Représente le paramètre d'alignement du texte de la forme ;



Le type ShapeTextAlignment expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [is_text_wrapped](/cells/python-net/fr/aspose.cells.drawing.texts/shapetextalignment/is_text_wrapped) | Obtient ou définit le type de texte enveloppé de la forme qui contient du texte.|
| [rotate_text_with_shape](/cells/python-net/fr/aspose.cells.drawing.texts/shapetextalignment/rotate_text_with_shape) | Indique si le texte doit être tourné avec une forme.|
| [text_vertical_overflow](/cells/python-net/fr/aspose.cells.drawing.texts/shapetextalignment/text_vertical_overflow) | Obtient et définit le type de débordement vertical du texte de la zone de texte.|
| [text_horizontal_overflow](/cells/python-net/fr/aspose.cells.drawing.texts/shapetextalignment/text_horizontal_overflow) | Obtient et définit le type de débordement horizontal du texte de la zone de texte.|
| [rotation_angle](/cells/python-net/fr/aspose.cells.drawing.texts/shapetextalignment/rotation_angle) | Obtient et définit la rotation de la forme.|
| [text_vertical_type](/cells/python-net/fr/aspose.cells.drawing.texts/shapetextalignment/text_vertical_type) | Obtient et définit la direction du texte.|
| [is_locked_text](/cells/python-net/fr/aspose.cells.drawing.texts/shapetextalignment/is_locked_text) | Indique si la forme est verrouillée lorsque la feuille de calcul est protégée.|
| [auto_size](/cells/python-net/fr/aspose.cells.drawing.texts/shapetextalignment/auto_size) | Indique si la taille de la forme est ajustée automatiquement en fonction de son contenu.|
| [text_shape_type](/cells/python-net/fr/aspose.cells.drawing.texts/shapetextalignment/text_shape_type) | Obtient et définit le type de transformation du texte.|
| [top_margin_pt](/cells/python-net/fr/aspose.cells.drawing.texts/shapetextalignment/top_margin_pt) | Renvoie la marge supérieure en unités de points|
| [bottom_margin_pt](/cells/python-net/fr/aspose.cells.drawing.texts/shapetextalignment/bottom_margin_pt) | Renvoie la marge inférieure en unités de points|
| [left_margin_pt](/cells/python-net/fr/aspose.cells.drawing.texts/shapetextalignment/left_margin_pt) | Renvoie la marge gauche en unités de points|
| [right_margin_pt](/cells/python-net/fr/aspose.cells.drawing.texts/shapetextalignment/right_margin_pt) | Renvoie la marge de droite en unités de points|
| [is_auto_margin](/cells/python-net/fr/aspose.cells.drawing.texts/shapetextalignment/is_auto_margin) |Indique si la marge du cadre de texte est automatique.|
| [number_of_columns](/cells/python-net/fr/aspose.cells.drawing.texts/shapetextalignment/number_of_columns) | Obtient et définit le nombre de colonnes de texte dans le rectangle englobant.|



###  Exemple

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
shape = workbook.worksheets[0].shapes.add_rectangle(1, 0, 1, 0, 50, 100)
shapeTextAlignment = shape.text_body.text_alignment

```

###  Voir également
* module [`aspose.cells.drawing.texts`](..)
