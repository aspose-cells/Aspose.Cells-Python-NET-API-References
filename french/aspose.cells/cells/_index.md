---
title: Cells classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 180
url: /fr/aspose.cells/cells/
is_root: false
---
##  Cells classe
Encapsule une collection d'objets pertinents pour les cellules, tels que [Cell](/cells/python-net/fr/aspose.cells/cell), [Row](/cells/python-net/fr/aspose.cells/row), ... etc.



Le type Cells expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [ods_cell_fields](/cells/python-net/fr/aspose.cells/cells/ods_cell_fields) | Obtient la liste des champs de ods.|
| [count](/cells/python-net/fr/aspose.cells/cells/count) | Obtient le nombre total d'objets Cell instanciés.|
| [count_large](/cells/python-net/fr/aspose.cells/cells/count_large) | Obtient le nombre total d'objets Cell instanciés.|
| [rows](/cells/python-net/fr/aspose.cells/cells/rows) | Obtient la collection d'objets [Row](/cells/python-net/fr/aspose.cells/row) qui représente les lignes individuelles de cette feuille de calcul.|
| [merged_cells](/cells/python-net/fr/aspose.cells/cells/merged_cells) | Obtient la collection de cellules fusionnées.|
| [multi_thread_reading](/cells/python-net/fr/aspose.cells/cells/multi_thread_reading) | Obtient ou définit si le modèle de données des cellules doit prendre en charge la lecture multithread.<br/> La valeur par défaut de cette propriété est false.|
| [memory_setting](/cells/python-net/fr/aspose.cells/cells/memory_setting) | Obtient ou définit l'option d'utilisation de la mémoire pour ces cellules.|
| [style](/cells/python-net/fr/aspose.cells/cells/style) | Obtient et définit le style par défaut.|
| [standard_width_inch](/cells/python-net/fr/aspose.cells/cells/standard_width_inch) |Obtient ou définit la largeur de colonne par défaut dans la feuille de calcul, en pouces.|
| [standard_width_pixels](/cells/python-net/fr/aspose.cells/cells/standard_width_pixels) | Obtient ou définit la largeur de colonne par défaut dans la feuille de calcul, en pixels.|
| [standard_width](/cells/python-net/fr/aspose.cells/cells/standard_width) | Obtient ou définit la largeur de colonne par défaut dans la feuille de calcul, en unités de caractères.|
| [standard_height](/cells/python-net/fr/aspose.cells/cells/standard_height) | Obtient ou définit la hauteur de ligne par défaut dans cette feuille de calcul, en unités de points.|
| [standard_height_pixels](/cells/python-net/fr/aspose.cells/cells/standard_height_pixels) | Obtient ou définit la hauteur de ligne par défaut dans cette feuille de calcul, en pixels.|
| [standard_height_inch](/cells/python-net/fr/aspose.cells/cells/standard_height_inch) | Obtient ou définit la hauteur de ligne par défaut dans cette feuille de calcul, en pouces.|
| [preserve_string](/cells/python-net/fr/aspose.cells/cells/preserve_string) | Obtient ou définit une valeur indiquant si toutes les valeurs de la feuille de calcul sont conservées sous forme de chaînes.<br/> La valeur par défaut est false.|
| [min_row](/cells/python-net/fr/aspose.cells/cells/min_row) | Index de ligne minimal de la cellule contenant des données ou un style.|
| [max_row](/cells/python-net/fr/aspose.cells/cells/max_row) | Index de ligne maximal de la cellule contenant des données ou un style.|
| [min_column](/cells/python-net/fr/aspose.cells/cells/min_column) | Index de colonne minimum des cellules qui ont été instanciées dans la collection (n'inclut pas la colonne<br/> où le style est défini pour toute la colonne mais aucune cellule n'y a été instanciée).|
| [max_column](/cells/python-net/fr/aspose.cells/cells/max_column) | Index de colonne minimum des cellules qui ont été instanciées dans la collection (n'inclut pas la colonne<br/> où le style est défini pour toute la colonne mais aucune cellule n'y a été instanciée).|
| [min_data_row](/cells/python-net/fr/aspose.cells/cells/min_data_row) | Index de ligne minimal de la cellule contenant des données.|
| [max_data_row](/cells/python-net/fr/aspose.cells/cells/max_data_row) |Index de ligne maximal de la cellule contenant des données.|
| [min_data_column](/cells/python-net/fr/aspose.cells/cells/min_data_column) | Index de colonne minimal de la cellule contenant des données.|
| [max_data_column](/cells/python-net/fr/aspose.cells/cells/max_data_column) | Index de colonne maximum de la cellule qui contient des données.|
| [is_default_row_height_matched](/cells/python-net/fr/aspose.cells/cells/is_default_row_height_matched) | Indique que la hauteur de ligne et la hauteur de police par défaut correspondent|
| [is_default_row_hidden](/cells/python-net/fr/aspose.cells/cells/is_default_row_hidden) | Indique si la ligne est masquée par défaut.|
| [columns](/cells/python-net/fr/aspose.cells/cells/columns) | Obtient la collection d'objets [Column](/cells/python-net/fr/aspose.cells/column) qui représente les colonnes individuelles de cette feuille de calcul.|
| [ranges](/cells/python-net/fr/aspose.cells/cells/ranges) | Obtient la collection d'objets [Range](/cells/python-net/fr/aspose.cells/range) créés au moment de l'exécution.|
| [last_cell](/cells/python-net/fr/aspose.cells/cells/last_cell) | Obtient la dernière cellule de cette feuille de calcul.|
| [max_display_range](/cells/python-net/fr/aspose.cells/cells/max_display_range) | Obtient la plage maximale qui inclut les données, les cellules fusionnées et les formes.|
| [first_cell](/cells/python-net/fr/aspose.cells/cells/first_cell) | Obtient la première cellule de cette feuille de calcul.|



Obtient l'élément [Cell](/cells/python-net/fr/aspose.cells/cell) dans la feuille de calcul
###  Indexeur
| Nom| Description|
| :- | :- |
| [index] | Index de base zéro de l'élément.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [create_range(upper_left_cell, lower_right_cell)](/cells/python-net/fr/aspose.cells/cells/create_range/#str-str) | Crée un objet [Range](/cells/python-net/fr/aspose.cells/range) à partir d'une plage de cellules.|
| [create_range(first_row, first_column, total_rows, total_columns)](/cells/python-net/fr/aspose.cells/cells/create_range/#int-int-int-int) | Crée un objet [Range](/cells/python-net/fr/aspose.cells/range) à partir d'une plage de cellules.|
| [create_range(address)](/cells/python-net/fr/aspose.cells/cells/create_range/#str) | Crée un objet [Range](/cells/python-net/fr/aspose.cells/range) à partir d'une adresse de la plage.|
| [create_range(first_index, number, is_vertical)](/cells/python-net/fr/aspose.cells/cells/create_range/#int-int-bool) | Crée un objet [Range](/cells/python-net/fr/aspose.cells/range) à partir de rangées de cellules ou de colonnes de cellules.|
| [get(row, column)](/cells/python-net/fr/aspose.cells/cells/get/#int-int) |Ajouter API for Python Via .Net.puisque ceci [ligne int, colonne int] n'est pas pris en charge|
| [get(cell_name)](/cells/python-net/fr/aspose.cells/cells/get/#str) | Ajouter API for Python Via .Net.puisque cette [string cellName] n'est pas prise en charge|
| [import_object_array(obj_array, first_row, first_column, is_vertical)](/cells/python-net/fr/aspose.cells/cells/import_object_array/#list-int-int-bool) | Importe un tableau de données dans une feuille de calcul.|
| [import_object_array(obj_array, first_row, first_column, is_vertical, skip)](/cells/python-net/fr/aspose.cells/cells/import_object_array/#list-int-int-bool-int) | Importe un tableau de données dans une feuille de calcul.|
| [import_array(string_array, first_row, first_column, is_vertical)](/cells/python-net/fr/aspose.cells/cells/import_array/#list-int-int-bool) | Importe un tableau de chaînes dans une feuille de calcul.|
| [import_array(int_array, first_row, first_column, is_vertical)](/cells/python-net/fr/aspose.cells/cells/import_array/#list-int-int-bool) | Importe un tableau d'entiers dans une feuille de calcul.|
| [import_array(double_array, first_row, first_column, is_vertical)](/cells/python-net/fr/aspose.cells/cells/import_array/#list-int-int-bool) | Importe un tableau de doubles dans une feuille de calcul.|
| [import_csv(file_name, splitter, convert_numeric_data, first_row, first_column)](/cells/python-net/fr/aspose.cells/cells/import_csv/#str-str-bool-int-int) | Importez un fichier CSV dans les cellules.|
| [import_csv(stream, splitter, convert_numeric_data, first_row, first_column)](/cells/python-net/fr/aspose.cells/cells/import_csv/#io.RawIOBase-str-bool-int-int) | Importez un fichier CSV dans les cellules.|
| [import_csv(file_name, options, first_row, first_column)](/cells/python-net/fr/aspose.cells/cells/import_csv/#str-TxtLoadOptions-int-int) | Importez un fichier CSV dans les cellules.|
| [import_csv(stream, options, first_row, first_column)](/cells/python-net/fr/aspose.cells/cells/import_csv/#io.RawIOBase-TxtLoadOptions-int-int) | Importez un fichier CSV dans les cellules.|
| [merge(first_row, first_column, total_rows, total_columns)](/cells/python-net/fr/aspose.cells/cells/merge/#int-int-int-int) | Fusionne une plage de cellules spécifiée en une seule cellule.|
| [merge(first_row, first_column, total_rows, total_columns, merge_conflict)](/cells/python-net/fr/aspose.cells/cells/merge/#int-int-int-int-bool) | Fusionne une plage de cellules spécifiée en une seule cellule.|
| [merge(first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict)](/cells/python-net/fr/aspose.cells/cells/merge/#int-int-int-int-bool-bool) | Fusionne une plage de cellules spécifiée en une seule cellule.|
| [copy_columns(source_cells0, source_column_index, destination_column_index, column_number, paste_options)](/cells/python-net/fr/aspose.cells/cells/copy_columns/#Cells-int-int-int-PasteOptions) | Copie les données et les formats d'une colonne entière.|
| [copy_columns(source_cells0, source_column_index, destination_column_index, column_number)](/cells/python-net/fr/aspose.cells/cells/copy_columns/#Cells-int-int-int) | Copie les données et les formats d'une colonne entière.|
| [copy_columns(source_cells, source_column_index, source_total_columns, destination_column_index, destination_total_columns)](/cells/python-net/fr/aspose.cells/cells/copy_columns/#Cells-int-int-int-int) | Copie les données et les formats de toutes les colonnes.|
| [copy_rows(source_cells, source_row_index, destination_row_index, row_number)](/cells/python-net/fr/aspose.cells/cells/copy_rows/#Cells-int-int-int) | Copie les données et les formats de certaines lignes entières.|
| [copy_rows(source_cells0, source_row_index, destination_row_index, row_number, copy_options)](/cells/python-net/fr/aspose.cells/cells/copy_rows/#Cells-int-int-int-CopyOptions) | Copie les données et les formats de certaines lignes entières.|
| [copy_rows(source_cells0, source_row_index, destination_row_index, row_number, copy_options, paste_options)](/cells/python-net/fr/aspose.cells/cells/copy_rows/#Cells-int-int-int-CopyOptions-PasteOptions) | Copie les données et les formats de certaines lignes entières.|
| [group_columns(first_index, last_index)](/cells/python-net/fr/aspose.cells/cells/group_columns/#int-int) | Regroupe les colonnes.|
| [group_columns(first_index, last_index, is_hidden)](/cells/python-net/fr/aspose.cells/cells/group_columns/#int-int-bool) | Regroupe les colonnes.|
| [ungroup_rows(first_index, last_index, is_all)](/cells/python-net/fr/aspose.cells/cells/ungroup_rows/#int-int-bool) | Dissocie les lignes.|
| [ungroup_rows(first_index, last_index)](/cells/python-net/fr/aspose.cells/cells/ungroup_rows/#int-int) | Dissocie les lignes.|
| [group_rows(first_index, last_index, is_hidden)](/cells/python-net/fr/aspose.cells/cells/group_rows/#int-int-bool) | Regroupe les rangées.|
| [group_rows(first_index, last_index)](/cells/python-net/fr/aspose.cells/cells/group_rows/#int-int) | Regroupe les rangées.|
| [delete_column(column_index, update_reference)](/cells/python-net/fr/aspose.cells/cells/delete_column/#int-bool) | Supprime une colonne.|
| [delete_column(column_index)](/cells/python-net/fr/aspose.cells/cells/delete_column/#int) | Supprime une colonne.|
| [delete_rows(row_index, total_rows)](/cells/python-net/fr/aspose.cells/cells/delete_rows/#int-int) | Supprime plusieurs lignes.|
| [delete_rows(row_index, total_rows, update_reference)](/cells/python-net/fr/aspose.cells/cells/delete_rows/#int-int-bool) | Supprime plusieurs lignes dans la feuille de calcul.|
| [delete_blank_columns()](/cells/python-net/fr/aspose.cells/cells/delete_blank_columns/#) | Supprimez toutes les colonnes vides qui ne contiennent aucune donnée.|
| [delete_blank_columns(options)](/cells/python-net/fr/aspose.cells/cells/delete_blank_columns/#DeleteOptions) | Supprimez toutes les colonnes vides qui ne contiennent aucune donnée.|
| [delete_blank_rows()](/cells/python-net/fr/aspose.cells/cells/delete_blank_rows/#) | Supprimez toutes les lignes vides qui ne contiennent aucune donnée.|
| [delete_blank_rows(options)](/cells/python-net/fr/aspose.cells/cells/delete_blank_rows/#DeleteOptions) | Supprimez toutes les lignes vides qui ne contiennent aucune donnée.|
| [insert_columns(column_index, total_columns)](/cells/python-net/fr/aspose.cells/cells/insert_columns/#int-int) | Insère des colonnes dans la feuille de calcul.|
| [insert_columns(column_index, total_columns, update_reference)](/cells/python-net/fr/aspose.cells/cells/insert_columns/#int-int-bool) | Insère des colonnes dans la feuille de calcul.|
| [insert_column(column_index, update_reference)](/cells/python-net/fr/aspose.cells/cells/insert_column/#int-bool) |Insère une nouvelle colonne dans la feuille de calcul.|
| [insert_column(column_index)](/cells/python-net/fr/aspose.cells/cells/insert_column/#int) |Insère une nouvelle colonne dans la feuille de calcul.|
| [insert_rows(row_index, total_rows, update_reference)](/cells/python-net/fr/aspose.cells/cells/insert_rows/#int-int-bool) | Insère plusieurs lignes dans la feuille de calcul.|
| [insert_rows(row_index, total_rows, options)](/cells/python-net/fr/aspose.cells/cells/insert_rows/#int-int-InsertOptions) | Insère plusieurs lignes dans la feuille de calcul.|
| [insert_rows(row_index, total_rows)](/cells/python-net/fr/aspose.cells/cells/insert_rows/#int-int) | Insère plusieurs lignes dans la feuille de calcul.|
| [clear_range(range)](/cells/python-net/fr/aspose.cells/cells/clear_range/#CellArea) | Efface le contenu et la mise en forme d'une plage.|
| [clear_range(start_row, start_column, end_row, end_column)](/cells/python-net/fr/aspose.cells/cells/clear_range/#int-int-int-int) | Efface le contenu et la mise en forme d'une plage.|
| [clear_contents(range)](/cells/python-net/fr/aspose.cells/cells/clear_contents/#CellArea) | Efface le contenu d'une plage.|
| [clear_contents(start_row, start_column, end_row, end_column)](/cells/python-net/fr/aspose.cells/cells/clear_contents/#int-int-int-int) | Efface le contenu d'une plage.|
| [clear_formats(range)](/cells/python-net/fr/aspose.cells/cells/clear_formats/#CellArea) | Efface la mise en forme d'une plage.|
| [clear_formats(start_row, start_column, end_row, end_column)](/cells/python-net/fr/aspose.cells/cells/clear_formats/#int-int-int-int) | Efface la mise en forme d'une plage.|
| [find(what, previous_cell)](/cells/python-net/fr/aspose.cells/cells/find/#any-Cell) | Recherche la cellule contenant l'objet d'entrée.|
| [find(what, previous_cell, find_options)](/cells/python-net/fr/aspose.cells/cells/find/#any-Cell-FindOptions) | Recherche la cellule contenant l'objet d'entrée.|
| [end_cell_in_row(row_index)](/cells/python-net/fr/aspose.cells/cells/end_cell_in_row/#int) | Obtient la dernière cellule de cette ligne.|
| [end_cell_in_row(start_row, end_row, start_column, end_column)](/cells/python-net/fr/aspose.cells/cells/end_cell_in_row/#int-int-int-int) | Obtient la dernière cellule avec l'index de ligne maximal dans cette plage.|
| [end_cell_in_column(column_index)](/cells/python-net/fr/aspose.cells/cells/end_cell_in_column/#int) | Obtient la dernière cellule de cette colonne.|
| [end_cell_in_column(start_row, end_row, start_column, end_column)](/cells/python-net/fr/aspose.cells/cells/end_cell_in_column/#int-int-int-int) | Obtient la dernière cellule avec l'index de colonne maximal dans cette plage.|
| [insert_range(area, shift_number, shift_type, update_reference)](/cells/python-net/fr/aspose.cells/cells/insert_range/#CellArea-int-ShiftType-bool) | Insère une plage de cellules et décale les cellules en fonction de l'option de décalage.|
| [insert_range(area, shift_type)](/cells/python-net/fr/aspose.cells/cells/insert_range/#CellArea-ShiftType) | Insère une plage de cellules et décale les cellules en fonction de l'option de décalage.|
| [insert_range(area, shift_number, shift_type)](/cells/python-net/fr/aspose.cells/cells/insert_range/#CellArea-int-ShiftType) | Insère une plage de cellules et décale les cellules en fonction de l'option de décalage.|
| [import_custom_objects(list, property_names, is_property_name_shown, first_row, first_column, row_number, insert_rows, date_format_string, convert_string_to_number)](/cells/python-net/fr/aspose.cells/cells/import_custom_objects/#list-list-bool-int-int-int-bool-str-bool) | Importe des objets personnalisés.|
| [import_custom_objects(list, first_row, first_column, options)](/cells/python-net/fr/aspose.cells/cells/import_custom_objects/#list-int-int-ImportTableOptions) | Importe des objets personnalisés.|
| [subtotal(ca, group_by, function, total_list)](/cells/python-net/fr/aspose.cells/cells/subtotal/#CellArea-int-ConsolidationFunction-list) | Crée des sous-totaux pour la plage.|
| [subtotal(ca, group_by, function, total_list, replace, page_breaks, summary_below_data)](/cells/python-net/fr/aspose.cells/cells/subtotal/#CellArea-int-ConsolidationFunction-list-bool-bool-bool) | Crée des sous-totaux pour la plage.|
| [remove_duplicates()](/cells/python-net/fr/aspose.cells/cells/remove_duplicates/#) | Supprime les lignes en double dans la feuille.|
| [remove_duplicates(start_row, start_column, end_row, end_column)](/cells/python-net/fr/aspose.cells/cells/remove_duplicates/#int-int-int-int) | Supprime les valeurs en double dans la plage.|
| [remove_duplicates(start_row, start_column, end_row, end_column, has_headers, column_offsets)](/cells/python-net/fr/aspose.cells/cells/remove_duplicates/#int-int-int-int-bool-list) | Supprime les données en double de la plage.|
| [get_row_enumerator()](/cells/python-net/fr/aspose.cells/cells/get_row_enumerator/#) | Obtient l'énumérateur de lignes.|
| [get_cell(row, column)](/cells/python-net/fr/aspose.cells/cells/get_cell/#int-int) | Obtient l'élément [Cell](/cells/python-net/fr/aspose.cells/cell) ou null à l'index de ligne de cellule et à l'index de colonne spécifiés.|
| [get_row(row)](/cells/python-net/fr/aspose.cells/cells/get_row/#int) | Obtient l'élément [Row](/cells/python-net/fr/aspose.cells/row) à l'index de ligne de cellule spécifié.|
| [check_cell(row, column)](/cells/python-net/fr/aspose.cells/cells/check_cell/#int-int) | Obtient l'élément [Cell](/cells/python-net/fr/aspose.cells/cell) ou null à l'index de ligne de cellule et à l'index de colonne spécifiés.|
| [check_row(row)](/cells/python-net/fr/aspose.cells/cells/check_row/#int) |Obtient l'élément [Row](/cells/python-net/fr/aspose.cells/row) ou à l'index de ligne de cellule spécifié.|
| [check_column(column_index)](/cells/python-net/fr/aspose.cells/cells/check_column/#int) | Obtient l'élément [Column](/cells/python-net/fr/aspose.cells/column) ou null à l'index de colonne spécifié.|
| [is_row_hidden(row_index)](/cells/python-net/fr/aspose.cells/cells/is_row_hidden/#int) | Vérifie si une ligne à un index donné est masquée.|
| [is_column_hidden(column_index)](/cells/python-net/fr/aspose.cells/cells/is_column_hidden/#int) | Vérifie si une colonne à un index donné est masquée.|
| [add_range(range_object)](/cells/python-net/fr/aspose.cells/cells/add_range/#Range) | Ajoute une référence d'objet de plage aux cellules|
| [clear()](/cells/python-net/fr/aspose.cells/cells/clear/#) | Efface tous les objets de cellule et de ligne.|
| [import_data(table, first_row, first_column, options)](/cells/python-net/fr/aspose.cells/cells/import_data/#ICellsDataTable-int-int-ImportTableOptions) | Importer des données à partir d'une table de données personnalisée.|
| [import_array_list(array_list, first_row, first_column, is_vertical)](/cells/python-net/fr/aspose.cells/cells/import_array_list/#list-int-int-bool) | Importe une liste de tableaux de données dans une feuille de calcul.|
| [import_formula_array(string_array, first_row, first_column, is_vertical)](/cells/python-net/fr/aspose.cells/cells/import_formula_array/#list-int-int-bool) | Importe un tableau de formules dans une feuille de calcul.|
| [text_to_columns(row, column, total_rows, options)](/cells/python-net/fr/aspose.cells/cells/text_to_columns/#int-int-int-TxtLoadOptions) | Divise le texte de la colonne en colonnes.|
| [un_merge(first_row, first_column, total_rows, total_columns)](/cells/python-net/fr/aspose.cells/cells/un_merge/#int-int-int-int) | Annule la fusion d'une plage spécifiée de cellules fusionnées.|
| [clear_merged_cells()](/cells/python-net/fr/aspose.cells/cells/clear_merged_cells/#) | Efface toutes les plages fusionnées.|
| [hide_row(row)](/cells/python-net/fr/aspose.cells/cells/hide_row/#int) | Masque une ligne.|
| [unhide_row(row, height)](/cells/python-net/fr/aspose.cells/cells/unhide_row/#int-float) | Affiche une ligne.|
| [hide_rows(row, total_rows)](/cells/python-net/fr/aspose.cells/cells/hide_rows/#int-int) | Masque plusieurs lignes.|
| [unhide_rows(row, total_rows, height)](/cells/python-net/fr/aspose.cells/cells/unhide_rows/#int-int-float) | Affiche les lignes masquées.|
| [set_row_height_pixel(row, pixels)](/cells/python-net/fr/aspose.cells/cells/set_row_height_pixel/#int-int) | Définit la hauteur de la ligne en pixels.|
| [set_row_height_inch(row, inches)](/cells/python-net/fr/aspose.cells/cells/set_row_height_inch/#int-float) | Définit la hauteur de ligne en pouces.|
| [set_row_height(row, height)](/cells/python-net/fr/aspose.cells/cells/set_row_height/#int-float) | Définit la hauteur de la ligne spécifiée.|
| [get_row_original_height_point(row)](/cells/python-net/fr/aspose.cells/cells/get_row_original_height_point/#int) | Obtient la hauteur de la ligne d'origine en unité de point si la ligne est masquée|
| [hide_column(column)](/cells/python-net/fr/aspose.cells/cells/hide_column/#int) | Masque une colonne.|
| [unhide_column(column, width)](/cells/python-net/fr/aspose.cells/cells/unhide_column/#int-float) | Affiche une colonne|
| [hide_columns(column, total_columns)](/cells/python-net/fr/aspose.cells/cells/hide_columns/#int-int) | Masquez plusieurs colonnes.|
| [unhide_columns(column, total_columns, width)](/cells/python-net/fr/aspose.cells/cells/unhide_columns/#int-int-float) |Afficher plusieurs colonnes.|
| [get_row_height(row)](/cells/python-net/fr/aspose.cells/cells/get_row_height/#int) | Obtient la hauteur d'une ligne spécifiée.|
| [get_view_row_height(row)](/cells/python-net/fr/aspose.cells/cells/get_view_row_height/#int) | Obtient la hauteur d'une ligne spécifiée.|
| [get_row_height_pixel(row)](/cells/python-net/fr/aspose.cells/cells/get_row_height_pixel/#int) | Obtient la hauteur d'une ligne spécifiée en unité de pixel.|
| [get_row_height_inch(row)](/cells/python-net/fr/aspose.cells/cells/get_row_height_inch/#int) | Obtient la hauteur d'une ligne spécifiée en pouces.|
| [get_view_row_height_inch(row)](/cells/python-net/fr/aspose.cells/cells/get_view_row_height_inch/#int) | Obtient la hauteur d'une ligne spécifiée en pouces.|
| [set_column_width_pixel(column, pixels)](/cells/python-net/fr/aspose.cells/cells/set_column_width_pixel/#int-int) | Définit la largeur de colonne en unités de pixels en vue normale.|
| [set_column_width_inch(column, inches)](/cells/python-net/fr/aspose.cells/cells/set_column_width_inch/#int-float) | Définit la largeur de la colonne en pouces en vue normale.|
| [set_column_width(column, width)](/cells/python-net/fr/aspose.cells/cells/set_column_width/#int-float) | Définit la largeur de la colonne spécifiée en vue normale.|
| [get_column_width_pixel(column)](/cells/python-net/fr/aspose.cells/cells/get_column_width_pixel/#int) | Obtient la largeur de la colonne spécifiée en mode normal, en unités de pixel.|
| [get_column_width_inch(column)](/cells/python-net/fr/aspose.cells/cells/get_column_width_inch/#int) | Obtient la largeur de la colonne spécifiée en mode normal, en unités de pouces.|
| [get_column_width(column)](/cells/python-net/fr/aspose.cells/cells/get_column_width/#int) | Obtient la largeur de la colonne spécifiée en mode normal|
| [get_view_column_width_pixel(column)](/cells/python-net/fr/aspose.cells/cells/get_view_column_width_pixel/#int) | Obtenez la largeur dans différents types de vue.|
| [set_view_column_width_pixel(column, pixels)](/cells/python-net/fr/aspose.cells/cells/set_view_column_width_pixel/#int-int) | Définit la largeur de la colonne dans différentes vues.|
| [get_last_data_row(column)](/cells/python-net/fr/aspose.cells/cells/get_last_data_row/#int) | Obtient le dernier index de ligne de la cellule qui contient des données dans la colonne spécifiée.|
| [apply_column_style(column, style, flag)](/cells/python-net/fr/aspose.cells/cells/apply_column_style/#int-Style-StyleFlag) | Applique les formats pour une colonne entière.|
| [apply_row_style(row, style, flag)](/cells/python-net/fr/aspose.cells/cells/apply_row_style/#int-Style-StyleFlag) | Applique les formats pour une ligne entière.|
| [apply_style(style, flag)](/cells/python-net/fr/aspose.cells/cells/apply_style/#Style-StyleFlag) | Applique des formats pour une feuille de calcul entière.|
| [copy_column(source_cells, source_column_index, destination_column_index)](/cells/python-net/fr/aspose.cells/cells/copy_column/#Cells-int-int) | Copie les données et les formats d'une colonne entière.|
| [copy_row(source_cells, source_row_index, destination_row_index)](/cells/python-net/fr/aspose.cells/cells/copy_row/#Cells-int-int) | Copie les données et les formats d'une ligne entière.|
| [get_grouped_row_outline_level(row_index)](/cells/python-net/fr/aspose.cells/cells/get_grouped_row_outline_level/#int) |Obtient le niveau hiérarchique (de base zéro) de la ligne.|
| [get_grouped_column_outline_level(column_index)](/cells/python-net/fr/aspose.cells/cells/get_grouped_column_outline_level/#int) | Obtient le niveau hiérarchique (basé sur zéro) de la colonne.|
| [get_max_grouped_column_outline_level()](/cells/python-net/fr/aspose.cells/cells/get_max_grouped_column_outline_level/#) | Obtient le niveau hiérarchique maximal des colonnes groupées (base zéro).|
| [get_max_grouped_row_outline_level()](/cells/python-net/fr/aspose.cells/cells/get_max_grouped_row_outline_level/#) | Obtient le niveau hiérarchique maximum des lignes groupées (basé sur zéro).|
| [show_group_detail(is_vertical, index)](/cells/python-net/fr/aspose.cells/cells/show_group_detail/#bool-int) | Développe les lignes/colonnes groupées.|
| [hide_group_detail(is_vertical, index)](/cells/python-net/fr/aspose.cells/cells/hide_group_detail/#bool-int) | Réduit les lignes/colonnes groupées.|
| [ungroup_columns(first_index, last_index)](/cells/python-net/fr/aspose.cells/cells/ungroup_columns/#int-int) | Dissocie les colonnes.|
| [delete_columns(column_index, total_columns, update_reference)](/cells/python-net/fr/aspose.cells/cells/delete_columns/#int-int-bool) | Supprime plusieurs colonnes.|
| [is_deleting_range_enabled(start_row, start_column, total_rows, total_columns)](/cells/python-net/fr/aspose.cells/cells/is_deleting_range_enabled/#int-int-int-int) | Vérifiez si la plage peut être supprimée.|
| [delete_row(row_index)](/cells/python-net/fr/aspose.cells/cells/delete_row/#int) | Supprime une ligne.|
| [is_blank_column(column_index)](/cells/python-net/fr/aspose.cells/cells/is_blank_column/#int) | Vérifie si la colonne donnée est vide (ne contient aucune donnée).|
| [insert_row(row_index)](/cells/python-net/fr/aspose.cells/cells/insert_row/#int) | Insère une nouvelle ligne dans la feuille de calcul.|
| [link_to_xml_map(map_name, row, column, path)](/cells/python-net/fr/aspose.cells/cells/link_to_xml_map/#str-int-int-str) | Lien vers une carte xml.|
| [find_formula(formula, previous_cell)](/cells/python-net/fr/aspose.cells/cells/find_formula/#str-Cell) | Recherche la cellule avec la chaîne d'entrée.|
| [find_formula_contains(formula, previous_cell)](/cells/python-net/fr/aspose.cells/cells/find_formula_contains/#str-Cell) | Recherche la cellule avec la formule qui contient la chaîne d'entrée.|
| [move_range(source_area, dest_row, dest_column)](/cells/python-net/fr/aspose.cells/cells/move_range/#CellArea-int-int) | Déplace la plage.|
| [insert_cut_cells(cut_range, row, column, shift_type)](/cells/python-net/fr/aspose.cells/cells/insert_cut_cells/#Range-int-int-ShiftType) | Insérer la plage de coupe.|
| [delete_range(start_row, start_column, end_row, end_column, shift_type)](/cells/python-net/fr/aspose.cells/cells/delete_range/#int-int-int-int-ShiftType) | Supprime une plage de cellules et décale les cellules en fonction de l'option de décalage.|
| [retrieve_subtotal_setting(ca)](/cells/python-net/fr/aspose.cells/cells/retrieve_subtotal_setting/#CellArea) | Récupère le réglage des sous-totaux de la plage.|
| [remove_formulas()](/cells/python-net/fr/aspose.cells/cells/remove_formulas/#) | Supprime toutes les formules et les remplace par la valeur de la formule.|
| [convert_string_to_numeric_value()](/cells/python-net/fr/aspose.cells/cells/convert_string_to_numeric_value/#) |Convertit les données de chaîne dans les cellules en valeur numérique si possible.|
| [get_dependents(is_all, row, column)](/cells/python-net/fr/aspose.cells/cells/get_dependents/#bool-int-int) | Obtenez toutes les cellules qui font référence à la cellule spécifique.|
| [get_dependents_in_calculation(row, column, recursive)](/cells/python-net/fr/aspose.cells/cells/get_dependents_in_calculation/#int-int-bool) | Obtient toutes les cellules dont le résultat calculé dépend d'une cellule spécifique.|
| [get_cell_style(row, column)](/cells/python-net/fr/aspose.cells/cells/get_cell_style/#int-int) | Récupère le style d'une cellule donnée.|



###  Voir également
* module [aspose.cells](..)
* classe [Cell](/cells/python-net/fr/aspose.cells/cell)
* classe [Column](/cells/python-net/fr/aspose.cells/column)
* classe [Range](/cells/python-net/fr/aspose.cells/range)
* classe [Row](/cells/python-net/fr/aspose.cells/row)
