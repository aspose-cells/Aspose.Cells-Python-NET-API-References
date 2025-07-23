---
title: Cells classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 160
url: /fr/aspose.cells/cells/
is_root: false
---
##  Cells classe
Encapsule une collection d'objets pertinents pour les cellules, tels que [`Cell`](/cells/python-net/fr/aspose.cells/cell), [`Row`](/cells/python-net/fr/aspose.cells/row), ...etc.



Le type Cells expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [ods_cell_fields](/cells/python-net/fr/aspose.cells/cells/ods_cell_fields) | Obtient la liste des champs d'ods.|
| [count](/cells/python-net/fr/aspose.cells/cells/count) | Obtient le nombre total d'objets Cell instanciés.|
| [count_large](/cells/python-net/fr/aspose.cells/cells/count_large) | Obtient le nombre total d'objets Cell instanciés.|
| [rows](/cells/python-net/fr/aspose.cells/cells/rows) | Obtient la collection de [`Row`](/cells/python-net/fr/aspose.cells/row) objets qui représentent les lignes individuelles de cette feuille de calcul.|
| [merged_cells](/cells/python-net/fr/aspose.cells/cells/merged_cells) | Obtient la collection de cellules fusionnées.|
| [multi_thread_reading](/cells/python-net/fr/aspose.cells/cells/multi_thread_reading) | Obtient ou définit si le modèle de données des cellules doit prendre en charge la lecture multithread.<br/> La valeur par défaut de cette propriété est false.|
| [memory_setting](/cells/python-net/fr/aspose.cells/cells/memory_setting) | Obtient ou définit l'option d'utilisation de la mémoire pour ces cellules.|
| [style](/cells/python-net/fr/aspose.cells/cells/style) | Obtient et définit le style par défaut de la feuille de calcul.|
| [is_default_column_hidden](/cells/python-net/fr/aspose.cells/cells/is_default_column_hidden) |  |
| [standard_width_inch](/cells/python-net/fr/aspose.cells/cells/standard_width_inch) | Obtient ou définit la largeur de colonne par défaut dans la feuille de calcul, en pouces.|
| [standard_width_pixels](/cells/python-net/fr/aspose.cells/cells/standard_width_pixels) |Obtient ou définit la largeur de colonne par défaut dans la feuille de calcul, en unités de pixels.|
| [standard_width](/cells/python-net/fr/aspose.cells/cells/standard_width) | Obtient ou définit la largeur de colonne par défaut dans la feuille de calcul, en unités de caractères.|
| [standard_height](/cells/python-net/fr/aspose.cells/cells/standard_height) | Obtient ou définit la hauteur de ligne par défaut dans cette feuille de calcul, en unités de points.|
| [standard_height_pixels](/cells/python-net/fr/aspose.cells/cells/standard_height_pixels) | Obtient ou définit la hauteur de ligne par défaut dans cette feuille de calcul, en unités de pixels.|
| [standard_height_inch](/cells/python-net/fr/aspose.cells/cells/standard_height_inch) | Obtient ou définit la hauteur de ligne par défaut dans cette feuille de calcul, en pouces.|
| [preserve_string](/cells/python-net/fr/aspose.cells/cells/preserve_string) | Obtient ou définit une valeur indiquant si toutes les valeurs de la feuille de calcul sont conservées sous forme de chaînes.<br/> La valeur par défaut est faux.|
| [min_row](/cells/python-net/fr/aspose.cells/cells/min_row) | Index de ligne minimum de la cellule contenant des données ou un style.|
| [max_row](/cells/python-net/fr/aspose.cells/cells/max_row) | Index de ligne maximal de la cellule contenant des données ou un style.|
| [min_column](/cells/python-net/fr/aspose.cells/cells/min_column) | Index de colonne minimum des cellules qui ont été instanciées dans la collection (n'inclut pas la colonne)<br/> où le style est défini pour la colonne entière mais aucune cellule n'y a été instanciée).|
| [max_column](/cells/python-net/fr/aspose.cells/cells/max_column) | Index de colonne maximal des cellules qui ont été instanciées dans la collection (n'inclut pas la colonne)<br/> où le style est défini pour la colonne entière mais aucune cellule n'y a été instanciée).|
| [min_data_row](/cells/python-net/fr/aspose.cells/cells/min_data_row) |Index de ligne minimum de la cellule contenant des données.|
| [max_data_row](/cells/python-net/fr/aspose.cells/cells/max_data_row) | Index de ligne maximal de la cellule contenant des données.|
| [min_data_column](/cells/python-net/fr/aspose.cells/cells/min_data_column) | Index de colonne minimum de la cellule contenant des données.|
| [max_data_column](/cells/python-net/fr/aspose.cells/cells/max_data_column) | Index de colonne maximal de la cellule contenant des données.|
| [is_default_row_height_matched](/cells/python-net/fr/aspose.cells/cells/is_default_row_height_matched) | Indique que la hauteur de ligne et la hauteur de police par défaut correspondent|
| [is_default_row_hidden](/cells/python-net/fr/aspose.cells/cells/is_default_row_hidden) | Indique si la ligne est masquée par défaut.|
| [columns](/cells/python-net/fr/aspose.cells/cells/columns) | Obtient la collection de [`Column`](/cells/python-net/fr/aspose.cells/column) objets qui représentent les colonnes individuelles de cette feuille de calcul.|
| [ranges](/cells/python-net/fr/aspose.cells/cells/ranges) | Obtient la collection de [`Range`](/cells/python-net/fr/aspose.cells/range) objets créés au moment de l'exécution.|
| [last_cell](/cells/python-net/fr/aspose.cells/cells/last_cell) | Obtient la dernière cellule de cette feuille de calcul.|
| [max_display_range](/cells/python-net/fr/aspose.cells/cells/max_display_range) | Obtient la plage maximale qui inclut les données, les cellules fusionnées et les formes.|
| [first_cell](/cells/python-net/fr/aspose.cells/cells/first_cell) | Obtient la première cellule de cette feuille de calcul.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`create_range(self, upper_left_cell, lower_right_cell)`](/cells/python-net/fr/aspose.cells/cells/create_range/#str-str) | Crée un objet [`Range`](/cells/python-net/fr/aspose.cells/range) à partir d'une plage de cellules.|
| [`create_range(self, first_row, first_column, total_rows, total_columns)`](/cells/python-net/fr/aspose.cells/cells/create_range/#int-int-int-int) | Crée un objet [`Range`](/cells/python-net/fr/aspose.cells/range) à partir d'une plage de cellules.|
| [`create_range(self, address)`](/cells/python-net/fr/aspose.cells/cells/create_range/#str) | Crée un objet [`Range`](/cells/python-net/fr/aspose.cells/range) à partir d'une adresse de la plage.|
| [`create_range(self, first_index, number, is_vertical)`](/cells/python-net/fr/aspose.cells/cells/create_range/#int-int-bool) | Crée un objet [`Range`](/cells/python-net/fr/aspose.cells/range) à partir de lignes de cellules ou de colonnes de cellules.|
| [`get(self, row, column)`](/cells/python-net/fr/aspose.cells/cells/get/#int-int) | Ajoutez API for Python via .Net. puisque ceci [int row, int column] n'est pas pris en charge|
| [`get(self, cell_name)`](/cells/python-net/fr/aspose.cells/cells/get/#str) |Ajoutez API for Python via .Net. puisque cette [chaîne cellName] n'est pas prise en charge|
| [`import_object_array(self, obj_array, first_row, first_column, is_vertical)`](/cells/python-net/fr/aspose.cells/cells/import_object_array/#list-int-int-bool) | Importe un tableau de données dans une feuille de calcul.|
| [`import_object_array(self, obj_array, first_row, first_column, is_vertical, skip)`](/cells/python-net/fr/aspose.cells/cells/import_object_array/#list-int-int-bool-int) | Importe un tableau de données dans une feuille de calcul.|
| [`import_array(self, string_array, first_row, first_column, is_vertical)`](/cells/python-net/fr/aspose.cells/cells/import_array/#list-int-int-bool) | Importe un tableau de chaînes dans une feuille de calcul.|
| [`import_array(self, int_array, first_row, first_column, is_vertical)`](/cells/python-net/fr/aspose.cells/cells/import_array/#list-int-int-bool) | Importe un tableau d'entiers dans une feuille de calcul.|
| [`import_array(self, double_array, first_row, first_column, is_vertical)`](/cells/python-net/fr/aspose.cells/cells/import_array/#list-int-int-bool) | Importe un tableau de doubles dans une feuille de calcul.|
| [`import_csv(self, file_name, splitter, convert_numeric_data, first_row, first_column)`](/cells/python-net/fr/aspose.cells/cells/import_csv/#str-str-bool-int-int) | Importez un fichier CSV dans les cellules.|
| [`import_csv(self, stream, splitter, convert_numeric_data, first_row, first_column)`](/cells/python-net/fr/aspose.cells/cells/import_csv/#io.rawiobase-str-bool-int-int) | Importez un fichier CSV dans les cellules.|
| [`import_csv(self, file_name, options, first_row, first_column)`](/cells/python-net/fr/aspose.cells/cells/import_csv/#str-aspose.cells.txtloadoptions-int-int) | Importez un fichier CSV dans les cellules.|
| [`import_csv(self, stream, options, first_row, first_column)`](/cells/python-net/fr/aspose.cells/cells/import_csv/#io.rawiobase-aspose.cells.txtloadoptions-int-int) | Importez un fichier CSV dans les cellules.|
| [`merge(self, first_row, first_column, total_rows, total_columns)`](/cells/python-net/fr/aspose.cells/cells/merge/#int-int-int-int) | Fusionne une plage de cellules spécifiée en une seule cellule.|
| [`merge(self, first_row, first_column, total_rows, total_columns, merge_conflict)`](/cells/python-net/fr/aspose.cells/cells/merge/#int-int-int-int-bool) | Fusionne une plage de cellules spécifiée en une seule cellule.|
| [`merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict)`](/cells/python-net/fr/aspose.cells/cells/merge/#int-int-int-int-bool-bool) | Fusionne une plage de cellules spécifiée en une seule cellule.|
| [`get_row_height(self, row, is_original, unit_type)`](/cells/python-net/fr/aspose.cells/cells/get_row_height/#int-bool-aspose.cells.cellsunittype) | Obtient la hauteur de la ligne.|
| [`get_row_height(self, row)`](/cells/python-net/fr/aspose.cells/cells/get_row_height/#int) | Obtient la hauteur d'une ligne spécifiée, en unités de points.|
| [`get_column_width(self, column, is_original, unit_type)`](/cells/python-net/fr/aspose.cells/cells/get_column_width/#int-bool-aspose.cells.cellsunittype) | Obtient la largeur de la colonne.|
| [`get_column_width(self, column)`](/cells/python-net/fr/aspose.cells/cells/get_column_width/#int) | Obtient la largeur (en unités de caractères) de la colonne spécifiée en vue normale|
| [`get_column_width_pixel(self, column)`](/cells/python-net/fr/aspose.cells/cells/get_column_width_pixel/#int) | Obtient la largeur de la colonne spécifiée en vue normale, en unités de pixels.|
| [`get_column_width_pixel(self, column, original)`](/cells/python-net/fr/aspose.cells/cells/get_column_width_pixel/#int-bool) | Obtient la largeur de la colonne spécifiée en vue normale, en unités de pixels.|
| [`copy_columns(self, source_cells0, source_column_index, destination_column_index, column_number, paste_options)`](/cells/python-net/fr/aspose.cells/cells/copy_columns/#aspose.cells.cells-int-int-int-aspose.cells.pasteoptions) | Copie les données et les formats d'une colonne entière.|
| [`copy_columns(self, source_cells0, source_column_index, destination_column_index, column_number)`](/cells/python-net/fr/aspose.cells/cells/copy_columns/#aspose.cells.cells-int-int-int) | Copie les données et les formats d'une colonne entière.|
| [`copy_columns(self, source_cells, source_column_index, source_total_columns, destination_column_index, destination_total_columns)`](/cells/python-net/fr/aspose.cells/cells/copy_columns/#aspose.cells.cells-int-int-int-int) | Copie les données et les formats de toutes les colonnes.|
| [`copy_rows(self, source_cells, source_row_index, destination_row_index, row_number)`](/cells/python-net/fr/aspose.cells/cells/copy_rows/#aspose.cells.cells-int-int-int) | Copie les données et les formats de certaines lignes entières.|
| [`copy_rows(self, source_cells0, source_row_index, destination_row_index, row_number, copy_options)`](/cells/python-net/fr/aspose.cells/cells/copy_rows/#aspose.cells.cells-int-int-int-aspose.cells.copyoptions) | Copie les données et les formats de certaines lignes entières.|
| [`copy_rows(self, source_cells0, source_row_index, destination_row_index, row_number, copy_options, paste_options)`](/cells/python-net/fr/aspose.cells/cells/copy_rows/#aspose.cells.cells-int-int-int-aspose.cells.copyoptions-aspose.cells.pasteoptions) | Copie les données et les formats de certaines lignes entières.|
| [`group_columns(self, first_index, last_index)`](/cells/python-net/fr/aspose.cells/cells/group_columns/#int-int) | Colonnes de groupes.|
| [`group_columns(self, first_index, last_index, is_hidden)`](/cells/python-net/fr/aspose.cells/cells/group_columns/#int-int-bool) | Colonnes de groupes.|
| [`ungroup_rows(self, first_index, last_index, is_all)`](/cells/python-net/fr/aspose.cells/cells/ungroup_rows/#int-int-bool) | Dissocie les lignes.|
| [`ungroup_rows(self, first_index, last_index)`](/cells/python-net/fr/aspose.cells/cells/ungroup_rows/#int-int) | Dissocie les lignes.|
| [`group_rows(self, first_index, last_index, is_hidden)`](/cells/python-net/fr/aspose.cells/cells/group_rows/#int-int-bool) | Groupes de lignes.|
| [`group_rows(self, first_index, last_index)`](/cells/python-net/fr/aspose.cells/cells/group_rows/#int-int) | Groupes de lignes.|
| [`delete_column(self, column_index, update_reference)`](/cells/python-net/fr/aspose.cells/cells/delete_column/#int-bool) | Supprime une colonne.|
| [`delete_column(self, column_index)`](/cells/python-net/fr/aspose.cells/cells/delete_column/#int) | Supprime une colonne.|
| [`delete_columns(self, column_index, total_columns, update_reference)`](/cells/python-net/fr/aspose.cells/cells/delete_columns/#int-int-bool) | Supprime plusieurs colonnes.|
| [`delete_columns(self, column_index, total_columns, options)`](/cells/python-net/fr/aspose.cells/cells/delete_columns/#int-int-aspose.cells.deleteoptions) | Supprime plusieurs colonnes.|
| [`delete_row(self, row_index)`](/cells/python-net/fr/aspose.cells/cells/delete_row/#int) | Supprime une ligne.|
| [`delete_row(self, row_index, update_reference)`](/cells/python-net/fr/aspose.cells/cells/delete_row/#int-bool) | Supprime une ligne.|
| [`delete_rows(self, row_index, total_rows)`](/cells/python-net/fr/aspose.cells/cells/delete_rows/#int-int) |Supprime plusieurs lignes.|
| [`delete_rows(self, row_index, total_rows, update_reference)`](/cells/python-net/fr/aspose.cells/cells/delete_rows/#int-int-bool) | Supprime plusieurs lignes dans la feuille de calcul.|
| [`delete_rows(self, row_index, total_rows, options)`](/cells/python-net/fr/aspose.cells/cells/delete_rows/#int-int-aspose.cells.deleteoptions) | Supprime plusieurs lignes dans la feuille de calcul.|
| [`delete_blank_columns(self)`](/cells/python-net/fr/aspose.cells/cells/delete_blank_columns/#) | Supprimez toutes les colonnes vides qui ne contiennent aucune donnée.|
| [`delete_blank_columns(self, options)`](/cells/python-net/fr/aspose.cells/cells/delete_blank_columns/#aspose.cells.deleteoptions) | Supprimez toutes les colonnes vides qui ne contiennent aucune donnée.|
| [`delete_blank_rows(self)`](/cells/python-net/fr/aspose.cells/cells/delete_blank_rows/#) | Supprimez toutes les lignes vides qui ne contiennent aucune donnée ni aucun autre objet.|
| [`delete_blank_rows(self, options)`](/cells/python-net/fr/aspose.cells/cells/delete_blank_rows/#aspose.cells.deleteoptions) | Supprimez toutes les lignes vides qui ne contiennent aucune donnée ou certains objets spéciaux tels que des commentaires visibles, des tableaux croisés dynamiques.|
| [`insert_columns(self, column_index, total_columns)`](/cells/python-net/fr/aspose.cells/cells/insert_columns/#int-int) | Insère quelques colonnes dans la feuille de calcul.|
| [`insert_columns(self, column_index, total_columns, update_reference)`](/cells/python-net/fr/aspose.cells/cells/insert_columns/#int-int-bool) | Insère quelques colonnes dans la feuille de calcul.|
| [`insert_columns(self, column_index, total_columns, options)`](/cells/python-net/fr/aspose.cells/cells/insert_columns/#int-int-aspose.cells.insertoptions) | Insère quelques colonnes dans la feuille de calcul.|
| [`insert_column(self, column_index, update_reference)`](/cells/python-net/fr/aspose.cells/cells/insert_column/#int-bool) | Insère une nouvelle colonne dans la feuille de calcul.|
| [`insert_column(self, column_index)`](/cells/python-net/fr/aspose.cells/cells/insert_column/#int) | Insère une nouvelle colonne dans la feuille de calcul.|
| [`insert_rows(self, row_index, total_rows, update_reference)`](/cells/python-net/fr/aspose.cells/cells/insert_rows/#int-int-bool) | Insère plusieurs lignes dans la feuille de calcul.|
| [`insert_rows(self, row_index, total_rows, options)`](/cells/python-net/fr/aspose.cells/cells/insert_rows/#int-int-aspose.cells.insertoptions) | Insère plusieurs lignes dans la feuille de calcul.|
| [`insert_rows(self, row_index, total_rows)`](/cells/python-net/fr/aspose.cells/cells/insert_rows/#int-int) | Insère plusieurs lignes dans la feuille de calcul.|
| [`clear_range(self, range)`](/cells/python-net/fr/aspose.cells/cells/clear_range/#aspose.cells.cellarea) | Efface le contenu et la mise en forme d'une plage.|
| [`clear_range(self, start_row, start_column, end_row, end_column)`](/cells/python-net/fr/aspose.cells/cells/clear_range/#int-int-int-int) | Efface le contenu et la mise en forme d'une plage.|
| [`clear_contents(self, range)`](/cells/python-net/fr/aspose.cells/cells/clear_contents/#aspose.cells.cellarea) | Efface le contenu d'une plage.|
| [`clear_contents(self, start_row, start_column, end_row, end_column)`](/cells/python-net/fr/aspose.cells/cells/clear_contents/#int-int-int-int) | Efface le contenu d'une plage.|
| [`clear_formats(self, range)`](/cells/python-net/fr/aspose.cells/cells/clear_formats/#aspose.cells.cellarea) | Efface la mise en forme d'une plage.|
| [`clear_formats(self, start_row, start_column, end_row, end_column)`](/cells/python-net/fr/aspose.cells/cells/clear_formats/#int-int-int-int) | Efface la mise en forme d'une plage.|
| [`find(self, what, previous_cell)`](/cells/python-net/fr/aspose.cells/cells/find/#any-aspose.cells.cell) | Recherche la cellule contenant l'objet d'entrée.|
| [`find(self, what, previous_cell, find_options)`](/cells/python-net/fr/aspose.cells/cells/find/#any-aspose.cells.cell-aspose.cells.findoptions) | Recherche la cellule contenant l'objet d'entrée.|
| [`end_cell_in_row(self, row_index)`](/cells/python-net/fr/aspose.cells/cells/end_cell_in_row/#int) | Obtient la dernière cellule de cette ligne.|
| [`end_cell_in_row(self, start_row, end_row, start_column, end_column)`](/cells/python-net/fr/aspose.cells/cells/end_cell_in_row/#int-int-int-int) | Obtient la dernière cellule avec l'index de ligne maximal dans cette plage.|
| [`end_cell_in_column(self, column_index)`](/cells/python-net/fr/aspose.cells/cells/end_cell_in_column/#int) | Obtient la dernière cellule de cette colonne.|
| [`end_cell_in_column(self, start_row, end_row, start_column, end_column)`](/cells/python-net/fr/aspose.cells/cells/end_cell_in_column/#int-int-int-int) | Obtient la dernière cellule avec l'index de colonne maximal dans cette plage.|
| [`insert_range(self, area, shift_number, shift_type, update_reference)`](/cells/python-net/fr/aspose.cells/cells/insert_range/#aspose.cells.cellarea-int-aspose.cells.shifttype-bool) | Insère une plage de cellules et décale les cellules en fonction de l'option de décalage.|
| [`insert_range(self, area, shift_type)`](/cells/python-net/fr/aspose.cells/cells/insert_range/#aspose.cells.cellarea-aspose.cells.shifttype) | Insère une plage de cellules et décale les cellules en fonction de l'option de décalage.|
| [`insert_range(self, area, shift_number, shift_type)`](/cells/python-net/fr/aspose.cells/cells/insert_range/#aspose.cells.cellarea-int-aspose.cells.shifttype) | Insère une plage de cellules et décale les cellules en fonction de l'option de décalage.|
| [`subtotal(self, ca, group_by, function, total_list)`](/cells/python-net/fr/aspose.cells/cells/subtotal/#aspose.cells.cellarea-int-aspose.cells.consolidationfunction-list) | Crée des sous-totaux pour la plage.|
| [`subtotal(self, ca, group_by, function, total_list, replace, page_breaks, summary_below_data)`](/cells/python-net/fr/aspose.cells/cells/subtotal/#aspose.cells.cellarea-int-aspose.cells.consolidationfunction-list-bool-bool-bool) | Crée des sous-totaux pour la plage.|
| [`remove_duplicates(self)`](/cells/python-net/fr/aspose.cells/cells/remove_duplicates/#) |Supprime les lignes en double dans la feuille.|
| [`remove_duplicates(self, start_row, start_column, end_row, end_column)`](/cells/python-net/fr/aspose.cells/cells/remove_duplicates/#int-int-int-int) | Supprime les valeurs en double dans la plage.|
| [`remove_duplicates(self, start_row, start_column, end_row, end_column, has_headers, column_offsets)`](/cells/python-net/fr/aspose.cells/cells/remove_duplicates/#int-int-int-int-bool-list) | Supprime les données en double de la plage.|
| [`get_cell_display_style(self, row, column)`](/cells/python-net/fr/aspose.cells/cells/get_cell_display_style/#int-int) | Obtenez le style d'affichage de la cellule donnée.|
| [`get_cell_display_style(self, row, column, adjacent_borders)`](/cells/python-net/fr/aspose.cells/cells/get_cell_display_style/#int-int-aspose.cells.bordertype) | Obtenez le style d'affichage de la cellule donnée.|
| [`get_row_enumerator(self)`](/cells/python-net/fr/aspose.cells/cells/get_row_enumerator/#) | Obtient l'énumérateur de lignes.|
| [`get_merged_areas(self)`](/cells/python-net/fr/aspose.cells/cells/get_merged_areas/#) | Obtient toutes les cellules fusionnées.|
| [`get_cell(self, row, column)`](/cells/python-net/fr/aspose.cells/cells/get_cell/#int-int) | Obtient l'élément [`Cell`](/cells/python-net/fr/aspose.cells/cell) ou null à l'index de ligne de cellule et à l'index de colonne spécifiés.|
| [`get_row(self, row)`](/cells/python-net/fr/aspose.cells/cells/get_row/#int) | Obtient l'élément [`Row`](/cells/python-net/fr/aspose.cells/row) à l'index de ligne de cellule spécifié.|
| [`check_cell(self, row, column)`](/cells/python-net/fr/aspose.cells/cells/check_cell/#int-int) | Obtient l'élément [`Cell`](/cells/python-net/fr/aspose.cells/cell) ou null à l'index de ligne de cellule et à l'index de colonne spécifiés.|
| [`check_row(self, row)`](/cells/python-net/fr/aspose.cells/cells/check_row/#int) | Obtient l'élément [`Row`](/cells/python-net/fr/aspose.cells/row) ou null à l'index de ligne de cellule spécifié.|
| [`check_column(self, column_index)`](/cells/python-net/fr/aspose.cells/cells/check_column/#int) | Obtient l'élément [`Column`](/cells/python-net/fr/aspose.cells/column) ou null à l'index de colonne spécifié.|
| [`is_row_hidden(self, row_index)`](/cells/python-net/fr/aspose.cells/cells/is_row_hidden/#int) | Vérifie si une ligne à l'index donné est masquée.|
| [`is_column_hidden(self, column_index)`](/cells/python-net/fr/aspose.cells/cells/is_column_hidden/#int) | Vérifie si une colonne à l'index donné est masquée.|
| [`add_range(self, range_object)`](/cells/python-net/fr/aspose.cells/cells/add_range/#aspose.cells.range) | Ajoute une référence d'objet de plage aux cellules|
| [`clear(self)`](/cells/python-net/fr/aspose.cells/cells/clear/#) | Efface toutes les données de la feuille de calcul.|
| [`import_array_list(self, array_list, first_row, first_column, is_vertical)`](/cells/python-net/fr/aspose.cells/cells/import_array_list/#list-int-int-bool) | Importe une liste de données dans une feuille de calcul.|
| [`import_formula_array(self, string_array, first_row, first_column, is_vertical)`](/cells/python-net/fr/aspose.cells/cells/import_formula_array/#list-int-int-bool) | Importe un tableau de formules dans une feuille de calcul.|
| [`text_to_columns(self, row, column, total_rows, options)`](/cells/python-net/fr/aspose.cells/cells/text_to_columns/#int-int-int-aspose.cells.txtloadoptions) | Divise le contenu de la colonne spécifiée en plusieurs colonnes.|
| [`un_merge(self, first_row, first_column, total_rows, total_columns)`](/cells/python-net/fr/aspose.cells/cells/un_merge/#int-int-int-int) | Annule la fusion d'une plage spécifiée de cellules fusionnées.|
| [`clear_merged_cells(self)`](/cells/python-net/fr/aspose.cells/cells/clear_merged_cells/#) | Efface toutes les plages fusionnées.|
| [`hide_row(self, row)`](/cells/python-net/fr/aspose.cells/cells/hide_row/#int) |Masque une ligne.|
| [`unhide_row(self, row, height)`](/cells/python-net/fr/aspose.cells/cells/unhide_row/#int-float) | Affiche une ligne.|
| [`hide_rows(self, row, total_rows)`](/cells/python-net/fr/aspose.cells/cells/hide_rows/#int-int) | Masque plusieurs lignes.|
| [`unhide_rows(self, row, total_rows, height)`](/cells/python-net/fr/aspose.cells/cells/unhide_rows/#int-int-float) | Affiche les lignes masquées.|
| [`set_row_height_pixel(self, row, pixels)`](/cells/python-net/fr/aspose.cells/cells/set_row_height_pixel/#int-int) | Définit la hauteur de la ligne en unités de pixels.|
| [`set_row_height_inch(self, row, inches)`](/cells/python-net/fr/aspose.cells/cells/set_row_height_inch/#int-float) | Définit la hauteur de la ligne en pouces.|
| [`set_row_height(self, row, height)`](/cells/python-net/fr/aspose.cells/cells/set_row_height/#int-float) | Définit la hauteur de la ligne spécifiée.|
| [`get_row_original_height_point(self, row)`](/cells/python-net/fr/aspose.cells/cells/get_row_original_height_point/#int) | Obtient la hauteur de la ligne d'origine en unité de point si la ligne est masquée|
| [`get_column_original_width_point(self, column)`](/cells/python-net/fr/aspose.cells/cells/get_column_original_width_point/#int) | Obtient la hauteur de la colonne d'origine en unité de point si la colonne est masquée|
| [`hide_column(self, column)`](/cells/python-net/fr/aspose.cells/cells/hide_column/#int) | Masque une colonne.|
| [`unhide_column(self, column, width)`](/cells/python-net/fr/aspose.cells/cells/unhide_column/#int-float) | Affiche une colonne|
| [`hide_columns(self, column, total_columns)`](/cells/python-net/fr/aspose.cells/cells/hide_columns/#int-int) | Masquer plusieurs colonnes.|
| [`unhide_columns(self, column, total_columns, width)`](/cells/python-net/fr/aspose.cells/cells/unhide_columns/#int-int-float) | Afficher plusieurs colonnes.|
| [`get_view_row_height(self, row)`](/cells/python-net/fr/aspose.cells/cells/get_view_row_height/#int) | Obtient la hauteur d'une ligne spécifiée.|
| [`get_row_height_inch(self, row)`](/cells/python-net/fr/aspose.cells/cells/get_row_height_inch/#int) | Obtient la hauteur d'une ligne spécifiée en pouces.|
| [`get_view_row_height_inch(self, row)`](/cells/python-net/fr/aspose.cells/cells/get_view_row_height_inch/#int) | Obtient la hauteur d'une ligne spécifiée en pouces.|
| [`get_row_height_pixel(self, row)`](/cells/python-net/fr/aspose.cells/cells/get_row_height_pixel/#int) | Obtient la hauteur d'une ligne spécifiée en unité de pixel.|
| [`set_column_width_pixel(self, column, pixels)`](/cells/python-net/fr/aspose.cells/cells/set_column_width_pixel/#int-int) | Définit la largeur de la colonne en unités de pixels en vue normale.|
| [`set_column_width_inch(self, column, inches)`](/cells/python-net/fr/aspose.cells/cells/set_column_width_inch/#int-float) | Définit la largeur de la colonne en pouces en vue normale.|
| [`set_column_width(self, column, width)`](/cells/python-net/fr/aspose.cells/cells/set_column_width/#int-float) | Définit la largeur de la colonne spécifiée en vue normale.|
| [`get_column_width_inch(self, column)`](/cells/python-net/fr/aspose.cells/cells/get_column_width_inch/#int) | Obtient la largeur de la colonne spécifiée en vue normale, en unités de pouces.|
| [`get_view_column_width_pixel(self, column)`](/cells/python-net/fr/aspose.cells/cells/get_view_column_width_pixel/#int) | Obtenez la largeur dans différents types de vue.|
| [`set_view_column_width_pixel(self, column, pixels)`](/cells/python-net/fr/aspose.cells/cells/set_view_column_width_pixel/#int-int) |Définit la largeur de la colonne dans différentes vues.|
| [`get_last_data_row(self, column)`](/cells/python-net/fr/aspose.cells/cells/get_last_data_row/#int) | Obtient le dernier index de ligne de la cellule qui contient des données dans la colonne spécifiée.|
| [`get_first_data_row(self, column)`](/cells/python-net/fr/aspose.cells/cells/get_first_data_row/#int) | Obtient l'index de la première ligne de la cellule qui contient les données dans la colonne spécifiée.|
| [`apply_column_style(self, column, style, flag)`](/cells/python-net/fr/aspose.cells/cells/apply_column_style/#int-aspose.cells.style-aspose.cells.styleflag) | Applique des formats pour une colonne entière.|
| [`apply_row_style(self, row, style, flag)`](/cells/python-net/fr/aspose.cells/cells/apply_row_style/#int-aspose.cells.style-aspose.cells.styleflag) | Applique les formats pour une ligne entière.|
| [`apply_style(self, style, flag)`](/cells/python-net/fr/aspose.cells/cells/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Applique des formats pour une feuille de calcul entière.|
| [`copy_column(self, source_cells, source_column_index, destination_column_index)`](/cells/python-net/fr/aspose.cells/cells/copy_column/#aspose.cells.cells-int-int) | Copie les données et les formats d'une colonne entière.|
| [`copy_row(self, source_cells, source_row_index, destination_row_index)`](/cells/python-net/fr/aspose.cells/cells/copy_row/#aspose.cells.cells-int-int) | Copie les données et les formats d'une ligne entière.|
| [`get_grouped_row_outline_level(self, row_index)`](/cells/python-net/fr/aspose.cells/cells/get_grouped_row_outline_level/#int) | Obtient le niveau de contour (à partir de zéro) de la ligne.|
| [`get_grouped_column_outline_level(self, column_index)`](/cells/python-net/fr/aspose.cells/cells/get_grouped_column_outline_level/#int) | Obtient le niveau de contour (à partir de zéro) de la colonne.|
| [`get_max_grouped_column_outline_level(self)`](/cells/python-net/fr/aspose.cells/cells/get_max_grouped_column_outline_level/#) | Obtient le niveau de contour de colonne groupée maximal (à partir de zéro).|
| [`get_max_grouped_row_outline_level(self)`](/cells/python-net/fr/aspose.cells/cells/get_max_grouped_row_outline_level/#) | Obtient le niveau de contour de ligne groupée maximal (à partir de zéro).|
| [`show_group_detail(self, is_vertical, index)`](/cells/python-net/fr/aspose.cells/cells/show_group_detail/#bool-int) | Développe les lignes/colonnes groupées.|
| [`hide_group_detail(self, is_vertical, index)`](/cells/python-net/fr/aspose.cells/cells/hide_group_detail/#bool-int) | Réduit les lignes/colonnes groupées.|
| [`ungroup_columns(self, first_index, last_index)`](/cells/python-net/fr/aspose.cells/cells/ungroup_columns/#int-int) | Dissocie les colonnes.|
| [`is_deleting_range_enabled(self, start_row, start_column, total_rows, total_columns)`](/cells/python-net/fr/aspose.cells/cells/is_deleting_range_enabled/#int-int-int-int) | Vérifiez si la plage peut être supprimée.|
| [`is_blank_column(self, column_index)`](/cells/python-net/fr/aspose.cells/cells/is_blank_column/#int) | Vérifie si la colonne donnée est vide (ne contient aucune donnée).|
| [`insert_row(self, row_index)`](/cells/python-net/fr/aspose.cells/cells/insert_row/#int) | Insère une nouvelle ligne dans la feuille de calcul.|
| [`link_to_xml_map(self, map_name, row, column, path)`](/cells/python-net/fr/aspose.cells/cells/link_to_xml_map/#str-int-int-str) | Lien vers une carte xml.|
| [`move_range(self, source_area, dest_row, dest_column)`](/cells/python-net/fr/aspose.cells/cells/move_range/#aspose.cells.cellarea-int-int) | Déplace la gamme.|
| [`insert_cut_cells(self, cut_range, row, column, shift_type)`](/cells/python-net/fr/aspose.cells/cells/insert_cut_cells/#aspose.cells.range-int-int-aspose.cells.shifttype) | Insérer la plage de coupe.|
| [`delete_range(self, start_row, start_column, end_row, end_column, shift_type)`](/cells/python-net/fr/aspose.cells/cells/delete_range/#int-int-int-int-aspose.cells.shifttype) |Supprime une plage de cellules et décale les cellules en fonction de l'option de décalage.|
| [`retrieve_subtotal_setting(self, ca)`](/cells/python-net/fr/aspose.cells/cells/retrieve_subtotal_setting/#aspose.cells.cellarea) | Récupère le paramètre des sous-totaux de la plage.|
| [`remove_formulas(self)`](/cells/python-net/fr/aspose.cells/cells/remove_formulas/#) | Supprime toutes les formules et les remplace par la valeur de la formule.|
| [`convert_string_to_numeric_value(self)`](/cells/python-net/fr/aspose.cells/cells/convert_string_to_numeric_value/#) | Convertit toutes les données de chaîne de la feuille de calcul en valeur numérique si possible.|
| [`get_dependents(self, is_all, row, column)`](/cells/python-net/fr/aspose.cells/cells/get_dependents/#bool-int-int) | Obtenez toutes les cellules qui font référence à la cellule spécifique.|
| [`get_dependents_in_calculation(self, row, column, recursive)`](/cells/python-net/fr/aspose.cells/cells/get_dependents_in_calculation/#int-int-bool) | Obtient toutes les cellules dont le résultat calculé dépend d'une cellule spécifique.|
| [`get_cells_with_place_in_cell_picture(self)`](/cells/python-net/fr/aspose.cells/cells/get_cells_with_place_in_cell_picture/#) | Obtient toutes les cellules qui contiennent une image intégrée.|
| [`get_cell_style(self, row, column)`](/cells/python-net/fr/aspose.cells/cells/get_cell_style/#int-int) | Obtenir le style de la cellule donnée.|



###  Remarques



###  Voir également
* module [`aspose.cells`](..)
* classe [`Cell`](/cells/python-net/fr/aspose.cells/cell)
* classe [`Column`](/cells/python-net/fr/aspose.cells/column)
* classe [`Range`](/cells/python-net/fr/aspose.cells/range)
* classe [`Row`](/cells/python-net/fr/aspose.cells/row)
