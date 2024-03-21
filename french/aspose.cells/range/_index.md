---
title: Range classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1290
url: /fr/aspose.cells/range/
is_root: false
---
##  Range classe
Encapsule l'objet qui représente une plage de cellules dans une feuille de calcul.



Le type Range expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [current_region](/cells/python-net/fr/aspose.cells/range/current_region) |Renvoie un objet Range qui représente la région actuelle.<br/> La région actuelle est une plage délimitée par n’importe quelle combinaison de lignes vides et de colonnes vides.|
| [hyperlinks](/cells/python-net/fr/aspose.cells/range/hyperlinks) | Obtient tous les liens hypertexte de la plage.|
| [row_count](/cells/python-net/fr/aspose.cells/range/row_count) | Obtient le nombre de lignes dans la plage.|
| [column_count](/cells/python-net/fr/aspose.cells/range/column_count) | Obtient le nombre de colonnes dans la plage.|
| [name](/cells/python-net/fr/aspose.cells/range/name) | Obtient ou définit le nom de la plage.|
| [refers_to](/cells/python-net/fr/aspose.cells/range/refers_to) | Obtient la référence à la plage.|
| [address](/cells/python-net/fr/aspose.cells/range/address) | Obtient l'adresse de la plage.|
| [left](/cells/python-net/fr/aspose.cells/range/left) | Obtient la distance, en points, entre le bord gauche de la colonne A et le bord gauche de la plage.|
| [top](/cells/python-net/fr/aspose.cells/range/top) | Obtient la distance, en points, entre le bord supérieur de la ligne 1 et le bord supérieur de la plage.|
| [width](/cells/python-net/fr/aspose.cells/range/width) | Obtient la largeur d'une plage en points.|
| [height](/cells/python-net/fr/aspose.cells/range/height) | Obtient la largeur d'une plage en points.|
| [first_row](/cells/python-net/fr/aspose.cells/range/first_row) | Obtient l'index de la première ligne de la plage.|
| [first_column](/cells/python-net/fr/aspose.cells/range/first_column) | Obtient l'index de la première colonne de la plage.|
| [value](/cells/python-net/fr/aspose.cells/range/value) | Obtient et définit la valeur de la plage.|
| [column_width](/cells/python-net/fr/aspose.cells/range/column_width) | Définit ou obtient la largeur de colonne de cette plage|
| [row_height](/cells/python-net/fr/aspose.cells/range/row_height) | Définit ou obtient la hauteur des lignes dans cette plage|
| [entire_column](/cells/python-net/fr/aspose.cells/range/entire_column) | Obtient un objet Range qui représente la ou les colonnes entières contenant la plage spécifiée.|
| [entire_row](/cells/python-net/fr/aspose.cells/range/entire_row) |Obtient un objet Range qui représente la ou les lignes entières contenant la plage spécifiée.|
| [worksheet](/cells/python-net/fr/aspose.cells/range/worksheet) | Obtient l'objet [`Range.worksheet`](/cells/python-net/fr/aspose.cells/range#worksheet) qui contient cette plage.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [auto_fill](/cells/python-net/fr/aspose.cells/range/auto_fill/#aspose.cells.Range) | Remplissez automatiquement la plage cible.|
| [auto_fill](/cells/python-net/fr/aspose.cells/range/auto_fill/#aspose.cells.Range-aspose.cells.AutoFillType) | Remplissez automatiquement la plage cible.|
| [set_style](/cells/python-net/fr/aspose.cells/range/set_style/#aspose.cells.Style-bool) | Appliquez le style de cellule.|
| [set_style](/cells/python-net/fr/aspose.cells/range/set_style/#aspose.cells.Style) | Définit le style de la plage.|
| [set_outline_borders](/cells/python-net/fr/aspose.cells/range/set_outline_borders/#aspose.cells.CellBorderType-aspose.cells.CellsColor) | Définit les bordures de contour autour d'une plage de cellules avec le même style et la même couleur de bordure.|
| [set_outline_borders](/cells/python-net/fr/aspose.cells/range/set_outline_borders/#aspose.cells.CellBorderType-aspose.pydrawing.Color) | Définit les bordures de contour autour d'une plage de cellules avec le même style et la même couleur de bordure.|
| [set_outline_borders](/cells/python-net/fr/aspose.cells/range/set_outline_borders/#list-aspose.pydrawing.Color[]) | Définit les bordures de ligne autour d’une plage de cellules.|
| [set_outline_border](/cells/python-net/fr/aspose.cells/range/set_outline_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.cells.CellsColor) | Définit la bordure du contour autour d’une plage de cellules.|
| [set_outline_border](/cells/python-net/fr/aspose.cells/range/set_outline_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.pydrawing.Color) | Définit la bordure du contour autour d’une plage de cellules.|
| [copy](/cells/python-net/fr/aspose.cells/range/copy/#aspose.cells.Range-aspose.cells.PasteOptions) | Copie de la plage avec les options spéciales de collage.|
| [copy](/cells/python-net/fr/aspose.cells/range/copy/#aspose.cells.Range) | Copie les données (y compris les formules), le formatage, les objets de dessin, etc. à partir d'une plage source.|
| [add_hyperlink](/cells/python-net/fr/aspose.cells/range/add_hyperlink/#str-str-str) | Ajoute un lien hypertexte vers une cellule spécifiée ou une plage de cellules.|
| [get_enumerator](/cells/python-net/fr/aspose.cells/range/get_enumerator/#) | Obtient l'énumérateur pour les cellules de cette plage.|
| [is_intersect](/cells/python-net/fr/aspose.cells/range/is_intersect/#aspose.cells.Range) | Indique si la plage est intersectée.|
| [intersect](/cells/python-net/fr/aspose.cells/range/intersect/#aspose.cells.Range) | Renvoie un objet [`Range`](/cells/python-net/fr/aspose.cells/range) qui représente l'intersection rectangulaire de deux plages.|
| [union_rang](/cells/python-net/fr/aspose.cells/range/union_rang/#aspose.cells.Range) | Renvoie le résultat de l'union de deux plages.|
| [union](/cells/python-net/fr/aspose.cells/range/union/#aspose.cells.Range) | Renvoie l'union de deux plages.|
| [is_blank](/cells/python-net/fr/aspose.cells/range/is_blank/#) | Indique si la plage contient des valeurs.|
| [merge](/cells/python-net/fr/aspose.cells/range/merge/#) | Combine une plage de cellules en une seule cellule.|
| [un_merge](/cells/python-net/fr/aspose.cells/range/un_merge/#) |Annule la fusion des cellules fusionnées de cette plage.|
| [put_value](/cells/python-net/fr/aspose.cells/range/put_value/#str-bool-bool) | Place une valeur dans la plage, le cas échéant, la valeur sera convertie en un autre type de données et le format numérique de la cellule sera réinitialisé.|
| [apply_style](/cells/python-net/fr/aspose.cells/range/apply_style/#aspose.cells.Style-aspose.cells.StyleFlag) | Applique des formats pour toute une gamme.|
| [set_inside_borders](/cells/python-net/fr/aspose.cells/range/set_inside_borders/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.cells.CellsColor) | Définir les limites intérieures de la plage.|
| [move_to](/cells/python-net/fr/aspose.cells/range/move_to/#int-int) | Déplacez la plage actuelle vers la plage de destination.|
| [copy_data](/cells/python-net/fr/aspose.cells/range/copy_data/#aspose.cells.Range) | Copie les données de cellule (y compris les formules) à partir d'une plage source.|
| [copy_value](/cells/python-net/fr/aspose.cells/range/copy_value/#aspose.cells.Range) | Copie la valeur de cellule à partir d’une plage source.|
| [copy_style](/cells/python-net/fr/aspose.cells/range/copy_style/#aspose.cells.Range) | Copie les paramètres de style à partir d’une plage source.|
| [get_cell_or_null](/cells/python-net/fr/aspose.cells/range/get_cell_or_null/#int-int) | Obtient l'objet [`Cell`](/cells/python-net/fr/aspose.cells/cell) ou null dans cette plage.|
| [get_offset](/cells/python-net/fr/aspose.cells/range/get_offset/#int-int) | Obtient la plage [`Range`](/cells/python-net/fr/aspose.cells/range) par décalage.|



###  Remarques

La classe Range désigne une région de la feuille de calcul Excel.
Avec cela, vous pouvez formater et définir la valeur de la plage.
Et vous pouvez également simplement copier une plage d’Excel.

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
