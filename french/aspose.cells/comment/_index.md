---
title: Comment classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 260
url: /fr/aspose.cells/comment/
is_root: false
---
##  Comment classe
Encapsule l'objet qui représente un commentaire de cellule.



Le type Comment expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [author](/cells/python-net/fr/aspose.cells/comment/author) | Obtient et définit le nom de l'auteur du commentaire d'origine|
| [comment_shape](/cells/python-net/fr/aspose.cells/comment/comment_shape) | Obtenez un objet Shape qui représente la forme attachée au commentaire spécifié.|
| [row](/cells/python-net/fr/aspose.cells/comment/row) | Obtient l'index de ligne du commentaire.|
| [column](/cells/python-net/fr/aspose.cells/comment/column) | Obtient l'index de la colonne du commentaire.|
| [is_threaded_comment](/cells/python-net/fr/aspose.cells/comment/is_threaded_comment) | Indique si ce commentaire est un commentaire fileté.|
| [threaded_comments](/cells/python-net/fr/aspose.cells/comment/threaded_comments) | Obtient la liste des commentaires en fil de discussion ;|
| [note](/cells/python-net/fr/aspose.cells/comment/note) | Représente le contenu du commentaire.|
| [html_note](/cells/python-net/fr/aspose.cells/comment/html_note) | Obtient et définit la chaîne HTML qui contient les données et certains formats dans ce commentaire.|
| [font](/cells/python-net/fr/aspose.cells/comment/font) | Obtient la police du commentaire.|
| [is_visible](/cells/python-net/fr/aspose.cells/comment/is_visible) | Indique si le commentaire est visible ou non.|
| [text_orientation_type](/cells/python-net/fr/aspose.cells/comment/text_orientation_type) | Obtient et définit le type d'orientation du texte du commentaire.|
| [text_horizontal_alignment](/cells/python-net/fr/aspose.cells/comment/text_horizontal_alignment) | Obtient et définit le type d'alignement horizontal du texte du commentaire.|
| [text_vertical_alignment](/cells/python-net/fr/aspose.cells/comment/text_vertical_alignment) | Obtient et définit le type d'alignement vertical du texte du commentaire.|
| [auto_size](/cells/python-net/fr/aspose.cells/comment/auto_size) | Indique si la taille du commentaire est ajustée automatiquement en fonction de son contenu.<br/>Remarque : Dans certains cas particuliers (comme sur Mac), ce paramètre peut ne pas être appliqué. Si ce paramètre ne fonctionne pas, remplacez-le par FitToTextSize().|
| [height_cm](/cells/python-net/fr/aspose.cells/comment/height_cm) | Représente la hauteur du commentaire, en centimètres.|
| [width_cm](/cells/python-net/fr/aspose.cells/comment/width_cm) | Représente la largeur du commentaire, en centimètres.|
| [width](/cells/python-net/fr/aspose.cells/comment/width) | Représente la largeur du commentaire, en unité de pixels.|
| [height](/cells/python-net/fr/aspose.cells/comment/height) | Représente la hauteur du commentaire, en unité de pixels.|
| [width_inch](/cells/python-net/fr/aspose.cells/comment/width_inch) | Représente la largeur du commentaire, en pouces.|
| [height_inch](/cells/python-net/fr/aspose.cells/comment/height_inch) | Représente la hauteur du commentaire, en pouces.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`format_characters(self, start_index, length, font, flag)`](/cells/python-net/fr/aspose.cells/comment/format_characters/#int-int-aspose.cells.font-aspose.cells.styleflag) | Formatez certains caractères avec le paramètre de police.|
| [`characters(self, start_index, length)`](/cells/python-net/fr/aspose.cells/comment/characters/#int-int) | Renvoie un objet Characters qui représente une plage de caractères dans le texte du commentaire.|
| [`get_characters(self)`](/cells/python-net/fr/aspose.cells/comment/get_characters/#) | Renvoie tous les objets Characters<br/> qui représente une plage de caractères dans le texte du commentaire.|
| [`get_rich_formattings(self)`](/cells/python-net/fr/aspose.cells/comment/get_rich_formattings/#) | Renvoie tous les objets Characters<br/> qui représente une plage de caractères dans le texte du commentaire.|



###  Exemple

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments
# Add comment to cell A1
commentIndex1 = comments.add(0, 0)
comment1 = comments[commentIndex1]
comment1.note = "First note."
comment1.font.name = "Times New Roman"
# Add comment to cell B2
comments.add("B2")
comment2 = comments.get("B2")
comment2.note = "Second note."
# do your business
# Save the excel file.
workbook.save("exmaple.xlsx")

```

###  Voir également
* module [`aspose.cells`](..)
