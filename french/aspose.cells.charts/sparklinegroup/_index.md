---
title: SparklineGroup classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 290
url: /fr/aspose.cells.charts/sparklinegroup/
is_root: false
---
##  SparklineGroup classe
Le groupe [`Sparkline`](/cells/python-net/fr/aspose.cells.charts/sparkline) est organisé en groupes Sparkline. Un groupe SparklineGroup contient un nombre variable d'éléments Sparkline.
Un groupe de graphiques sparkline spécifie le type, les paramètres d'affichage et les paramètres d'axe des graphiques sparkline.



Le type SparklineGroup expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [preset_style](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/preset_style) | Obtient et définit le type de style prédéfini du groupe Sparkline.|
| [sparkline_collection](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/sparkline_collection) | Obtient la collection de l'objet [`Sparkline`](/cells/python-net/fr/aspose.cells.charts/sparkline).|
| [sparklines](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/sparklines) | Obtient la collection de l'objet [`Sparkline`](/cells/python-net/fr/aspose.cells.charts/sparkline).|
| [type](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/type) | Indique le type de sparkline du groupe de sparkline.|
| [plot_empty_cells_type](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/plot_empty_cells_type) | Indique comment tracer des cellules vides.|
| [display_hidden](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/display_hidden) | Indique s'il faut afficher les données dans les lignes et les colonnes masquées.|
| [show_high_point](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/show_high_point) | Indique s'il faut mettre en évidence les points de données les plus élevés dans le groupe Sparkline.|
| [high_point_color](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/high_point_color) | Obtient et définit la couleur des points de données les plus élevés dans le groupe Sparkline.|
| [show_low_point](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/show_low_point) | Indique s'il faut mettre en évidence les points les plus bas des données dans le groupe Sparkline.|
| [low_point_color](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/low_point_color) | Obtient et définit la couleur des points les plus bas des données dans le groupe Sparkline.|
| [show_negative_points](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/show_negative_points) |Indique s'il faut mettre en évidence les valeurs négatives du groupe Sparkline avec une couleur ou un marqueur différent.|
| [negative_points_color](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/negative_points_color) | Obtient et définit la couleur des valeurs négatives sur le groupe Sparkline.|
| [show_first_point](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/show_first_point) | Indique s'il faut mettre en évidence le premier point de données dans le groupe Sparkline.|
| [first_point_color](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/first_point_color) | Obtient et définit la couleur du premier point de données dans le groupe Sparkline.|
| [show_last_point](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/show_last_point) | Indique s'il faut mettre en évidence le dernier point de données dans le groupe Sparkline.|
| [last_point_color](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/last_point_color) | Obtient et définit la couleur du dernier point de données dans le groupe Sparkline.|
| [show_markers](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/show_markers) | Indique s'il faut mettre en surbrillance chaque point de chaque ligne sparkline dans le groupe sparkline.|
| [markers_color](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/markers_color) | Obtient et définit la couleur des points dans chaque ligne sparkline du groupe sparkline.|
| [series_color](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/series_color) | Obtient et définit la couleur des sparklines dans le groupe sparklines.|
| [plot_right_to_left](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/plot_right_to_left) | Indique si les données du tracé sont de droite à gauche.|
| [line_weight](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/line_weight) | Obtient et définit l'épaisseur de ligne dans chaque sparkline de ligne dans le groupe sparkline, en unités de points.|
| [horizontal_axis_color](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/horizontal_axis_color) |Obtient et définit la couleur de l'axe horizontal dans le groupe Sparkline.|
| [show_horizontal_axis](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/show_horizontal_axis) | Indique s'il faut afficher l'axe horizontal du sparkline.<br/> L'axe horizontal apparaît si le graphique sparkline contient des données qui croisent l'axe zéro.|
| [horizontal_axis_date_range](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/horizontal_axis_date_range) | Représente la plage qui contient les valeurs de date pour les données sparkline.|
| [vertical_axis_max_value_type](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/vertical_axis_max_value_type) | Représente le type de valeur maximale de l'axe vertical.|
| [vertical_axis_max_value](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/vertical_axis_max_value) | Obtient et définit la valeur maximale personnalisée pour l'axe vertical.|
| [vertical_axis_min_value_type](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/vertical_axis_min_value_type) | Représente le type de valeur minimale de l'axe vertical.|
| [vertical_axis_min_value](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/vertical_axis_min_value) | Obtient et définit la valeur minimale personnalisée pour l'axe vertical.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`reset_ranges(self, data_range, is_vertical, location_range)`](/cells/python-net/fr/aspose.cells.charts/sparklinegroup/reset_ranges/#str-bool-aspose.cells.cellarea) | Réinitialise la plage de données et la plage d'emplacement du groupe sparkline.<br/> Cette méthode effacera les éléments Sparkline d'origine du groupe et créera de nouveaux éléments Sparkline pour les nouvelles plages.|



###  Exemple

```python
from aspose.cells import CellArea, SaveFormat, Workbook
from aspose.cells.charts import SparklineType
from aspose.pydrawing import Color

book = Workbook()
sheet = book.worksheets[0]
sheet.cells.get("A1").put_value(5)
sheet.cells.get("B1").put_value(2)
sheet.cells.get("C1").put_value(1)
sheet.cells.get("D1").put_value(3)
#  Define the CellArea
ca = CellArea()
ca.start_column = 4
ca.end_column = 4
ca.start_row = 0
ca.end_row = 0
idx = sheet.sparkline_groups.add(SparklineType.LINE, "A1:D1", False, ca)
group = sheet.sparkline_groups[idx]
group.sparklines.add(sheet.name + "!A1:D1", 0, 4)
#  Create CellsColor
clr = book.create_cells_color()
clr.color = Color.orange
group.series_color = clr
#  set the high points are colored green and the low points are colored red
group.show_high_point = True
group.show_low_point = True
group.high_point_color.color = Color.green
group.low_point_color.color = Color.red
#  set line weight
group.line_weight = 1.0
book.save("output.xlsx", SaveFormat.XLSX)

```

###  Voir également
* module [`aspose.cells.charts`](..)
* classe [`Sparkline`](/cells/python-net/fr/aspose.cells.charts/sparkline)
