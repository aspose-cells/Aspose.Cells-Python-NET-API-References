---
title: CellsHelper classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 240
url: /fr/aspose.cells/cellshelper/
is_root: false
---
##  CellsHelper classe
Fournit des fonctions d’assistance.



Le type CellsHelper expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [significant_digits](/cells/python-net/fr/aspose.cells/cellshelper/significant_digits) | Obtient et définit le nombre de chiffres significatifs.<br/> La valeur par défaut est 17.|
| [dpi](/cells/python-net/fr/aspose.cells/cellshelper/dpi) | Obtient le DPI de la machine.|
| [startup_path](/cells/python-net/fr/aspose.cells/cellshelper/startup_path) | Obtient ou définit le chemin de démarrage, auquel font référence certaines références de formule externes.|
| [alt_start_path](/cells/python-net/fr/aspose.cells/cellshelper/alt_start_path) | Obtient ou définit le chemin de démarrage alternatif, auquel font référence certaines références de formule externes.|
| [library_path](/cells/python-net/fr/aspose.cells/cellshelper/library_path) | Obtient ou définit le chemin de la bibliothèque auquel font référence certaines références de formule externes.|
| [custom_implementation_factory](/cells/python-net/fr/aspose.cells/cellshelper/custom_implementation_factory) | Obtient ou définit la fabrique pour créer des instances avec une implémentation spéciale.|
| [is_cloud_platform](/cells/python-net/fr/aspose.cells/cellshelper/is_cloud_platform) | Veuillez définir cette propriété sur True lors de l'exécution sur une plateforme cloud, telle que : Azure, AWSLambda, etc.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [create_safe_sheet_name](/cells/python-net/fr/aspose.cells/cellshelper/create_safe_sheet_name/#str) | Vérifie le nom de la feuille donnée et en crée un valide si nécessaire.<br/>Si le nom de la feuille donné est conforme aux règles du nom de la feuille Excel, renvoyez-le.<br/>Sinon, la chaîne sera tronquée si la longueur dépasse la limite<br/>et les caractères invalides seront remplacés par « », puis renverront la valeur de chaîne reconstruite.|
| [create_safe_sheet_name](/cells/python-net/fr/aspose.cells/cellshelper/create_safe_sheet_name/#str-char) | Vérifie le nom de la feuille donnée et en crée un valide si nécessaire.<br/>Si le nom de la feuille donné est conforme aux règles du nom de la feuille Excel, renvoyez-le.<br/>Sinon, la chaîne sera tronquée si la longueur dépasse la limite<br/> et les caractères invalides seront remplacés par le caractère donné, puis renverront la valeur de chaîne reconstruite.|
| [get_text_width](/cells/python-net/fr/aspose.cells/cellshelper/get_text_width/#str-aspose.cells.Font-float) | Obtenez la largeur du texte en unité de points.|
| [get_version](/cells/python-net/fr/aspose.cells/cellshelper/get_version/#) | Obtenez la version finale.|
| [cell_name_to_index](/cells/python-net/fr/aspose.cells/cellshelper/cell_name_to_index/#str-any-any) | Obtient les index de lignes et de colonnes de cellules en fonction de leur nom.|
| [cell_index_to_name](/cells/python-net/fr/aspose.cells/cellshelper/cell_index_to_name/#int-int) | Obtient le nom de la cellule en fonction de ses index de ligne et de colonne.|
| [column_index_to_name](/cells/python-net/fr/aspose.cells/cellshelper/column_index_to_name/#int) | Obtient le nom de la colonne en fonction de l'index de la colonne.|
| [column_name_to_index](/cells/python-net/fr/aspose.cells/cellshelper/column_name_to_index/#str) | Obtient l'index de colonne en fonction du nom de la colonne.|
| [row_index_to_name](/cells/python-net/fr/aspose.cells/cellshelper/row_index_to_name/#int) | Obtient le nom de la ligne en fonction de l'index de la ligne.|
| [row_name_to_index](/cells/python-net/fr/aspose.cells/cellshelper/row_name_to_index/#str) | Obtient l'index de ligne en fonction du nom de la ligne.|
| [convert_r1c1_formula_to_a1](/cells/python-net/fr/aspose.cells/cellshelper/convert_r1c1_formula_to_a1/#str-int-int) | Convertit la formule r1c1 de la cellule en formule A1.|
| [convert_a1_formula_to_r1c1](/cells/python-net/fr/aspose.cells/cellshelper/convert_a1_formula_to_r1c1/#str-int-int) | Convertit la formule A1 de la cellule en formule r1c1.|
| [get_date_time_from_double](/cells/python-net/fr/aspose.cells/cellshelper/get_date_time_from_double/#float-bool) | Convertissez la valeur double en valeur date/heure.|
| [get_double_from_date_time](/cells/python-net/fr/aspose.cells/cellshelper/get_double_from_date_time/#DateTime-bool) | Convertissez la date et l'heure en valeur double.|
| [get_used_colors](/cells/python-net/fr/aspose.cells/cellshelper/get_used_colors/#aspose.cells.Workbook) | Obtient toutes les couleurs utilisées dans le classeur.|
| [add_add_in_function](/cells/python-net/fr/aspose.cells/cellshelper/add_add_in_function/#str-int-int-list-aspose.cells.ParameterType) | Ajouter une fonction complémentaire.|
| [merge_files](/cells/python-net/fr/aspose.cells/cellshelper/merge_files/#list-str-str) | Fusionne certains gros fichiers xls en un fichier xls.|
| [need_quote_in_formula](/cells/python-net/fr/aspose.cells/cellshelper/need_quote_in_formula/#str) |Indique si le nom de la feuille doit être placé entre guillemets simples|
| [init_for_dot_net_core](/cells/python-net/fr/aspose.cells/cellshelper/init_for_dot_net_core/#) | Effectuez l'initialisation du programme .NetCore.<br/> Nous vous suggérons d'appeler d'abord cette méthode pour toutes les initialisations .NetCore.<br/>Par exemple:<br/>CellsHelper.InitForDotNetCore();<br/> Classeur wb = new Workbook();|



###  Voir également
* module [`aspose.cells`](..)
