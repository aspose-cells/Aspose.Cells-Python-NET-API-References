---
title: ExportTableOptions classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 560
url: /fr/aspose.cells/exporttableoptions/
is_root: false
---
##  ExportTableOptions classe
Représente toutes les options de la table d'exportation.



Le type ExportTableOptions expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self)`](/cells/python-net/fr/aspose.cells/exporttableoptions/__init__/#) | Construit une nouvelle instance de ExportTableOptions|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [export_column_name](/cells/python-net/fr/aspose.cells/exporttableoptions/export_column_name) | Indique si les données de la première ligne sont exportées vers le nom de colonne du DataTable.<br/> La valeur par défaut est false.|
| [skip_error_value](/cells/python-net/fr/aspose.cells/exporttableoptions/skip_error_value) | Indique si la valeur non valide doit être ignorée pour la colonne.<br/> Par exemple, si le type de colonne est décimal, la valeur est supérieure à décimal.MaxValue<br/>et cette propriété est vraie, nous ne lancerons plus d'exception.<br/> La valeur par défaut est false.|
| [plot_visible_cells](/cells/python-net/fr/aspose.cells/exporttableoptions/plot_visible_cells) | Exporte uniquement les cellules visibles.|
| [plot_visible_rows](/cells/python-net/fr/aspose.cells/exporttableoptions/plot_visible_rows) | Exporte uniquement les lignes visibles.|
| [plot_visible_columns](/cells/python-net/fr/aspose.cells/exporttableoptions/plot_visible_columns) | Exporte uniquement les colonnes visibles.|
| [export_as_string](/cells/python-net/fr/aspose.cells/exporttableoptions/export_as_string) | Exporte la valeur de chaîne des cellules vers le DataTable.|
| [export_as_html_string](/cells/python-net/fr/aspose.cells/exporttableoptions/export_as_html_string) | Exporte la valeur de chaîne HTML des cellules vers le DataTable.|
| [format_strategy](/cells/python-net/fr/aspose.cells/exporttableoptions/format_strategy) | Obtient et définit la stratégie de format lors de l'exportation de la valeur sous forme de valeur de chaîne.|
| [check_mixed_value_type](/cells/python-net/fr/aspose.cells/exporttableoptions/check_mixed_value_type) | Faux, Aspose.Cells définira le type de DataColumn par le type de valeur de la première ligne pour les performances.<br/> Vrai, Aspose.Cells vérifiera si le type de valeur dans la colonne est mixte avant de définir le type de DataColumn<br/> Et le type de valeur est mixte, le type de DataColumn sera une chaîne.|
| [allow_db_null](/cells/python-net/fr/aspose.cells/exporttableoptions/allow_db_null) |Cette valeur indique si les DBNulls sont autorisés dans cette table.|
| [is_vertical](/cells/python-net/fr/aspose.cells/exporttableoptions/is_vertical) | Vrai si une ligne du fichier classeur représente une ligne du DataTable. Faux si une colonne du fichier classeur représente une ligne du DataTable.|
| [indexes](/cells/python-net/fr/aspose.cells/exporttableoptions/indexes) | Les index des colonnes/lignes qui doivent être exportés.|
| [rename_strategy](/cells/python-net/fr/aspose.cells/exporttableoptions/rename_strategy) | Stratégie pour les noms de colonnes en double.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`preprocess_exported_value(self, cell_row, cell_column, value)`](/cells/python-net/fr/aspose.cells/exporttableoptions/preprocess_exported_value/#int-int-aspose.cells.cellvalue) | Prétraiter la valeur de la cellule actuelle à exporter.|



###  Remarques

S'il existe des exigences particulières concernant l'exportation, comme ignorer les valeurs d'erreur, l'utilisateur peut étendre cette classe
pour écraser les API correspondantes pour atteindre l'objectif.

###  Voir également
* module [`aspose.cells`](..)
