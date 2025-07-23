---
title: SettableGlobalizationSettings classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1310
url: /fr/aspose.cells/settableglobalizationsettings/
is_root: false
---
##  SettableGlobalizationSettings classe
Implémentation de GlobalizationSettings qui permet à l'utilisateur de définir/modifier des textes prédéfinis.



**Héritage:** [`SettableGlobalizationSettings`](/cells/python-net/aspose.cells/settableglobalizationsettings) → 
[`GlobalizationSettings`](/cells/python-net/fr/aspose.cells/globalizationsettings)



Le type SettableGlobalizationSettings expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/__init__/#) | Construit une nouvelle instance de SettableGlobalizationSettings|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [chart_settings](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/chart_settings) | Obtient ou définit les paramètres de globalisation pour Chart.|
| [pivot_settings](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/pivot_settings) | Obtient ou définit les paramètres de globalisation pour le tableau croisé dynamique.|
| [list_separator](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/list_separator) | Obtient le séparateur pour la liste, les paramètres de la fonction, ...etc.|
| [row_separator_of_formula_array](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/row_separator_of_formula_array) | Obtient le séparateur pour les lignes dans les données du tableau dans la formule.|
| [column_separator_of_formula_array](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/column_separator_of_formula_array) |Obtient le séparateur pour les éléments dans les données de ligne du tableau dans la formule.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`get_pivot_total_name(self)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_pivot_total_name/#) | Obtient le nom de l'étiquette « Total » dans le tableau croisé dynamique.<br/> Vous devez remplacer cette méthode lorsque le tableau croisé dynamique contient deux champs croisés dynamiques ou plus dans la zone de données.|
| [`get_pivot_grand_total_name(self)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_pivot_grand_total_name/#) | Obtient le nom de l'étiquette « Total général » dans le tableau croisé dynamique.|
| [`get_multiple_items_name(self)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_multiple_items_name/#) | Obtient le nom de l'étiquette « (Plusieurs éléments) » dans le tableau croisé dynamique.|
| [`get_all_name(self)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_all_name/#) | Obtient le nom de l'étiquette « (Tous) » dans le tableau croisé dynamique.|
| [`get_protection_name_of_pivot_table(self)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_protection_name_of_pivot_table/#) | Obtient le nom de protection dans le tableau croisé dynamique.|
| [`get_column_labels_of_pivot_table(self)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_column_labels_of_pivot_table/#) | Obtient le nom de l'étiquette « Étiquettes de colonne » dans le tableau croisé dynamique.|
| [`get_row_labels_name_of_pivot_table(self)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_row_labels_name_of_pivot_table/#) | Obtient le nom de l'étiquette « Étiquettes de ligne » dans le tableau croisé dynamique.|
| [`get_empty_data_name(self)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_empty_data_name/#) | Obtient le nom de l'étiquette « (vide) » dans le tableau croisé dynamique.|
| [`get_data_field_header_name_of_pivot_table(self)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_data_field_header_name_of_pivot_table/#) | Obtient le nom de l'en-tête du champ de zone de valeur dans le tableau croisé dynamique.|
| [`get_sub_total_name(self, sub_total_type)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_sub_total_name/#aspose.cells.pivot.pivotfieldsubtotaltype) | Obtient le nom du type [`PivotFieldSubtotalType`](/cells/python-net/fr/aspose.cells.pivot/pivotfieldsubtotaltype) dans le tableau croisé dynamique.|
| [`get_total_name(self, function_type)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_total_name/#aspose.cells.consolidationfunction) | Obtient le nom total d'une fonction spécifique.|
| [`get_grand_total_name(self, function_type)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_grand_total_name/#aspose.cells.consolidationfunction) | Obtient le nom total général de la fonction.|
| [`get_default_sheet_name(self)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_default_sheet_name/#) |Obtient le nom de la feuille par défaut pour ajouter automatiquement une feuille de calcul.<br/> La valeur par défaut est « Feuille ».|
| [`get_table_row_type_of_headers(self)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_table_row_type_of_headers/#) | Obtient le nom de type des lignes de table constituées de l'en-tête de table.<br/> La valeur par défaut est « En-têtes », donc dans la formule « #En-têtes » représente l'en-tête du tableau.|
| [`get_table_row_type_of_data(self)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_table_row_type_of_data/#) | Obtient le nom du type des lignes de table qui se composent de la région de données de la table référencée.<br/> La valeur par défaut est « Données », donc dans la formule « #Données » représente la région de données de la table.|
| [`get_table_row_type_of_all(self)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_table_row_type_of_all/#) | Obtient le nom de type des lignes de la table qui se compose de toutes les lignes de la table référencée.|
| [`get_table_row_type_of_totals(self)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_table_row_type_of_totals/#) | Obtient le nom de type des lignes de table qui se composent de la ligne totale de la table référencée.|
| [`get_table_row_type_of_current(self)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_table_row_type_of_current/#) |Obtient le nom de type des lignes de table qui se composent de la ligne actuelle dans la table référencée.|
| [`get_error_value_string(self, err)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_error_value_string/#str) | Obtient la valeur de la chaîne d'affichage pour la valeur d'erreur de la cellule|
| [`get_boolean_value_string(self, bv)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_boolean_value_string/#bool) | Obtient la valeur de la chaîne d'affichage pour la valeur booléenne de la cellule|
| [`get_local_function_name(self, standard_name)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_local_function_name/#str) | Obtient le nom de la fonction dépendant des paramètres régionaux en fonction du nom de fonction standard donné.|
| [`get_standard_function_name(self, local_name)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_standard_function_name/#str) | Obtient le nom de la fonction standard en fonction du nom de la fonction dépendant des paramètres régionaux donnés.|
| [`get_local_built_in_name(self, standard_name)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_local_built_in_name/#str) | Obtient le texte dépendant des paramètres régionaux pour le nom intégré selon le texte standard donné.|
| [`get_standard_built_in_name(self, local_name)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_standard_built_in_name/#str) | Obtient le texte standard du nom intégré en fonction du texte dépendant des paramètres régionaux donnés.|
| [`get_standard_header_footer_font_style_name(self, localfont_style_name)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_standard_header_footer_font_style_name/#str) | Obtient le nom de style de police anglais standard (normal, gras, italique) pour l'en-tête/pied de page en fonction du nom de style de police local donné.|
| [`get_comment_title_name(self, type)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/get_comment_title_name/#aspose.cells.rendering.commenttitletype) | Obtient le nom du titre du commentaire dépendant des paramètres régionaux en fonction du type de titre du commentaire.|
| [`compare(self, v1, v2, ignore_case)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/compare/#str-str-bool) | Compare deux valeurs de chaîne selon certaines règles de classement.|
| [`set_total_name(self, function_type, name)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/set_total_name/#aspose.cells.consolidationfunction-str) | Définit le nom total d'une fonction spécifique.|
| [`set_grand_total_name(self, function_type, name)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/set_grand_total_name/#aspose.cells.consolidationfunction-str) | Définit le nom total général d'une fonction spécifique.|
| [`set_table_row_type_of_headers(self, name)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/set_table_row_type_of_headers/#str) | Définit le nom du type des lignes du tableau qui se composent de l'en-tête du tableau.|
| [`set_table_row_type_of_data(self, name)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/set_table_row_type_of_data/#str) | Définit le nom du type des lignes de table qui se composent de la région de données de la table référencée.|
| [`set_table_row_type_of_all(self, name)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/set_table_row_type_of_all/#str) | Définit le nom du type des lignes de la table qui se compose de toutes les lignes de la table référencée.|
| [`set_table_row_type_of_totals(self, name)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/set_table_row_type_of_totals/#str) | Définit le nom du type des lignes de table qui se composent de la ligne totale de la table référencée.|
| [`set_table_row_type_of_current(self, name)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/set_table_row_type_of_current/#str) | Définit le nom du type des lignes de table qui se composent de la ligne actuelle dans la table référencée.|
| [`set_boolean_value_string(self, bv, name)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/set_boolean_value_string/#bool-str) | Définit la valeur de la chaîne d'affichage pour la valeur booléenne de la cellule|
| [`set_local_function_name(self, standard_name, local_name, bidirectional)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/set_local_function_name/#str-str-bool) | Définit le nom de la fonction dépendante des paramètres régionaux correspondant au nom de fonction standard donné.|
| [`set_standard_function_name(self, local_name, standard_name, bidirectional)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/set_standard_function_name/#str-str-bool) | Définit le nom de la fonction dépendant des paramètres régionaux en fonction du nom de fonction standard donné.|
| [`set_local_built_in_name(self, standard_name, local_name, bidirectional)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/set_local_built_in_name/#str-str-bool) | Définit le texte dépendant des paramètres régionaux pour le nom intégré avec le texte de nom standard donné.|
| [`set_standard_built_in_name(self, local_name, standard_name, bidirectional)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/set_standard_built_in_name/#str-str-bool) | Définit le nom de la fonction dépendant des paramètres régionaux en fonction du nom de fonction standard donné.|
| [`set_list_separator(self, c)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/set_list_separator/#char) |Définit le séparateur pour la liste, les paramètres de fonction, ...etc.|
| [`set_row_separator_of_formula_array(self, c)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/set_row_separator_of_formula_array/#char) | Définit le séparateur pour les lignes dans les données du tableau dans la formule.|
| [`set_column_separator_of_formula_array(self, c)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/set_column_separator_of_formula_array/#char) | Définit le séparateur pour les éléments dans les données de ligne du tableau dans la formule.|
| [`set_standard_header_footer_font_style_name(self, localfont_style_name, standard_name)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/set_standard_header_footer_font_style_name/#str-str) | Définit le nom de la fonction dépendant des paramètres régionaux en fonction du nom de fonction standard donné.|
| [`set_comment_title_name(self, type, name)`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings/set_comment_title_name/#aspose.cells.rendering.commenttitletype-str) | Obtient le nom du titre du commentaire dépendant des paramètres régionaux en fonction du type de titre du commentaire.|



###  Voir également
* module [`aspose.cells`](..)
* classe [`GlobalizationSettings`](/cells/python-net/fr/aspose.cells/globalizationsettings)
* classe [`PivotFieldSubtotalType`](/cells/python-net/fr/aspose.cells.pivot/pivotfieldsubtotaltype)
* classe [`SettableGlobalizationSettings`](/cells/python-net/fr/aspose.cells/settableglobalizationsettings)
