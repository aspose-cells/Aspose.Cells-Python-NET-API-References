---
title: ListObject classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 30
url: /fr/aspose.cells.tables/listobject/
is_root: false
---
##  ListObject classe
Représente un objet de liste sur une feuille de calcul.
 L'objet ListObject est un membre de la collection ListObjects.
La collection ListObjects contient tous les objets de liste d'une feuille de calcul.



Le type ListObject expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [start_row](/cells/python-net/fr/aspose.cells.tables/listobject/start_row) | Obtient la ligne de départ de la plage.|
| [start_column](/cells/python-net/fr/aspose.cells.tables/listobject/start_column) | Obtient la colonne de départ de la plage.|
| [end_row](/cells/python-net/fr/aspose.cells.tables/listobject/end_row) | Obtient la dernière ligne de la plage.|
| [end_column](/cells/python-net/fr/aspose.cells.tables/listobject/end_column) | Obtient la colonne de fin de la plage.|
| [list_columns](/cells/python-net/fr/aspose.cells.tables/listobject/list_columns) | Obtient les ListColumns du ListObject.|
| [show_header_row](/cells/python-net/fr/aspose.cells.tables/listobject/show_header_row) | Obtient et définit si ce ListObject affiche la ligne d'en-tête.|
| [show_totals](/cells/python-net/fr/aspose.cells.tables/listobject/show_totals) | Obtient et définit si ce ListObject affiche le nombre total de lignes.|
| [data_range](/cells/python-net/fr/aspose.cells.tables/listobject/data_range) | Obtient la plage de données du ListObject.|
| [query_table](/cells/python-net/fr/aspose.cells.tables/listobject/query_table) | Obtient la table de requête liée.|
| [data_source_type](/cells/python-net/fr/aspose.cells.tables/listobject/data_source_type) |Obtient le type de source de données de la table.|
| [auto_filter](/cells/python-net/fr/aspose.cells.tables/listobject/auto_filter) | Obtient un filtre automatique.|
| [display_name](/cells/python-net/fr/aspose.cells.tables/listobject/display_name) | Obtient et définit le nom d'affichage.|
| [comment](/cells/python-net/fr/aspose.cells.tables/listobject/comment) | Obtient et définit le commentaire de la table.|
| [show_table_style_first_column](/cells/python-net/fr/aspose.cells.tables/listobject/show_table_style_first_column) | Indique si le style doit être appliqué à la première colonne du tableau.|
| [show_table_style_last_column](/cells/python-net/fr/aspose.cells.tables/listobject/show_table_style_last_column) | Indique si la dernière colonne du tableau doit avoir le style appliqué.|
| [show_table_style_row_stripes](/cells/python-net/fr/aspose.cells.tables/listobject/show_table_style_row_stripes) | Indique si le formatage des bandes de lignes est appliqué.|
| [show_table_style_column_stripes](/cells/python-net/fr/aspose.cells.tables/listobject/show_table_style_column_stripes) | Indique si la mise en forme des bandes de colonnes est appliquée.|
| [table_style_type](/cells/python-net/fr/aspose.cells.tables/listobject/table_style_type) | Obtient et le style de table intégré.|
| [table_style_name](/cells/python-net/fr/aspose.cells.tables/listobject/table_style_name) | Obtient et définit le nom du style de table.|
| [xml_map](/cells/python-net/fr/aspose.cells.tables/listobject/xml_map) | Obtient un [`ListObject.xml_map`](/cells/python-net/fr/aspose.cells.tables/listobject#xml_map) utilisé pour cette liste.|
| [alternative_text](/cells/python-net/fr/aspose.cells.tables/listobject/alternative_text) | Obtient et définit le texte alternatif.|
| [alternative_description](/cells/python-net/fr/aspose.cells.tables/listobject/alternative_description) | Obtient et définit la description alternative.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`put_cell_value(self, row_offset, column_offset, value)`](/cells/python-net/fr/aspose.cells.tables/listobject/put_cell_value/#int-int-any) | Mettez la valeur dans la cellule.|
| [`put_cell_value(self, row_offset, column_offset, value, is_totals_row_label)`](/cells/python-net/fr/aspose.cells.tables/listobject/put_cell_value/#int-int-any-bool) | Mettez la valeur dans la cellule.|
| [`put_cell_formula(self, row_offset, column_offset, formula)`](/cells/python-net/fr/aspose.cells.tables/listobject/put_cell_formula/#int-int-str) | Placez la formule dans la cellule du tableau.|
| [`put_cell_formula(self, row_offset, column_offset, formula, is_totals_row_formula)`](/cells/python-net/fr/aspose.cells.tables/listobject/put_cell_formula/#int-int-str-bool) | Placez la formule dans la cellule du tableau.|
| [`convert_to_range(self)`](/cells/python-net/fr/aspose.cells.tables/listobject/convert_to_range/#) | Convertir le tableau en plage.|
| [`convert_to_range(self, options)`](/cells/python-net/fr/aspose.cells.tables/listobject/convert_to_range/#aspose.cells.tables.tabletorangeoptions) | Convertir le tableau en plage.|
| [`resize(self, start_row, start_column, end_row, end_column, has_headers)`](/cells/python-net/fr/aspose.cells.tables/listobject/resize/#int-int-int-int-bool) | Redimensionner la plage de l'objet de liste.|
| [`update_column_name(self)`](/cells/python-net/fr/aspose.cells.tables/listobject/update_column_name/#) | Met à jour le nom de toutes les colonnes de la liste à partir de la feuille de calcul.|
| [`filter(self)`](/cells/python-net/fr/aspose.cells.tables/listobject/filter/#) | Filtrer le tableau.|
| [`apply_style_to_range(self)`](/cells/python-net/fr/aspose.cells.tables/listobject/apply_style_to_range/#) | Appliquer le style de tableau à la plage.|



###  Exemple

```python
from aspose.cells import CellsHelper, Workbook
from aspose.cells.tables import TotalsCalculation

workbook = Workbook()
cells = workbook.worksheets[0].cells
for i in range(5):
    cells.get(0, i).put_value(CellsHelper.column_index_to_name(i))
for row in range(1, 10):
    for column in range(5):
        cells.get(row, column).put_value(row * column)
tables = workbook.worksheets[0].list_objects
index = tables.add(0, 0, 9, 4, True)
table = tables[0]
table.show_totals = True
table.list_columns[4].totals_calculation = TotalsCalculation.SUM
workbook.save(r"Book1.xlsx")

```

###  Voir également
* module [`aspose.cells.tables`](..)
