---
title: PivotTable classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 180
url: /fr/aspose.cells.pivot/pivottable/
is_root: false
---
##  PivotTable classe
Description sommaire pour PivotTable.



Le type PivotTable expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [is_excel_2003_compatible](/cells/python-net/fr/aspose.cells.pivot/pivottable/is_excel_2003_compatible) | Spécifie si le tableau croisé dynamique est compatible avec Excel2003 lors de l'actualisation du tableau croisé dynamique,<br/>si vrai, une chaîne doit être inférieure ou égale à 255 caractères, donc si la chaîne est supérieure à 255 caractères,<br/>il sera tronqué. si elle est fausse, une chaîne n'aura pas la restriction susmentionnée.<br/> La valeur par défaut est vraie.|
| [refreshed_by_who](/cells/python-net/fr/aspose.cells.pivot/pivottable/refreshed_by_who) | Obtient le nom de l'utilisateur qui a actualisé le tableau croisé dynamique pour la dernière fois|
| [refresh_date](/cells/python-net/fr/aspose.cells.pivot/pivottable/refresh_date) | Obtient la date à laquelle le tableau croisé dynamique a été actualisé pour la dernière fois.|
| [pivot_table_style_name](/cells/python-net/fr/aspose.cells.pivot/pivottable/pivot_table_style_name) | Obtient et définit le nom du style pivotant.|
| [pivot_table_style_type](/cells/python-net/fr/aspose.cells.pivot/pivottable/pivot_table_style_type) | Obtient et définit le style de tableau croisé dynamique intégré.|
| [column_fields](/cells/python-net/fr/aspose.cells.pivot/pivottable/column_fields) | Renvoie un objet PivotFields actuellement affiché sous forme de champs de colonne.|
| [row_fields](/cells/python-net/fr/aspose.cells.pivot/pivottable/row_fields) | Renvoie un objet PivotFields actuellement affiché sous forme de champs de ligne.|
| [page_fields](/cells/python-net/fr/aspose.cells.pivot/pivottable/page_fields) | Renvoie un objet PivotFields actuellement affiché sous forme de champs de page.|
| [data_fields](/cells/python-net/fr/aspose.cells.pivot/pivottable/data_fields) | Obtient un objet PivotField qui représente tous les champs de données d'un tableau croisé dynamique.<br/>En lecture seule. Il ne s'agirait que d'un init lorsqu'il y a deux champs de données ou plus dans DataPiovtFiels.<br/> Il sert uniquement à ajouter DataPivotField à la zone de ligne/colonne du tableau croisé dynamique. La valeur par défaut est dans la zone de ligne.|
| [data_field](/cells/python-net/fr/aspose.cells.pivot/pivottable/data_field) | Obtient un objet PivotField qui représente tous les champs de données d'un tableau croisé dynamique.<br/>En lecture seule. Il ne s'agirait que d'un init lorsqu'il y a deux champs de données ou plus dans DataPiovtFiels.<br/> Il sert uniquement à ajouter DataPivotField à la zone de ligne/colonne du tableau croisé dynamique. La valeur par défaut est dans la zone de ligne.|
| [base_fields](/cells/python-net/fr/aspose.cells.pivot/pivottable/base_fields) | Renvoie un objet PivotFields qui inclut tous les champs du rapport de tableau croisé dynamique|
| [pivot_filters](/cells/python-net/fr/aspose.cells.pivot/pivottable/pivot_filters) | Renvoie un objet PivotFilterCollection.|
| [column_range](/cells/python-net/fr/aspose.cells.pivot/pivottable/column_range) |Renvoie un objet CellArea qui représente la plage<br/> qui contient la zone de colonnes dans le rapport de tableau croisé dynamique. Lecture seulement.|
| [row_range](/cells/python-net/fr/aspose.cells.pivot/pivottable/row_range) |Renvoie un objet CellArea qui représente la plage<br/> qui contient la zone de ligne dans le rapport de tableau croisé dynamique. Lecture seulement.|
| [data_body_range](/cells/python-net/fr/aspose.cells.pivot/pivottable/data_body_range) | Renvoie un objet CellArea qui représente la plage contenant la zone de données<br/> dans la liste entre la ligne d'en-tête et la ligne d'insertion. Lecture seulement.|
| [table_range1](/cells/python-net/fr/aspose.cells.pivot/pivottable/table_range1) | Renvoie un objet CellArea qui représente la plage contenant l'intégralité du rapport de tableau croisé dynamique,<br/> mais n'inclut pas les champs de page. Lecture seulement.|
| [table_range2](/cells/python-net/fr/aspose.cells.pivot/pivottable/table_range2) | Renvoie un objet CellArea qui représente la plage contenant l'intégralité du rapport de tableau croisé dynamique,<br/> inclut les champs de page. Lecture seulement.|
| [column_grand](/cells/python-net/fr/aspose.cells.pivot/pivottable/column_grand) | Indique si le rapport de tableau croisé dynamique affiche les totaux généraux des colonnes.|
| [is_grid_drop_zones](/cells/python-net/fr/aspose.cells.pivot/pivottable/is_grid_drop_zones) | Indique si le rapport de tableau croisé dynamique affiche une disposition de tableau croisé dynamique classique.<br/> (permet de faire glisser les champs dans la grille)|
| [row_grand](/cells/python-net/fr/aspose.cells.pivot/pivottable/row_grand) | Indique si le rapport de tableau croisé dynamique affiche les totaux généraux des lignes.|
| [display_null_string](/cells/python-net/fr/aspose.cells.pivot/pivottable/display_null_string) | Indique si le rapport de tableau croisé dynamique affiche une chaîne personnalisée<br/> dans les cellules contenant des valeurs nulles.|
| [null_string](/cells/python-net/fr/aspose.cells.pivot/pivottable/null_string) | Obtient la chaîne affichée dans les cellules contenant des valeurs nulles<br/>lorsque la propriété DisplayNullString est vraie. La valeur par défaut est une chaîne vide.|
| [display_error_string](/cells/python-net/fr/aspose.cells.pivot/pivottable/display_error_string) | Indique si le rapport de tableau croisé dynamique affiche une chaîne personnalisée dans les cellules contenant des erreurs.|
| [data_field_header_name](/cells/python-net/fr/aspose.cells.pivot/pivottable/data_field_header_name) | Obtient et définit le nom de l’en-tête du champ de zone de valeurs dans le tableau croisé dynamique.|
| [error_string](/cells/python-net/fr/aspose.cells.pivot/pivottable/error_string) | Obtient la chaîne affichée dans les cellules contenant des erreurs<br/> lorsque la propriété DisplayErrorString est vraie. La valeur par défaut est une chaîne vide.|
| [is_auto_format](/cells/python-net/fr/aspose.cells.pivot/pivottable/is_auto_format) | Indique si le rapport de tableau croisé dynamique est automatiquement formaté.<br/> Case à cocher "tableau de formatage automatique" qui est en option de tableau croisé dynamique pour Excel 2003|
| [autofit_column_width_on_update](/cells/python-net/fr/aspose.cells.pivot/pivottable/autofit_column_width_on_update) | Indique si l'ajustement automatique de la largeur des colonnes lors de la mise à jour|
| [auto_format_type](/cells/python-net/fr/aspose.cells.pivot/pivottable/auto_format_type) | Obtient le type de formatage automatique du tableau croisé dynamique.|
| [has_blank_rows](/cells/python-net/fr/aspose.cells.pivot/pivottable/has_blank_rows) | Indique s’il faut ajouter des lignes vides.<br/> Cette propriété s'applique uniquement aux types de formatage automatique de tableau croisé dynamique qui doivent ajouter des lignes vides.|
| [merge_labels](/cells/python-net/fr/aspose.cells.pivot/pivottable/merge_labels) | Indique si l'élément de ligne externe, l'élément de colonne, le sous-total, le rapport de tableau croisé dynamique spécifié.<br/> et les étiquettes de total général utilisent des cellules fusionnées.|
| [preserve_formatting](/cells/python-net/fr/aspose.cells.pivot/pivottable/preserve_formatting) |Indique si la mise en forme est conservée lorsque le tableau croisé dynamique est actualisé ou recalculé.|
| [show_drill](/cells/python-net/fr/aspose.cells.pivot/pivottable/show_drill) | Obtient si les boutons développer/réduire sont affichés.|
| [enable_drilldown](/cells/python-net/fr/aspose.cells.pivot/pivottable/enable_drilldown) | Obtient si l’exploration en profondeur est activée.|
| [enable_field_dialog](/cells/python-net/fr/aspose.cells.pivot/pivottable/enable_field_dialog) | Indique si la boîte de dialogue Champ de tableau croisé dynamique est disponible<br/> lorsque l'utilisateur double-clique sur le champ du tableau croisé dynamique.|
| [enable_field_list](/cells/python-net/fr/aspose.cells.pivot/pivottable/enable_field_list) | Obtient si la liste de champs est activée pour le tableau croisé dynamique.|
| [enable_wizard](/cells/python-net/fr/aspose.cells.pivot/pivottable/enable_wizard) | Indique si l'Assistant Tableau croisé dynamique est disponible.|
| [subtotal_hidden_page_items](/cells/python-net/fr/aspose.cells.pivot/pivottable/subtotal_hidden_page_items) | Indique si les éléments de champ de page masqués dans le rapport de tableau croisé dynamique<br/>sont inclus dans les sous-totaux de ligne et de colonne, les totaux de bloc et les totaux généraux.<br/> La valeur par défaut est Faux.|
| [grand_total_name](/cells/python-net/fr/aspose.cells.pivot/pivottable/grand_total_name) | Renvoie l'étiquette de chaîne de texte affichée dans l'en-tête de colonne ou de ligne du total général.<br/> La valeur par défaut est la chaîne « Grand Total ».|
| [manual_update](/cells/python-net/fr/aspose.cells.pivot/pivottable/manual_update) | Indique si le rapport de tableau croisé dynamique est recalculé uniquement à la demande de l'utilisateur.|
| [is_multiple_field_filters](/cells/python-net/fr/aspose.cells.pivot/pivottable/is_multiple_field_filters) | Spécifie une valeur booléenne qui indique si les champs d'un tableau croisé dynamique peuvent avoir plusieurs filtres définis.|
| [missing_items_limit](/cells/python-net/fr/aspose.cells.pivot/pivottable/missing_items_limit) | Spécifie une valeur booléenne qui indique si les champs d'un tableau croisé dynamique peuvent avoir plusieurs filtres définis.|
| [enable_data_value_editing](/cells/python-net/fr/aspose.cells.pivot/pivottable/enable_data_value_editing) |Spécifie une valeur booléenne qui indique si l'utilisateur est autorisé à modifier les cellules de la zone de données du tableau croisé dynamique.<br/> Activer la modification des cellules dans la zone des valeurs|
| [show_data_tips](/cells/python-net/fr/aspose.cells.pivot/pivottable/show_data_tips) | Spécifie une valeur booléenne qui indique si les info-bulles doivent être affichées pour les cellules de données de tableau croisé dynamique.|
| [show_member_property_tips](/cells/python-net/fr/aspose.cells.pivot/pivottable/show_member_property_tips) | Spécifie une valeur booléenne qui indique si les informations sur les propriétés des membres doivent être omises des info-bulles du tableau croisé dynamique.|
| [show_values_row](/cells/python-net/fr/aspose.cells.pivot/pivottable/show_values_row) | Spécifie une valeur booléenne qui indique si la ligne des valeurs est affichée.<br/> afficher la ligne des valeurs|
| [show_empty_col](/cells/python-net/fr/aspose.cells.pivot/pivottable/show_empty_col) | Spécifie une valeur booléenne qui indique s'il faut inclure des colonnes vides dans le tableau|
| [show_empty_row](/cells/python-net/fr/aspose.cells.pivot/pivottable/show_empty_row) | Spécifie une valeur booléenne qui indique s'il faut inclure des lignes vides dans le tableau.|
| [field_list_sort_ascending](/cells/python-net/fr/aspose.cells.pivot/pivottable/field_list_sort_ascending) | Spécifie une valeur booléenne qui indique si les champs du tableau croisé dynamique sont triés dans un ordre différent de celui par défaut dans la liste des champs.|
| [print_drill](/cells/python-net/fr/aspose.cells.pivot/pivottable/print_drill) | Spécifie une valeur booléenne qui indique si les indicateurs d'exploration doivent être imprimés.<br/> imprimer les boutons d'agrandissement/réduction lorsqu'ils sont affichés sur la table pivotante.|
| [alt_text_title](/cells/python-net/fr/aspose.cells.pivot/pivottable/alt_text_title) |Obtient le titre de l'altertext|
| [alt_text_description](/cells/python-net/fr/aspose.cells.pivot/pivottable/alt_text_description) | Obtient la description du texte alternatif|
| [name](/cells/python-net/fr/aspose.cells.pivot/pivottable/name) | Obtient le nom du tableau croisé dynamique|
| [column_header_caption](/cells/python-net/fr/aspose.cells.pivot/pivottable/column_header_caption) | Obtient la légende de l'en-tête de colonne du tableau croisé dynamique.|
| [indent](/cells/python-net/fr/aspose.cells.pivot/pivottable/indent) | Spécifie l'incrément d'indentation pour l'axe compact et peut être utilisé pour définir la présentation du rapport sur Forme compacte.|
| [row_header_caption](/cells/python-net/fr/aspose.cells.pivot/pivottable/row_header_caption) | Obtient la légende de l'en-tête de ligne du tableau croisé dynamique.|
| [show_row_header_caption](/cells/python-net/fr/aspose.cells.pivot/pivottable/show_row_header_caption) | Indique si la légende de l'en-tête de ligne est affichée dans le rapport de tableau croisé dynamique<br/> Indique si Afficher les légendes des champs et les listes déroulantes des filtres|
| [custom_list_sort](/cells/python-net/fr/aspose.cells.pivot/pivottable/custom_list_sort) | Indique s'il faut prendre en compte la liste personnalisée intégrée lors du tri des données|
| [pivot_format_conditions](/cells/python-net/fr/aspose.cells.pivot/pivottable/pivot_format_conditions) | Obtient les conditions de format du tableau croisé dynamique.|
| [page_field_order](/cells/python-net/fr/aspose.cells.pivot/pivottable/page_field_order) | Obtient l'ordre dans lequel les champs de page sont ajoutés à la présentation du rapport de tableau croisé dynamique.|
| [page_field_wrap_count](/cells/python-net/fr/aspose.cells.pivot/pivottable/page_field_wrap_count) | Obtient le nombre de champs de page dans chaque colonne ou ligne du rapport de tableau croisé dynamique.|
| [tag](/cells/python-net/fr/aspose.cells.pivot/pivottable/tag) | Obtient une chaîne enregistrée avec le rapport de tableau croisé dynamique.|
| [save_data](/cells/python-net/fr/aspose.cells.pivot/pivottable/save_data) | Indique si les données du rapport de tableau croisé dynamique sont enregistrées avec le classeur.|
| [refresh_data_on_opening_file](/cells/python-net/fr/aspose.cells.pivot/pivottable/refresh_data_on_opening_file) | Indique si Actualiser les données lors de l'ouverture du fichier.|
| [refresh_data_flag](/cells/python-net/fr/aspose.cells.pivot/pivottable/refresh_data_flag) |Indique si les données sont actualisées ou non.|
| [external_connection_data_source](/cells/python-net/fr/aspose.cells.pivot/pivottable/external_connection_data_source) | Obtient la source de données de connexion externe.|
| [data_source](/cells/python-net/fr/aspose.cells.pivot/pivottable/data_source) | Obtient et définit la source de données du tableau croisé dynamique.|
| [pivot_formats](/cells/python-net/fr/aspose.cells.pivot/pivottable/pivot_formats) | Obtient la collection de formats appliqués au tableau croisé dynamique.|
| [item_print_titles](/cells/python-net/fr/aspose.cells.pivot/pivottable/item_print_titles) | Un bit qui spécifie si les légendes des éléments pivots sur l'axe des lignes<br/> sont répétés sur chaque page imprimée pour les champs pivots sous forme de tableau.|
| [print_titles](/cells/python-net/fr/aspose.cells.pivot/pivottable/print_titles) | Indique si les titres à imprimer de la feuille de calcul sont définis en fonction<br/> sur le rapport de tableau croisé dynamique. La valeur par défaut est fausse.|
| [display_immediate_items](/cells/python-net/fr/aspose.cells.pivot/pivottable/display_immediate_items) | Indique si les éléments des zones de ligne et de colonne sont visibles<br/> lorsque la zone de données du tableau croisé dynamique est vide. La valeur par défaut est vraie.|
| [is_selected](/cells/python-net/fr/aspose.cells.pivot/pivottable/is_selected) | Indique si le tableau croisé dynamique est sélectionné.|
| [show_pivot_style_row_header](/cells/python-net/fr/aspose.cells.pivot/pivottable/show_pivot_style_row_header) | Indique si le style doit être appliqué à l'en-tête de ligne du tableau croisé dynamique.|
| [show_pivot_style_column_header](/cells/python-net/fr/aspose.cells.pivot/pivottable/show_pivot_style_column_header) | Indique si l'en-tête de colonne du tableau croisé dynamique doit avoir le style appliqué.|
| [show_pivot_style_row_stripes](/cells/python-net/fr/aspose.cells.pivot/pivottable/show_pivot_style_row_stripes) | Indique si le formatage des bandes de lignes est appliqué.|
| [show_pivot_style_column_stripes](/cells/python-net/fr/aspose.cells.pivot/pivottable/show_pivot_style_column_stripes) | Indique si la mise en forme des bandes de colonnes est appliquée.|
| [show_pivot_style_last_column](/cells/python-net/fr/aspose.cells.pivot/pivottable/show_pivot_style_last_column) | Indique si la mise en forme des bandes de colonnes est appliquée.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [remove_field](/cells/python-net/fr/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.PivotFieldType-str) |Supprime un champ d'une zone de champ spécifique|
| [remove_field](/cells/python-net/fr/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.PivotFieldType-int) |Supprime un champ d'une zone de champ spécifique|
| [remove_field](/cells/python-net/fr/aspose.cells.pivot/pivottable/remove_field/#aspose.cells.pivot.PivotFieldType-aspose.cells.pivot.PivotField) | Supprimer le champ d'une zone de champ spécifique|
| [add_field_to_area](/cells/python-net/fr/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.PivotFieldType-str) | Ajoute le champ à la zone spécifique.|
| [add_field_to_area](/cells/python-net/fr/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.PivotFieldType-int) | Ajoute le champ à la zone spécifique.|
| [add_field_to_area](/cells/python-net/fr/aspose.cells.pivot/pivottable/add_field_to_area/#aspose.cells.pivot.PivotFieldType-aspose.cells.pivot.PivotField) | Ajoute le champ à la zone spécifique.|
| [add_calculated_field](/cells/python-net/fr/aspose.cells.pivot/pivottable/add_calculated_field/#str-str-bool) | Ajoute un champ calculé au champ pivot.|
| [add_calculated_field](/cells/python-net/fr/aspose.cells.pivot/pivottable/add_calculated_field/#str-str) | Ajoute un champ calculé au champ pivot et faites-le glisser vers la zone de données.|
| [move](/cells/python-net/fr/aspose.cells.pivot/pivottable/move/#int-int) | Déplace le tableau croisé dynamique vers un autre emplacement dans la feuille de calcul.|
| [move](/cells/python-net/fr/aspose.cells.pivot/pivottable/move/#str) | Déplace le tableau croisé dynamique vers un autre emplacement dans la feuille de calcul.|
| [format](/cells/python-net/fr/aspose.cells.pivot/pivottable/format/#aspose.cells.pivot.PivotArea-aspose.cells.Style) | Formate la zone sélectionnée du tableau croisé dynamique.|
| [format](/cells/python-net/fr/aspose.cells.pivot/pivottable/format/#int-int-aspose.cells.Style) | Formater la cellule dans la zone pivotante|
| [set_auto_group_field](/cells/python-net/fr/aspose.cells.pivot/pivottable/set_auto_group_field/#int) | Définit le groupe de champs automatique par le tableau croisé dynamique.|
| [set_auto_group_field](/cells/python-net/fr/aspose.cells.pivot/pivottable/set_auto_group_field/#aspose.cells.pivot.PivotField) | Définit le groupe de champs automatique par le tableau croisé dynamique.|
| [set_manual_group_field](/cells/python-net/fr/aspose.cells.pivot/pivottable/set_manual_group_field/#int-float-float-list-float) | Définit le groupe de champs manuel par le tableau croisé dynamique.|
| [set_manual_group_field](/cells/python-net/fr/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.PivotField-float-float-list-float) | Définit le groupe de champs manuel par le tableau croisé dynamique.|
| [set_manual_group_field](/cells/python-net/fr/aspose.cells.pivot/pivottable/set_manual_group_field/#int-DateTime-DateTime-list-int) | Définit le groupe de champs manuel par le tableau croisé dynamique.|
| [set_manual_group_field](/cells/python-net/fr/aspose.cells.pivot/pivottable/set_manual_group_field/#aspose.cells.pivot.PivotField-DateTime-DateTime-list-int) | Définit le groupe de champs manuel par le tableau croisé dynamique.|
| [set_ungroup](/cells/python-net/fr/aspose.cells.pivot/pivottable/set_ungroup/#int) | Définit le dissociation par le tableau croisé dynamique|
| [set_ungroup](/cells/python-net/fr/aspose.cells.pivot/pivottable/set_ungroup/#aspose.cells.pivot.PivotField) | Définit le dissociation par le tableau croisé dynamique|
| [copy_style](/cells/python-net/fr/aspose.cells.pivot/pivottable/copy_style/#aspose.cells.pivot.PivotTable) | Copie le style nommé à partir d'un autre tableau croisé dynamique.|
| [show_report_filter_page](/cells/python-net/fr/aspose.cells.pivot/pivottable/show_report_filter_page/#aspose.cells.pivot.PivotField) | Afficher toutes les pages de filtre du rapport selon PivotField, le PivotField doit être situé dans les PageFields.|
| [show_report_filter_page_by_name](/cells/python-net/fr/aspose.cells.pivot/pivottable/show_report_filter_page_by_name/#str) | Afficher toutes les pages de filtre du rapport en fonction du nom de PivotField, le PivotField doit être situé dans les PageFields.|
| [show_report_filter_page_by_index](/cells/python-net/fr/aspose.cells.pivot/pivottable/show_report_filter_page_by_index/#int) | Afficher toutes les pages de filtre du rapport en fonction de l'index de position dans les PageFields|
| [fields](/cells/python-net/fr/aspose.cells.pivot/pivottable/fields/#aspose.cells.pivot.PivotFieldType) | Obtient les champs spécifiques par type de champ.|
| [change_data_source](/cells/python-net/fr/aspose.cells.pivot/pivottable/change_data_source/#list) |Définissez les données sources du tableau croisé dynamique.<br/> Feuille 1 ! $A$1 : $C$3|
| [get_source](/cells/python-net/fr/aspose.cells.pivot/pivottable/get_source/#) | Obtenez les données sources du tableau croisé dynamique.|
| [refresh_data](/cells/python-net/fr/aspose.cells.pivot/pivottable/refresh_data/#) | Actualise les données et les paramètres du tableau croisé dynamique à partir de sa source de données.|
| [calculate_data](/cells/python-net/fr/aspose.cells.pivot/pivottable/calculate_data/#) | Calcule les données du tableau croisé dynamique en cellules.|
| [clear_data](/cells/python-net/fr/aspose.cells.pivot/pivottable/clear_data/#) | Effacer les données et le formatage du tableau croisé dynamique|
| [calculate_range](/cells/python-net/fr/aspose.cells.pivot/pivottable/calculate_range/#) | Calcule la plage du tableau croisé dynamique.|
| [format_all](/cells/python-net/fr/aspose.cells.pivot/pivottable/format_all/#aspose.cells.Style) | Formater toutes les cellules de la zone pivotante|
| [format_row](/cells/python-net/fr/aspose.cells.pivot/pivottable/format_row/#int-aspose.cells.Style) | Formatez les données de la ligne dans la zone du tableau croisé dynamique|
| [get_horizontal_breaks](/cells/python-net/fr/aspose.cells.pivot/pivottable/get_horizontal_breaks/#) | obtenir la liste d'index des lignes du tableau croisé dynamique des sauts de page horizontaux|
| [show_in_compact_form](/cells/python-net/fr/aspose.cells.pivot/pivottable/show_in_compact_form/#) | Présente le tableau croisé dynamique sous forme compacte.|
| [show_in_outline_form](/cells/python-net/fr/aspose.cells.pivot/pivottable/show_in_outline_form/#) | Présente le tableau croisé dynamique sous forme de plan.|
| [show_in_tabular_form](/cells/python-net/fr/aspose.cells.pivot/pivottable/show_in_tabular_form/#) | Présente le tableau croisé dynamique sous forme de tableau.|
| [get_cell_by_display_name](/cells/python-net/fr/aspose.cells.pivot/pivottable/get_cell_by_display_name/#str) | Obtient l’objet [`Cell`](/cells/python-net/fr/aspose.cells/cell) sous le nom d’affichage PivotField.|
| [get_children](/cells/python-net/fr/aspose.cells.pivot/pivottable/get_children/#) | Obtient les tableaux croisés dynamiques enfants qui utilisent ces données de tableau croisé dynamique comme source de données.|



###  Exemple

```python
from aspose.cells import FormatConditionType, OperatorType, Workbook
from aspose.cells.pivot import PivotFieldType, PivotFilterType, PivotTableStyleType
from aspose.pydrawing import Color

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Change PivotField's attributes
rowField = pivot.row_fields[0]
rowField.display_name = "custom display name"
# Add PivotFilter
index = pivot.pivot_filters.add(0, PivotFilterType.COUNT)
filter = pivot.pivot_filters[index]
filter.auto_filter.filter_top10(0, False, False, 2)
# Add PivotFormatCondition
formatIndex = pivot.pivot_format_conditions.add()
pfc = pivot.pivot_format_conditions[formatIndex]
fcc = pfc.format_conditions
fcc.add_area(pivot.data_body_range)
idx = fcc.add_condition(FormatConditionType.CELL_VALUE)
fc = fcc[idx]
fc.formula1 = "100"
fc.operator = OperatorType.GREATER_OR_EQUAL
fc.style.background_color = Color.red
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  Voir également
* module [`aspose.cells.pivot`](..)
* classe [`Cell`](/cells/python-net/fr/aspose.cells/cell)
