---
title: AutoFilter classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 40
url: /fr/aspose.cells/autofilter/
is_root: false
---
##  AutoFilter classe
Représente le filtrage automatique pour la feuille de calcul spécifiée.



Le type AutoFilter expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [sorter](/cells/python-net/fr/aspose.cells/autofilter/sorter) | Obtient le trieur de données.|
| [range](/cells/python-net/fr/aspose.cells/autofilter/range) | Représente la plage à laquelle s'applique le filtre automatique spécifié.|
| [show_filter_button](/cells/python-net/fr/aspose.cells/autofilter/show_filter_button) | Indique si le bouton Filtre automatique pour cette colonne est visible.|
| [filter_columns](/cells/python-net/fr/aspose.cells/autofilter/filter_columns) | Obtient la collection des colonnes de filtre.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`get_cell_area(self)`](/cells/python-net/fr/aspose.cells/autofilter/get_cell_area/#) | Obtient le [`CellArea`](/cells/python-net/fr/aspose.cells/cellarea) auquel s'applique ce filtre automatique.|
| [`get_cell_area(self, refresh_applied_range)`](/cells/python-net/fr/aspose.cells/autofilter/get_cell_area/#bool) | Obtient le [`CellArea`](/cells/python-net/fr/aspose.cells/cellarea) auquel s'applique le filtre automatique spécifié.|
| [`remove_filter(self, field_index, criteria)`](/cells/python-net/fr/aspose.cells/autofilter/remove_filter/#int-str) | Supprime un filtre pour une colonne de filtre.|
| [`remove_filter(self, field_index)`](/cells/python-net/fr/aspose.cells/autofilter/remove_filter/#int) | Retirez le filtre spécifique.|
| [`custom(self, field_index, operator_type1, criteria1)`](/cells/python-net/fr/aspose.cells/autofilter/custom/#int-aspose.cells.filteroperatortype-any) | Filtre une liste avec des critères personnalisés.|
| [`custom(self, field_index, operator_type1, criteria1, is_and, operator_type2, criteria2)`](/cells/python-net/fr/aspose.cells/autofilter/custom/#int-aspose.cells.filteroperatortype-any-bool-aspose.cells.filteroperatortype-any) | Filtre une liste avec des critères personnalisés.|
| [`refresh(self)`](/cells/python-net/fr/aspose.cells/autofilter/refresh/#) | Actualisez les filtres automatiques pour masquer ou afficher les lignes.|
| [`refresh(self, hide_rows)`](/cells/python-net/fr/aspose.cells/autofilter/refresh/#bool) | Obtient tous les index des lignes masquées.|
| [`set_range(self, row, start_column, end_column)`](/cells/python-net/fr/aspose.cells/autofilter/set_range/#int-int-int) | Définit la plage à laquelle s'applique le filtre automatique spécifié.|
| [`add_filter(self, field_index, criteria)`](/cells/python-net/fr/aspose.cells/autofilter/add_filter/#int-str) | Ajoute un filtre pour une colonne de filtre.|
| [`add_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second)`](/cells/python-net/fr/aspose.cells/autofilter/add_date_filter/#int-aspose.cells.datetimegroupingtype-int-int-int-int-int-int) | Ajoute un filtre de date.|
| [`remove_date_filter(self, field_index, date_time_grouping_type, year, month, day, hour, minute, second)`](/cells/python-net/fr/aspose.cells/autofilter/remove_date_filter/#int-aspose.cells.datetimegroupingtype-int-int-int-int-int-int) |Supprime un filtre de date.|
| [`filter(self, field_index, criteria)`](/cells/python-net/fr/aspose.cells/autofilter/filter/#int-str) | Filtre une liste avec des critères spécifiés.|
| [`filter_top10(self, field_index, is_top, is_percent, item_count)`](/cells/python-net/fr/aspose.cells/autofilter/filter_top10/#int-bool-bool-int) | Filtrer les 10 premiers éléments de la liste|
| [`dynamic_filter(self, field_index, dynamic_filter_type)`](/cells/python-net/fr/aspose.cells/autofilter/dynamic_filter/#int-aspose.cells.dynamicfiltertype) | Ajoute un filtre dynamique.|
| [`add_font_color_filter(self, field_index, color)`](/cells/python-net/fr/aspose.cells/autofilter/add_font_color_filter/#int-aspose.cells.cellscolor) | Ajoute un filtre de couleur de police.|
| [`add_fill_color_filter(self, field_index, pattern, foreground_color, background_color)`](/cells/python-net/fr/aspose.cells/autofilter/add_fill_color_filter/#int-aspose.cells.backgroundtype-aspose.cells.cellscolor-aspose.cells.cellscolor) | Ajoute un filtre de couleur de remplissage.|
| [`add_icon_filter(self, field_index, icon_set_type, icon_id)`](/cells/python-net/fr/aspose.cells/autofilter/add_icon_filter/#int-aspose.cells.iconsettype-int) | Ajoute un filtre d'icône.|
| [`match_blanks(self, field_index)`](/cells/python-net/fr/aspose.cells/autofilter/match_blanks/#int) | Faites correspondre toutes les cellules vides de la liste.|
| [`match_non_blanks(self, field_index)`](/cells/python-net/fr/aspose.cells/autofilter/match_non_blanks/#int) | Faire correspondre toutes les cellules non vides de la liste.|
| [`show_all(self)`](/cells/python-net/fr/aspose.cells/autofilter/show_all/#) | Afficher toutes les lignes.|



###  Exemple

```python
from aspose.cells import Workbook

# Creating a file stream containing the Excel file to be opened
# Instantiating a Workbook object
workbook = Workbook("template.xlsx")
# Accessing the first worksheet in the Excel file
worksheet = workbook.worksheets[0]
# Creating AutoFilter by giving the cells range of the heading row
worksheet.auto_filter.range = "A1:B1"
# Filtering columns with specified values
worksheet.auto_filter.filter(1, "Bananas")
# Saving the modified Excel file.
workbook.save("output.xls")

```

###  Voir également
* module [`aspose.cells`](..)
* classe [`CellArea`](/cells/python-net/fr/aspose.cells/cellarea)
