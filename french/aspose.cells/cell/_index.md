---
title: Cell classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 110
url: /fr/aspose.cells/cell/
is_root: false
---
##  Cell classe
Encapsule l'objet qui représente une seule cellule du classeur.



Le type Cell expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [worksheet](/cells/python-net/fr/aspose.cells/cell/worksheet) | Obtient la feuille de calcul parent.|
| [date_time_value](/cells/python-net/fr/aspose.cells/cell/date_time_value) | Obtient la valeur DateTime contenue dans la cellule.|
| [row](/cells/python-net/fr/aspose.cells/cell/row) | Obtient le numéro de ligne (à partir de zéro) de la cellule.|
| [column](/cells/python-net/fr/aspose.cells/cell/column) | Obtient le numéro de colonne (à partir de zéro) de la cellule.|
| [is_formula](/cells/python-net/fr/aspose.cells/cell/is_formula) | Représente si la cellule spécifiée contient une formule.|
| [has_custom_function](/cells/python-net/fr/aspose.cells/cell/has_custom_function) |Vérifie s'il existe une fonction personnalisée (fonction non prise en charge) dans la formule de cette cellule.|
| [type](/cells/python-net/fr/aspose.cells/cell/type) | Représente le type de valeur de cellule.|
| [name](/cells/python-net/fr/aspose.cells/cell/name) | Obtient le nom de la cellule.|
| [is_error_value](/cells/python-net/fr/aspose.cells/cell/is_error_value) | Vérifie si la valeur de cette cellule est une erreur.|
| [is_numeric_value](/cells/python-net/fr/aspose.cells/cell/is_numeric_value) | Indique si la valeur de cette cellule est numérique (int, double et datetime)|
| [string_value](/cells/python-net/fr/aspose.cells/cell/string_value) | Obtient la valeur de chaîne contenue dans la cellule. Si le type de cette cellule est une chaîne, renvoie la valeur de chaîne elle-même.<br/>Pour les autres types de cellules, la valeur de chaîne formatée (formatée avec le style spécifié de cette cellule) sera renvoyée.<br/>La valeur de la cellule formatée est la même que celle que vous pouvez obtenir à partir d'Excel lorsque vous copiez une cellule sous forme de texte (par exemple<br/> (copie de cellule dans un éditeur de texte ou exportation au format csv).|
| [string_value_without_format](/cells/python-net/fr/aspose.cells/cell/string_value_without_format) | Obtient la valeur de la cellule sous forme de chaîne sans aucun format.|
| [number_category_type](/cells/python-net/fr/aspose.cells/cell/number_category_type) | Représente le type de catégorie du formatage numérique de cette cellule.|
| [display_string_value](/cells/python-net/fr/aspose.cells/cell/display_string_value) | Obtient la valeur de chaîne formatée de cette cellule par le style d'affichage de la cellule.|
| [int_value](/cells/python-net/fr/aspose.cells/cell/int_value) | Obtient la valeur entière contenue dans la cellule.|
| [double_value](/cells/python-net/fr/aspose.cells/cell/double_value) | Obtient la valeur double contenue dans la cellule.|
| [float_value](/cells/python-net/fr/aspose.cells/cell/float_value) | Obtient la valeur flottante contenue dans la cellule.|
| [bool_value](/cells/python-net/fr/aspose.cells/cell/bool_value) | Obtient la valeur booléenne contenue dans la cellule.|
| [has_custom_style](/cells/python-net/fr/aspose.cells/cell/has_custom_style) | Indique si cette cellule possède des paramètres de style personnalisés (différents de ceux par défaut hérités)<br/>à partir de la ligne, de la colonne ou du classeur correspondant).|
| [shared_style_index](/cells/python-net/fr/aspose.cells/cell/shared_style_index) | Obtient l'index de style partagé de la cellule dans le pool de styles.|
| [formula](/cells/python-net/fr/aspose.cells/cell/formula) | Obtient ou définit une formule du [`Cell`](/cells/python-net/fr/aspose.cells/cell).|
| [formula_local](/cells/python-net/fr/aspose.cells/cell/formula_local) | Obtenez la formule formatée par les paramètres régionaux de la cellule.|
| [r1c1_formula](/cells/python-net/fr/aspose.cells/cell/r1c1_formula) | Obtient ou définit une formule R1C1 du [`Cell`](/cells/python-net/fr/aspose.cells/cell).|
| [contains_external_link](/cells/python-net/fr/aspose.cells/cell/contains_external_link) | Indique si cette cellule contient un lien externe.<br/> S'applique uniquement lorsque la cellule est une cellule de formule.|
| [is_array_header](/cells/python-net/fr/aspose.cells/cell/is_array_header) | Indique que la formule de la cellule est une formule matricielle<br/> et c'est la première cellule du tableau.|
| [is_dynamic_array_formula](/cells/python-net/fr/aspose.cells/cell/is_dynamic_array_formula) | Indique si la formule de la cellule est une formule de tableau dynamique (vrai) ou une formule de tableau héritée (faux).|
| [is_array_formula](/cells/python-net/fr/aspose.cells/cell/is_array_formula) | Indique si la formule de cellule est une formule matricielle.|
| [is_in_array](/cells/python-net/fr/aspose.cells/cell/is_in_array) | Indique si la formule de cellule est une formule matricielle.|
| [is_shared_formula](/cells/python-net/fr/aspose.cells/cell/is_shared_formula) | Indique si la formule de la cellule fait partie d'une formule partagée.|
| [is_table_formula](/cells/python-net/fr/aspose.cells/cell/is_table_formula) | Indique si cette cellule fait partie d'une formule de tableau.|
| [is_in_table](/cells/python-net/fr/aspose.cells/cell/is_in_table) | Indique si cette cellule fait partie d'une formule de tableau.|
| [value](/cells/python-net/fr/aspose.cells/cell/value) | Obtient/définit la valeur contenue dans cette cellule.|
| [is_style_set](/cells/python-net/fr/aspose.cells/cell/is_style_set) | Indique si le style de la cellule est défini. Si la valeur est « false », cela signifie que la cellule possède un format par défaut.|
| [is_merged](/cells/python-net/fr/aspose.cells/cell/is_merged) | Vérifie si une cellule fait partie d'une plage fusionnée ou non.|
| [comment](/cells/python-net/fr/aspose.cells/cell/comment) |Obtient le commentaire de cette cellule.|
| [html_string](/cells/python-net/fr/aspose.cells/cell/html_string) | Obtient et définit la chaîne HTML qui contient des données et certains formats dans cette cellule.|
| [is_check_box_style](/cells/python-net/fr/aspose.cells/cell/is_check_box_style) | Indique si cette cellule doit être définie comme une case à cocher.|
| [embedded_image](/cells/python-net/fr/aspose.cells/cell/embedded_image) | Obtient et définit l'image intégrée dans la cellule.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`put_value(self, bool_value)`](/cells/python-net/fr/aspose.cells/cell/put_value/#bool) | Place une valeur booléenne dans la cellule.|
| [`put_value(self, int_value)`](/cells/python-net/fr/aspose.cells/cell/put_value/#int) | Met une valeur entière dans la cellule.|
| [`put_value(self, double_value)`](/cells/python-net/fr/aspose.cells/cell/put_value/#float) | Met une valeur double dans la cellule.|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/fr/aspose.cells/cell/put_value/#str-bool-bool) | Place une valeur dans la cellule, si nécessaire, la valeur sera convertie en un autre type de données et le format numérique de la cellule sera réinitialisé.|
| [`put_value(self, string_value, is_converted)`](/cells/python-net/fr/aspose.cells/cell/put_value/#str-bool) | Place une valeur de chaîne dans la cellule et convertit la valeur en un autre type de données si approprié.|
| [`put_value(self, string_value)`](/cells/python-net/fr/aspose.cells/cell/put_value/#str) | Place une valeur de chaîne dans la cellule.|
| [`put_value(self, date_time)`](/cells/python-net/fr/aspose.cells/cell/put_value/#datetime) | Place une valeur DateTime dans la cellule.|
| [`put_value(self, object_value)`](/cells/python-net/fr/aspose.cells/cell/put_value/#any) | Place une valeur d'objet dans la cellule.|
| [`get_display_style(self)`](/cells/python-net/fr/aspose.cells/cell/get_display_style/#) | Obtient le style d'affichage de cette cellule.|
| [`get_display_style(self, include_merged_borders)`](/cells/python-net/fr/aspose.cells/cell/get_display_style/#bool) | Obtient le style d'affichage de cette cellule.|
| [`get_display_style(self, adjacent_borders)`](/cells/python-net/fr/aspose.cells/cell/get_display_style/#aspose.cells.bordertype) | Obtient le style d'affichage de cette cellule.|
| [`get_style(self)`](/cells/python-net/fr/aspose.cells/cell/get_style/#) | Obtient le style de cellule.|
| [`get_style(self, check_borders)`](/cells/python-net/fr/aspose.cells/cell/get_style/#bool) | Si checkBorders est vrai, vérifiez si les bordures des autres cellules affecteront le style de cette cellule.|
| [`set_style(self, style)`](/cells/python-net/fr/aspose.cells/cell/set_style/#aspose.cells.style) | Définit le style de cellule.|
| [`set_style(self, style, explicit_flag)`](/cells/python-net/fr/aspose.cells/cell/set_style/#aspose.cells.style-bool) | Appliquez la propriété modifiée du style à la cellule.|
| [`set_style(self, style, flag)`](/cells/python-net/fr/aspose.cells/cell/set_style/#aspose.cells.style-aspose.cells.styleflag) |Appliquer le style de cellule en fonction des indicateurs.|
| [`set_formula(self, formula, value)`](/cells/python-net/fr/aspose.cells/cell/set_formula/#str-any) | Définissez la formule et la valeur (résultat calculé) de la formule.|
| [`set_formula(self, formula, options)`](/cells/python-net/fr/aspose.cells/cell/set_formula/#str-aspose.cells.formulaparseoptions) | Définissez la formule et la valeur (résultat calculé) de la formule.|
| [`set_formula(self, formula, is_r1c1, is_local, value)`](/cells/python-net/fr/aspose.cells/cell/set_formula/#str-bool-bool-any) | Définissez la formule et la valeur de la formule.|
| [`set_formula(self, formula, options, value)`](/cells/python-net/fr/aspose.cells/cell/set_formula/#str-aspose.cells.formulaparseoptions-any) | Définissez la formule et la valeur (résultat calculé) de la formule.|
| [`set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local)`](/cells/python-net/fr/aspose.cells/cell/set_array_formula/#str-int-int-bool-bool) | Définit une formule matricielle sur une plage de cellules.|
| [`set_array_formula(self, array_formula, row_number, column_number)`](/cells/python-net/fr/aspose.cells/cell/set_array_formula/#str-int-int) | Définit une formule de tableau (formule de tableau héritée saisie via CTRL+MAJ+ENTRÉE dans MS Excel) sur une plage de cellules.|
| [`set_array_formula(self, array_formula, row_number, column_number, options)`](/cells/python-net/fr/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.formulaparseoptions) | Définit une formule matricielle sur une plage de cellules.|
| [`set_array_formula(self, array_formula, row_number, column_number, options, values)`](/cells/python-net/fr/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.formulaparseoptions-list) | Définit une formule matricielle sur une plage de cellules.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, is_r1c1, is_local)`](/cells/python-net/fr/aspose.cells/cell/set_shared_formula/#str-int-int-bool-bool) | Définit une formule sur une plage de cellules.|
| [`set_shared_formula(self, shared_formula, row_number, column_number)`](/cells/python-net/fr/aspose.cells/cell/set_shared_formula/#str-int-int) | Définit des formules partagées sur une plage de cellules.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, options)`](/cells/python-net/fr/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.formulaparseoptions) | Définit des formules partagées sur une plage de cellules.|
| [`set_shared_formula(self, shared_formula, row_number, column_number, options, values)`](/cells/python-net/fr/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.formulaparseoptions-list) | Définit des formules partagées sur une plage de cellules.|
| [`get_leafs(self)`](/cells/python-net/fr/aspose.cells/cell/get_leafs/#) | Obtenez toutes les cellules qui font directement référence à cette cellule et doivent être mises à jour lorsque cette cellule est modifiée.|
| [`get_leafs(self, recursive)`](/cells/python-net/fr/aspose.cells/cell/get_leafs/#bool) | Obtenez toutes les cellules qui seront mises à jour lorsque cette cellule est modifiée.|
| [`set_dynamic_array_formula(self, array_formula, options, calculate_value)`](/cells/python-net/fr/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-bool) | Définit une formule de tableau dynamique et fait en sorte que la formule se répande dans les cellules voisines si possible.|
| [`set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value)`](/cells/python-net/fr/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-list-bool-bool) | Définit une formule de tableau dynamique et fait en sorte que la formule se répande dans les cellules voisines si possible.|
| [`set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts)`](/cells/python-net/fr/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-list-bool-bool-aspose.cells.calculationoptions) | Définit une formule de tableau dynamique et fait en sorte que la formule se répande dans les cellules voisines si possible.|
| [`set_table_formula(self, row_number, column_number, row_input_cell, column_input_cell, values)`](/cells/python-net/fr/aspose.cells/cell/set_table_formula/#int-int-str-str-list) | Créez un tableau de données à deux variables pour une plage donnée à partir de cette cellule.|
| [`set_table_formula(self, row_number, column_number, input_cell, is_row_input, values)`](/cells/python-net/fr/aspose.cells/cell/set_table_formula/#int-int-str-bool-list) | Créez un tableau de données à une variable pour une plage donnée à partir de cette cellule.|
| [`set_table_formula(self, row_number, column_number, row_index_of_row_input_cell, column_index_of_row_input_cell, row_index_of_column_input_cell, column_index_of_column_input_cell, values)`](/cells/python-net/fr/aspose.cells/cell/set_table_formula/#int-int-int-int-int-int-list) | Créez un tableau de données à deux variables pour une plage donnée à partir de cette cellule.|
| [`set_table_formula(self, row_number, column_number, row_index_of_input_cell, column_index_of_input_cell, is_row_input, values)`](/cells/python-net/fr/aspose.cells/cell/set_table_formula/#int-int-int-int-bool-list) | Créez un tableau de données à une variable pour une plage donnée à partir de cette cellule.|
| [`get_characters(self)`](/cells/python-net/fr/aspose.cells/cell/get_characters/#) | Renvoie tous les objets Characters<br/> qui représente une plage de caractères dans le texte de la cellule.|
| [`get_characters(self, flag)`](/cells/python-net/fr/aspose.cells/cell/get_characters/#bool) | Renvoie tous les objets Characters<br/> qui représente une plage de caractères dans le texte de la cellule.|
| [`calculate(self, options)`](/cells/python-net/fr/aspose.cells/cell/calculate/#aspose.cells.calculationoptions) | Calcule la formule de la cellule.|
| [`get_string_value(self, format_strategy)`](/cells/python-net/fr/aspose.cells/cell/get_string_value/#aspose.cells.cellvalueformatstrategy) |Obtient la valeur de la chaîne par une stratégie formatée spécifique.|
| [`get_width_of_value(self)`](/cells/python-net/fr/aspose.cells/cell/get_width_of_value/#) | Obtient la largeur de la valeur en unité de pixels.|
| [`get_height_of_value(self)`](/cells/python-net/fr/aspose.cells/cell/get_height_of_value/#) | Obtient la hauteur de la valeur en unité de pixels.|
| [`get_format_conditions(self)`](/cells/python-net/fr/aspose.cells/cell/get_format_conditions/#) | Obtient les conditions de format qui s'appliquent à cette cellule.|
| [`get_formula(self, is_r1c1, is_local)`](/cells/python-net/fr/aspose.cells/cell/get_formula/#bool-bool) | Obtenez la formule de cette cellule.|
| [`get_precedents(self)`](/cells/python-net/fr/aspose.cells/cell/get_precedents/#) | Obtient toutes les références apparaissant dans la formule de cette cellule.|
| [`get_dependents(self, is_all)`](/cells/python-net/fr/aspose.cells/cell/get_dependents/#bool) | Obtenez toutes les cellules dont la formule fait directement référence à cette cellule.|
| [`get_precedents_in_calculation(self)`](/cells/python-net/fr/aspose.cells/cell/get_precedents_in_calculation/#) | Obtient tous les précédents (référence aux cellules du classeur actuel) utilisés par la formule de cette cellule lors de son calcul.|
| [`get_dependents_in_calculation(self, recursive)`](/cells/python-net/fr/aspose.cells/cell/get_dependents_in_calculation/#bool) | Obtient toutes les cellules dont le résultat calculé dépend de cette cellule.|
| [`get_array_range(self)`](/cells/python-net/fr/aspose.cells/cell/get_array_range/#) | Obtient la plage du tableau si la formule de la cellule est une formule de tableau.|
| [`remove_array_formula(self, leave_normal_formula)`](/cells/python-net/fr/aspose.cells/cell/remove_array_formula/#bool) | Supprimer la formule matricielle.|
| [`copy(self, cell)`](/cells/python-net/fr/aspose.cells/cell/copy/#aspose.cells.cell) | Copie les données d'une cellule source.|
| [`characters(self, start_index, length)`](/cells/python-net/fr/aspose.cells/cell/characters/#int-int) | Renvoie un objet Characters qui représente une plage de caractères dans le texte de la cellule.|
| [`replace(self, place_holder, new_value, options)`](/cells/python-net/fr/aspose.cells/cell/replace/#str-str-aspose.cells.replaceoptions) | Remplacer le texte de la cellule par des options.|
| [`insert_text(self, index, text)`](/cells/python-net/fr/aspose.cells/cell/insert_text/#int-str) | Insérez quelques caractères dans la cellule.<br/> Si la cellule est au format riche, cette méthode peut conserver le formatage d'origine.|
| [`is_rich_text(self)`](/cells/python-net/fr/aspose.cells/cell/is_rich_text/#) |Indique si la valeur de chaîne de cette cellule est un texte au format enrichi.|
| [`set_characters(self, characters)`](/cells/python-net/fr/aspose.cells/cell/set_characters/#list) | Définit le format de texte enrichi de la cellule.|
| [`get_merged_range(self)`](/cells/python-net/fr/aspose.cells/cell/get_merged_range/#) | Renvoie un objet [`Range`](/cells/python-net/fr/aspose.cells/range) qui représente une plage fusionnée.|
| [`get_html_string(self, html5)`](/cells/python-net/fr/aspose.cells/cell/get_html_string/#bool) | Obtient la chaîne HTML qui contient les données et certains formats dans cette cellule.|
| [`to_json(self)`](/cells/python-net/fr/aspose.cells/cell/to_json/#) | Convertissez les données de structure [`Cell`](/cells/python-net/fr/aspose.cells/cell) en JSON.|
| [`equals(self, cell)`](/cells/python-net/fr/aspose.cells/cell/equals/#aspose.cells.cell) | Vérifie si cet objet fait référence à la même cellule qu'un autre objet cellule.|
| [`get_conditional_formatting_result(self)`](/cells/python-net/fr/aspose.cells/cell/get_conditional_formatting_result/#) | Obtenez le résultat de la mise en forme conditionnelle.|
| [`get_validation(self)`](/cells/python-net/fr/aspose.cells/cell/get_validation/#) | Obtient la validation appliquée à cette cellule.|
| [`get_validation_value(self)`](/cells/python-net/fr/aspose.cells/cell/get_validation_value/#) | Obtient la valeur de validation appliquée à cette cellule.|
| [`get_table(self)`](/cells/python-net/fr/aspose.cells/cell/get_table/#) | Obtient le tableau qui contient cette cellule.|
| [`get_rich_value(self)`](/cells/python-net/fr/aspose.cells/cell/get_rich_value/#) | Obtient la valeur riche de la cellule.|



###  Exemple

```python
from aspose.cells import TextAlignmentType, Workbook
from aspose.pydrawing import Color

excel = Workbook()
cells = excel.worksheets[0].cells
# Put a string into a cell
cell = cells.get(0, 0)
cell.put_value("Hello")
first = cell.string_value
# Put an integer into a cell
cell = cells.get("B1")
cell.put_value(12)
second = cell.int_value
# Put a double into a cell
cell = cells.get(0, 2)
cell.put_value(-1.234)
third = cell.double_value
# Put a formula into a cell
cell = cells.get("D1")
cell.formula = "=B1 + C1"
# Put a combined formula: "sum(average(b1,c1), b1)" to cell at b2
cell = cells.get("b2")
cell.formula = "=sum(average(b1,c1), b1)"
# Set style of a cell
style = cell.get_style()
# Set background color
style.background_color = Color.yellow
# Set format of a cell
style.font.name = "Courier New"
style.vertical_alignment = TextAlignmentType.TOP
cell.set_style(style)

```

###  Voir également
* module [`aspose.cells`](..)
* classe [`Cell`](/cells/python-net/fr/aspose.cells/cell)
* classe [`Range`](/cells/python-net/fr/aspose.cells/range)
