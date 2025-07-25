---
title: Range classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1180
url: /fr/aspose.cells/range/
is_root: false
---
##  Range classe
Encapsule l'objet qui représente une plage de cellules dans une feuille de calcul.



Le type Range expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [current_region](/cells/python-net/fr/aspose.cells/range/current_region) | Renvoie un objet Range qui représente la région actuelle.<br/> La région actuelle est une plage délimitée par n’importe quelle combinaison de lignes vides et de colonnes vides.|
| [hyperlinks](/cells/python-net/fr/aspose.cells/range/hyperlinks) | Obtient tous les hyperliens de la plage.|
| [row_count](/cells/python-net/fr/aspose.cells/range/row_count) | Obtient le nombre de lignes dans la plage.|
| [column_count](/cells/python-net/fr/aspose.cells/range/column_count) | Obtient le nombre de colonnes dans la plage.|
| [name](/cells/python-net/fr/aspose.cells/range/name) | Obtient ou définit le nom de la plage.|
| [refers_to](/cells/python-net/fr/aspose.cells/range/refers_to) | Obtient la plage à laquelle se réfère.|
| [address](/cells/python-net/fr/aspose.cells/range/address) | Obtient l'adresse de la plage.|
| [left](/cells/python-net/fr/aspose.cells/range/left) | Obtient la distance, en points, du bord gauche de la colonne A au bord gauche de la plage.|
| [top](/cells/python-net/fr/aspose.cells/range/top) | Obtient la distance, en points, entre le bord supérieur de la ligne 1 et le bord supérieur de la plage.|
| [width](/cells/python-net/fr/aspose.cells/range/width) | Obtient la largeur d'une plage en points.|
| [height](/cells/python-net/fr/aspose.cells/range/height) | Obtient la largeur d'une plage en points.|
| [first_row](/cells/python-net/fr/aspose.cells/range/first_row) | Obtient l'index de la première ligne de la plage.|
| [first_column](/cells/python-net/fr/aspose.cells/range/first_column) | Obtient l'index de la première colonne de la plage.|
| [value](/cells/python-net/fr/aspose.cells/range/value) | Obtient et définit la valeur de la plage.|
| [column_width](/cells/python-net/fr/aspose.cells/range/column_width) | Définit ou obtient la largeur de colonne de cette plage|
| [row_height](/cells/python-net/fr/aspose.cells/range/row_height) | Définit ou obtient la hauteur des lignes dans cette plage|
| [entire_column](/cells/python-net/fr/aspose.cells/range/entire_column) |Obtient un objet Range qui représente la colonne entière (ou les colonnes) qui contient la plage spécifiée.|
| [entire_row](/cells/python-net/fr/aspose.cells/range/entire_row) | Obtient un objet Range qui représente la ligne entière (ou les lignes) qui contient la plage spécifiée.|
| [worksheet](/cells/python-net/fr/aspose.cells/range/worksheet) | Obtient l'objet [`Range.worksheet`](/cells/python-net/fr/aspose.cells/range#worksheet) qui contient cette plage.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`auto_fill(self, target)`](/cells/python-net/fr/aspose.cells/range/auto_fill/#aspose.cells.range) | Remplir automatiquement la plage cible.|
| [`auto_fill(self, target, auto_fill_type)`](/cells/python-net/fr/aspose.cells/range/auto_fill/#aspose.cells.range-aspose.cells.autofilltype) | Remplir automatiquement la plage cible.|
| [`set_style(self, style, explicit_flag)`](/cells/python-net/fr/aspose.cells/range/set_style/#aspose.cells.style-bool) | Appliquer le style de cellule.|
| [`set_style(self, style)`](/cells/python-net/fr/aspose.cells/range/set_style/#aspose.cells.style) | Définit le style de la plage.|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/fr/aspose.cells/range/set_outline_borders/#aspose.cells.cellbordertype-aspose.cells.cellscolor) | Définit les bordures de contour autour d'une plage de cellules avec le même style de bordure et la même couleur.|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/fr/aspose.cells/range/set_outline_borders/#aspose.cells.cellbordertype-aspose.pydrawing.color) | Définit les bordures de contour autour d'une plage de cellules avec le même style de bordure et la même couleur.|
| [`set_outline_borders(self, border_styles, border_colors)`](/cells/python-net/fr/aspose.cells/range/set_outline_borders/#list-aspose.pydrawing.color[]) | Définit les bordures de ligne autour d'une plage de cellules.|
| [`set_outline_border(self, border_edge, border_style, border_color)`](/cells/python-net/fr/aspose.cells/range/set_outline_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | Définit la bordure du contour autour d'une plage de cellules.|
| [`set_outline_border(self, border_edge, border_style, border_color)`](/cells/python-net/fr/aspose.cells/range/set_outline_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.pydrawing.color) | Définit la bordure du contour autour d'une plage de cellules.|
| [`copy(self, range, options)`](/cells/python-net/fr/aspose.cells/range/copy/#aspose.cells.range-aspose.cells.pasteoptions) | Copie de la plage avec les options de collage spécial.|
| [`copy(self, range)`](/cells/python-net/fr/aspose.cells/range/copy/#aspose.cells.range) | Copie les données (y compris les formules), la mise en forme, les objets de dessin, etc. à partir d'une plage source.|
| [`add_hyperlink(self, address, text_to_display, screen_tip)`](/cells/python-net/fr/aspose.cells/range/add_hyperlink/#str-str-str) | Ajoute un lien hypertexte vers une cellule spécifiée ou une plage de cellules.|
| [`is_intersect(self, range)`](/cells/python-net/fr/aspose.cells/range/is_intersect/#aspose.cells.range) | Indique si la plage est intersectée.|
| [`intersect(self, range)`](/cells/python-net/fr/aspose.cells/range/intersect/#aspose.cells.range) | Renvoie un objet [`Range`](/cells/python-net/fr/aspose.cells/range) qui représente l'intersection rectangulaire de deux plages.|
| [`union_rang(self, range)`](/cells/python-net/fr/aspose.cells/range/union_rang/#aspose.cells.range) | Renvoie le résultat de l'union de deux plages.|
| [`union_ranges(self, ranges)`](/cells/python-net/fr/aspose.cells/range/union_ranges/#list) | Renvoie le résultat de l'union de deux plages.|
| [`union(self, range)`](/cells/python-net/fr/aspose.cells/range/union/#aspose.cells.range) | Renvoie l'union de deux plages.|
| [`is_blank(self)`](/cells/python-net/fr/aspose.cells/range/is_blank/#) | Indique si la plage contient des valeurs.|
| [`merge(self)`](/cells/python-net/fr/aspose.cells/range/merge/#) |Combine une plage de cellules en une seule cellule.|
| [`un_merge(self)`](/cells/python-net/fr/aspose.cells/range/un_merge/#) | Annule la fusion des cellules fusionnées de cette plage.|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/fr/aspose.cells/range/put_value/#str-bool-bool) | Place une valeur dans la plage, si nécessaire, la valeur sera convertie en un autre type de données et le format numérique de la cellule sera réinitialisé.|
| [`apply_style(self, style, flag)`](/cells/python-net/fr/aspose.cells/range/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Applique des formats pour toute une gamme.|
| [`set_inside_borders(self, border_edge, line_style, border_color)`](/cells/python-net/fr/aspose.cells/range/set_inside_borders/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) | Situé à l'intérieur des limites de la gamme.|
| [`move_to(self, dest_row, dest_column)`](/cells/python-net/fr/aspose.cells/range/move_to/#int-int) | Déplacer la plage actuelle vers la plage de destination.|
| [`copy_data(self, range)`](/cells/python-net/fr/aspose.cells/range/copy_data/#aspose.cells.range) | Copie les données de cellule (y compris les formules) à partir d'une plage source.|
| [`copy_value(self, range)`](/cells/python-net/fr/aspose.cells/range/copy_value/#aspose.cells.range) | Copie la valeur de la cellule à partir d'une plage source.|
| [`copy_style(self, range)`](/cells/python-net/fr/aspose.cells/range/copy_style/#aspose.cells.range) | Copie les paramètres de style à partir d'une plage source.|
| [`transpose(self)`](/cells/python-net/fr/aspose.cells/range/transpose/#) | Transposer (faire pivoter) les données des lignes vers les colonnes ou vice versa.|
| [`get(self, row_offset, column_offset)`](/cells/python-net/fr/aspose.cells/range/get/#int-int) | Ajoutez API for Python via .Net. puisque ceci [int, int] n'est pas pris en charge|
| [`get_cell_or_null(self, row_offset, column_offset)`](/cells/python-net/fr/aspose.cells/range/get_cell_or_null/#int-int) | Obtient l'objet [`Cell`](/cells/python-net/fr/aspose.cells/cell) ou null dans cette plage.|
| [`get_offset(self, row_offset, column_offset)`](/cells/python-net/fr/aspose.cells/range/get_offset/#int-int) | Obtient la plage [`Range`](/cells/python-net/fr/aspose.cells/range) par décalage.|
| [`to_image(self, options)`](/cells/python-net/fr/aspose.cells/range/to_image/#aspose.cells.rendering.imageorprintoptions) | Convertit la plage en image.|
| [`to_json(self, options)`](/cells/python-net/fr/aspose.cells/range/to_json/#aspose.cells.jsonsaveoptions) | Convertissez la plage en valeur JSON.|
| [`to_html(self, save_options)`](/cells/python-net/fr/aspose.cells/range/to_html/#aspose.cells.htmlsaveoptions) | Convertissez la plage en HTML.|
| [`clear(self)`](/cells/python-net/fr/aspose.cells/range/clear/#) | Efface cette plage.|
| [`clear_contents(self)`](/cells/python-net/fr/aspose.cells/range/clear_contents/#) | Efface le contenu de cette plage.|
| [`clear_formats(self)`](/cells/python-net/fr/aspose.cells/range/clear_formats/#) | Efface les formats de cette plage.|
| [`clear_comments(self)`](/cells/python-net/fr/aspose.cells/range/clear_comments/#) | Efface les commentaires de cette plage.|
| [`clear_hyperlinks(self, clear_format)`](/cells/python-net/fr/aspose.cells/range/clear_hyperlinks/#bool) | Supprime uniquement les hyperliens.|



###  Remarques

La classe Range désigne une région de feuille de calcul Excel.
Avec cela, vous pouvez formater et définir la valeur de la plage.
Et vous pouvez également simplement copier une plage d'Excel.

###  Exemple

L'exemple suivant montre comment créer une plage et définir la valeur de la plage d'Excel.

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
#  Create a range (A1:D3).
range = cells.create_range("A1", "D3")
#  Set value to the range.
range.value = "Hello"
# Save the Excel file
workbook.save("book1.xlsm")

```

###  Voir également
* module [`aspose.cells`](..)
* classe [`Cell`](/cells/python-net/fr/aspose.cells/cell)
* classe [`Range`](/cells/python-net/fr/aspose.cells/range)
