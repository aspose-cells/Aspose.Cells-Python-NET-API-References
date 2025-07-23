---
title: ShapeCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 510
url: /fr/aspose.cells.drawing/shapecollection/
is_root: false
---
##  ShapeCollection classe
Représente toutes les formes d'une feuille de calcul/d'un graphique.



Le type ShapeCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells.drawing/shapecollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`add_shape_in_chart(self, type, placement, left, top, right, bottom, image_data)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_shape_in_chart/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-int-int-int-int-bytes) | Ajoutez une forme au graphique. Toutes les unités sont 1/4000 de la zone du graphique.|
| [`add_shape_in_chart(self, type, placement, left, top, right, bottom)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_shape_in_chart/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-int-int-int-int) | Ajoutez une forme au graphique. Toutes les unités sont 1/4000 de la zone du graphique.|
| [`add_shape_in_chart_by_scale(self, type, placement, left, top, right, bottom)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_shape_in_chart_by_scale/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-float-float-float-float) | Ajoutez une forme au graphique. Toutes les unités sont exprimées en pourcentage de la surface du graphique.|
| [`add_shape_in_chart_by_scale(self, type, placement, left, top, right, bottom, image_data)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_shape_in_chart_by_scale/#aspose.cells.drawing.msodrawingtype-aspose.cells.drawing.placementtype-float-float-float-float-bytes) | Ajoutez une forme au graphique. Toutes les unités sont 1/4000 de la zone du graphique.|
| [`add_picture(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_picture/#int-int-int-int-io.rawiobase) | Ajoute une image à la collection.|
| [`add_picture(self, upper_left_row, upper_left_column, stream, width_scale, height_scale)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_picture/#int-int-io.rawiobase-int-int) | Ajoute une image à la collection.|
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/index_of/#aspose.cells.drawing.shape-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/index_of/#aspose.cells.drawing.shape-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/last_index_of/#aspose.cells.drawing.shape-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`get(self, name)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/get/#str) | Obtient l'objet [`Shape`](/cells/python-net/fr/aspose.cells.drawing/shape) par le nom de la forme.|
| [`add_copy(self, source_shape, top_row, top, left_column, left)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_copy/#aspose.cells.drawing.shape-int-int-int-int) | Ajoute et copie une forme dans la feuille de calcul.|
| [`add_check_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_check_box/#int-int-int-int-int-int) | Ajoute une case à cocher à la feuille de calcul.|
| [`add_text_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_text_box/#int-int-int-int-int-int) | Ajoute une zone de texte à la feuille de calcul.|
| [`add_equation(self, top_row, top, left_column, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_equation/#int-int-int-int-int-int) |Ajoutez un objet d’équation à la feuille de calcul.|
| [`add_spinner(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_spinner/#int-int-int-int-int-int) | Ajoute un Spinner à la feuille de calcul.|
| [`add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_scroll_bar/#int-int-int-int-int-int) | Ajoute une barre de défilement à la feuille de calcul.|
| [`add_radio_button(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_radio_button/#int-int-int-int-int-int) | Ajoute un RadioButton à la feuille de calcul.|
| [`add_list_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_list_box/#int-int-int-int-int-int) | Ajoute une ListBox à la feuille de calcul.|
| [`add_combo_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_combo_box/#int-int-int-int-int-int) | Ajoute une ComboBox à la feuille de calcul.|
| [`add_group_box(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_group_box/#int-int-int-int-int-int) | Ajoute un GroupBox à la feuille de calcul.|
| [`add_button(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_button/#int-int-int-int-int-int) | Ajoute un bouton à la feuille de calcul.|
| [`add_label(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_label/#int-int-int-int-int-int) | Ajoute une étiquette à la feuille de calcul.|
| [`add_label_in_chart(self, top, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_label_in_chart/#int-int-int-int) | Ajoute une étiquette au graphique.|
| [`add_text_box_in_chart(self, top, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_text_box_in_chart/#int-int-int-int) | Ajoute une zone de texte au graphique.|
| [`add_text_effect_in_chart(self, effect, text, font_name, size, font_bold, font_italic, top, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_text_effect_in_chart/#aspose.cells.drawing.msopresettexteffect-str-str-int-bool-bool-int-int-int-int) | Insère un objet WordArt dans le graphique|
| [`add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_text_effect/#aspose.cells.drawing.msopresettexteffect-str-str-int-bool-bool-int-int-int-int-int-int) | Insère un objet WordArt.|
| [`add_word_art(self, style, text, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_word_art/#aspose.cells.drawing.presetwordartstyle-str-int-int-int-int-int-int) | Ajoute des éléments WordArt prédéfinis depuis Excel 2007.|
| [`add_rectangle(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_rectangle/#int-int-int-int-int-int) | Ajoute une forme rectangulaire à la feuille de calcul.|
| [`add_oval(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_oval/#int-int-int-int-int-int) | Ajoute un ovale à la feuille de calcul.|
| [`add_line(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_line/#int-int-int-int-int-int) | Ajoute une forme de ligne à la feuille de calcul.|
| [`add_free_floating_shape(self, type, top, left, height, width, image_data, is_original_size)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_free_floating_shape/#aspose.cells.drawing.msodrawingtype-int-int-int-int-bytes-bool) | Ajoute une forme flottante libre à la feuille de calcul. S'applique uniquement à la forme de ligne/image.|
| [`add_arc(self, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_arc/#int-int-int-int-int-int) | Ajoute une forme d'arc à la feuille de calcul.|
| [`add_shape(self, type, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_shape/#aspose.cells.drawing.msodrawingtype-int-int-int-int-int-int) | Ajoute une forme à la feuille de calcul.|
| [`add_auto_shape(self, type, upper_left_row, top, upper_left_column, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_auto_shape/#aspose.cells.drawing.autoshapetype-int-int-int-int-int-int) | Ajoute une forme automatique à la feuille de calcul.|
| [`add_auto_shape_in_chart(self, type, top, left, height, width)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_auto_shape_in_chart/#aspose.cells.drawing.autoshapetype-int-int-int-int) | Ajoute une forme automatique au graphique.|
| [`add_active_x_control(self, type, top_row, top, left_column, left, width, height)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_active_x_control/#aspose.cells.drawing.activexcontrols.controltype-int-int-int-int-int-int) | Crée un contrôle Activex.|
| [`add_svg(self, upper_left_row, top, upper_left_column, left, height, width, svg_data, compatible_image_data)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_svg/#int-int-int-int-int-int-bytes-bytes) | Ajoute une image svg.|
| [`add_icons(self, upper_left_row, top, upper_left_column, left, height, width, image_byte_data, compatible_image_data)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_icons/#int-int-int-int-int-int-bytes-bytes) | Ajoute une image svg.|
| [`add_linked_picture(self, upper_left_row, upper_left_column, height, width, source_full_name)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_linked_picture/#int-int-int-int-str) |Ajouter une image liée.|
| [`add_ole_object_with_linked_image(self, upper_left_row, upper_left_column, height, width, source_full_name)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_ole_object_with_linked_image/#int-int-int-int-str) |Ajouter une image liée.|
| [`add_picture_in_chart(self, top, left, stream, width_scale, height_scale)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_picture_in_chart/#int-int-io.rawiobase-int-int) | Ajoute une image au graphique.|
| [`add_ole_object(self, upper_left_row, top, upper_left_column, left, height, width, image_data)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_ole_object/#int-int-int-int-int-int-bytes) | Ajoute un OleObject.|
| [`copy_comments_in_range(self, shapes, ca, dest_row, dest_column)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/copy_comments_in_range/#aspose.cells.drawing.shapecollection-aspose.cells.cellarea-int-int) | Copiez tous les commentaires de la plage.|
| [`copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/copy_in_range/#aspose.cells.drawing.shapecollection-aspose.cells.cellarea-int-int-bool) | Copiez les formes de la plage vers la plage de destination.|
| [`delete_in_range(self, ca)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/delete_in_range/#aspose.cells.cellarea) | Supprimez les formes de la plage. Les formes de commentaires ne seront pas supprimées.|
| [`delete_shape(self, shape)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/delete_shape/#aspose.cells.drawing.shape) | Supprimer une forme. Si la forme fait partie du groupe ou est une forme de commentaire, elle ne sera pas supprimée.|
| [`group(self, group_items)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/group/#list) | Regroupez les formes.|
| [`ungroup(self, group)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/ungroup/#aspose.cells.drawing.groupshape) | Dissocie les éléments de forme.|
| [`remove_a_shape(self, shape)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/remove_a_shape/#aspose.cells.drawing.shape) | Ajoutez API for Python via .Net. puisque ce API n'est pas pris en charge|
| [`update_selected_value(self)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/update_selected_value/#) | Mettre à jour la valeur sélectionnée par la valeur de la cellule ou de la plage liée de la forme.|
| [`add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_freeform/#int-int-int-int-int-int-list) | Ajoute une forme libre à la feuille de calcul.|
| [`add_signature_line(self, upper_left_row, upper_left_column, signature_line)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/add_signature_line/#int-int-aspose.cells.drawing.signatureline) | Ajoute une ligne de signature à la feuille de calcul.|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells.drawing/shapecollection/binary_search/#aspose.cells.drawing.shape) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Exemple

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# get ShapeCollection
shapes = workbook.worksheets[0].shapes
# do your business
# Save the excel file.
workbook.save("result.xlsx")

```

###  Voir également
* module [`aspose.cells.drawing`](..)
* classe [`Shape`](/cells/python-net/fr/aspose.cells.drawing/shape)
