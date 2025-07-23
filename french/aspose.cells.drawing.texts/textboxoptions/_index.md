---
title: TextBoxOptions classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 80
url: /fr/aspose.cells.drawing.texts/textboxoptions/
is_root: false
---
##  TextBoxOptions classe
Représente les options de texte de la forme



Le type TextBoxOptions expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [shape_text_vertical_alignment](/cells/python-net/fr/aspose.cells.drawing.texts/textboxoptions/shape_text_vertical_alignment) | Cela correspond à « Format de la forme - Options de texte - Zone de texte - Alignement vertical » dans Excel.|
| [resize_to_fit_text](/cells/python-net/fr/aspose.cells.drawing.texts/textboxoptions/resize_to_fit_text) | Indique s'il faut redimensionner la forme pour l'adapter au texte|
| [shape_text_direction](/cells/python-net/fr/aspose.cells.drawing.texts/textboxoptions/shape_text_direction) | Obtient ou définit la direction d'affichage du texte dans un corps de texte donné.<br/> Cela correspond à « Format de la forme - Options de texte - Zone de texte - Direction du texte » dans Excel|
| [left_margin_pt](/cells/python-net/fr/aspose.cells.drawing.texts/textboxoptions/left_margin_pt) | Obtient et définit la marge gauche en unités de points.|
| [right_margin_pt](/cells/python-net/fr/aspose.cells.drawing.texts/textboxoptions/right_margin_pt) | Obtient et définit la marge droite en unité de points.|
| [top_margin_pt](/cells/python-net/fr/aspose.cells.drawing.texts/textboxoptions/top_margin_pt) | Obtient et définit la marge supérieure en unités de points.|
| [bottom_margin_pt](/cells/python-net/fr/aspose.cells.drawing.texts/textboxoptions/bottom_margin_pt) | Renvoie la marge inférieure en unités de points|
| [allow_text_to_overflow](/cells/python-net/fr/aspose.cells.drawing.texts/textboxoptions/allow_text_to_overflow) | Autoriser ou non le texte à déborder de la forme.|
| [wrap_text_in_shape](/cells/python-net/fr/aspose.cells.drawing.texts/textboxoptions/wrap_text_in_shape) | Spécifie l'habillage du texte dans une forme.<br/> Faux - Aucun habillage ne se produira sur le corps du texte.<br/>Vrai - L'habillage se produira sur le corps du texte.|



###  Exemple

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
index = workbook.worksheets[0].text_boxes.add(0, 0, 350, 350)
shape = workbook.worksheets[0].text_boxes[index]
shape.text = "This is test."
# do your business
# Save the excel file.
workbook.save("exmaple.xlsx")

```

###  Voir également
* module [`aspose.cells.drawing.texts`](..)
