---
title: Chart classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 30
url: /fr/aspose.cells.charts/chart/
is_root: false
---
##  Chart classe
Encapsule l'objet qui représente un seul graphique Excel.



Le type Chart expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [style](/cells/python-net/fr/aspose.cells.charts/chart/style) | Obtient et définit le style intégré.|
| [chart_object](/cells/python-net/fr/aspose.cells.charts/chart/chart_object) | Représente la forme du graphique ;|
| [hide_pivot_field_buttons](/cells/python-net/fr/aspose.cells.charts/chart/hide_pivot_field_buttons) | Indique si les boutons du champ du graphique croisé dynamique doivent être masqués uniquement lorsque le graphique est un graphique croisé dynamique.|
| [pivot_options](/cells/python-net/fr/aspose.cells.charts/chart/pivot_options) | Spécifie les contrôles de pivot qui apparaissent sur le graphique|
| [pivot_source](/cells/python-net/fr/aspose.cells.charts/chart/pivot_source) |La source est les données du tableau croisé dynamique.<br/> Si PivotSource n'est pas vide, le graphique est PivotChart.|
| [plot_by](/cells/python-net/fr/aspose.cells.charts/chart/plot_by) | Obtient et définit si le tracé est effectué par ligne ou par colonne.|
| [plot_empty_cells_type](/cells/python-net/fr/aspose.cells.charts/chart/plot_empty_cells_type) | Obtient et définit comment tracer les cellules vides.|
| [plot_visible_cells](/cells/python-net/fr/aspose.cells.charts/chart/plot_visible_cells) | Indique si seules les cellules visibles du tracé doivent être tracées.|
| [plot_visible_cells_only](/cells/python-net/fr/aspose.cells.charts/chart/plot_visible_cells_only) | Indique si seules les cellules visibles du tracé sont visibles.|
| [display_na_as_blank](/cells/python-net/fr/aspose.cells.charts/chart/display_na_as_blank) | Indique si #N/A doit être affiché comme valeur vide.|
| [name](/cells/python-net/fr/aspose.cells.charts/chart/name) | Obtient et définit le nom du graphique.|
| [size_with_window](/cells/python-net/fr/aspose.cells.charts/chart/size_with_window) | Vrai si Microsoft Excel redimensionne le graphique pour qu'il corresponde à la taille de la fenêtre de la feuille de graphique.|
| [worksheet](/cells/python-net/fr/aspose.cells.charts/chart/worksheet) | Obtient la feuille de calcul qui contient ce graphique.|
| [shapes](/cells/python-net/fr/aspose.cells.charts/chart/shapes) | Renvoie toutes les formes de dessin dans ce graphique.|
| [print_size](/cells/python-net/fr/aspose.cells.charts/chart/print_size) | Obtient et définit la taille du graphique imprimé.|
| [type](/cells/python-net/fr/aspose.cells.charts/chart/type) | Obtient ou définit le type d'un graphique.|
| [n_series](/cells/python-net/fr/aspose.cells.charts/chart/n_series) | Obtient une collection [`SeriesCollection`](/cells/python-net/fr/aspose.cells.charts/seriescollection) représentant la série de données dans le graphique.|
| [filtered_n_series](/cells/python-net/fr/aspose.cells.charts/chart/filtered_n_series) | Obtient une collection [`SeriesCollection`](/cells/python-net/fr/aspose.cells.charts/seriescollection) représentant les séries de données filtrées dans le graphique.|
| [title](/cells/python-net/fr/aspose.cells.charts/chart/title) | Obtient le titre du graphique.|
| [sub_title](/cells/python-net/fr/aspose.cells.charts/chart/sub_title) | Obtient le sous-titre du graphique.<br/> Uniquement pour le fichier au format ODS.|
| [plot_area](/cells/python-net/fr/aspose.cells.charts/chart/plot_area) |Obtient la zone de tracé du graphique qui inclut les étiquettes de graduation des axes.|
| [chart_area](/cells/python-net/fr/aspose.cells.charts/chart/chart_area) | Obtient la zone de graphique dans la feuille de calcul.|
| [category_axis](/cells/python-net/fr/aspose.cells.charts/chart/category_axis) | Obtient l'axe X du graphique.|
| [value_axis](/cells/python-net/fr/aspose.cells.charts/chart/value_axis) | Obtient l'axe Y du graphique.|
| [second_value_axis](/cells/python-net/fr/aspose.cells.charts/chart/second_value_axis) | Obtient le deuxième axe Y du graphique.|
| [second_category_axis](/cells/python-net/fr/aspose.cells.charts/chart/second_category_axis) | Obtient le deuxième axe X du graphique.|
| [series_axis](/cells/python-net/fr/aspose.cells.charts/chart/series_axis) | Obtient l'axe des séries du graphique.|
| [legend](/cells/python-net/fr/aspose.cells.charts/chart/legend) | Obtient la légende du graphique.|
| [chart_data_table](/cells/python-net/fr/aspose.cells.charts/chart/chart_data_table) | Représente le tableau de données du graphique.|
| [show_legend](/cells/python-net/fr/aspose.cells.charts/chart/show_legend) | Obtient ou définit une valeur indiquant si la légende du graphique doit être affichée. La valeur par défaut est « true ».|
| [is_rectangular_cornered](/cells/python-net/fr/aspose.cells.charts/chart/is_rectangular_cornered) | Obtient ou définit une valeur indiquant si la zone du graphique est rectangulaire et angulaire.<br/> La valeur par défaut est vrai.|
| [show_data_table](/cells/python-net/fr/aspose.cells.charts/chart/show_data_table) | Obtient ou définit une valeur indiquant si le graphique affiche un tableau de données.|
| [first_slice_angle](/cells/python-net/fr/aspose.cells.charts/chart/first_slice_angle) | Obtient ou définit l'angle de la première tranche du graphique à secteurs ou du graphique en anneau, en degrés (dans le sens des aiguilles d'une montre à partir de la verticale).<br/> S'applique uniquement aux graphiques à secteurs, à secteurs 3D et en anneau, de 0 à 360.|
| [gap_width](/cells/python-net/fr/aspose.cells.charts/chart/gap_width) | Renvoie ou définit l'espace entre les groupes de barres ou de colonnes, sous forme de pourcentage de la largeur de la barre ou de la colonne.<br/> La valeur de cette propriété doit être comprise entre 0 et 500.|
| [gap_depth](/cells/python-net/fr/aspose.cells.charts/chart/gap_depth) |Obtient ou définit la distance entre les séries de données dans un graphique 3D, en pourcentage de la largeur du marqueur.<br/> La valeur de cette propriété doit être comprise entre 0 et 500.|
| [floor](/cells/python-net/fr/aspose.cells.charts/chart/floor) | Renvoie un objet [`Chart.floor`](/cells/python-net/fr/aspose.cells.charts/chart#floor) qui représente les murs d'un graphique 3D.|
| [walls](/cells/python-net/fr/aspose.cells.charts/chart/walls) | Renvoie un objet [`Chart.walls`](/cells/python-net/fr/aspose.cells.charts/chart#walls) qui représente les murs d'un graphique 3D.|
| [back_wall](/cells/python-net/fr/aspose.cells.charts/chart/back_wall) | Renvoie un objet [`Chart.walls`](/cells/python-net/fr/aspose.cells.charts/chart#walls) qui représente le mur arrière d'un graphique 3D.|
| [side_wall](/cells/python-net/fr/aspose.cells.charts/chart/side_wall) | Renvoie un objet [`Chart.walls`](/cells/python-net/fr/aspose.cells.charts/chart#walls) qui représente la paroi latérale d'un graphique 3D.|
| [walls_and_gridlines_2d](/cells/python-net/fr/aspose.cells.charts/chart/walls_and_gridlines_2d) | Vrai si les lignes de la grille sont dessinées en deux dimensions sur un graphique 3D.|
| [rotation_angle](/cells/python-net/fr/aspose.cells.charts/chart/rotation_angle) | Représente la rotation de la vue graphique 3D (la rotation de la zone de tracé autour de l'axe z, en degrés).|
| [elevation](/cells/python-net/fr/aspose.cells.charts/chart/elevation) | Représente l'élévation de la vue graphique 3D, en degrés.|
| [right_angle_axes](/cells/python-net/fr/aspose.cells.charts/chart/right_angle_axes) | Vrai si les axes du graphique sont à angle droit. Applicable uniquement aux graphiques 3D (sauf les graphiques Column3D et les graphiques à secteurs 3D).|
| [auto_scaling](/cells/python-net/fr/aspose.cells.charts/chart/auto_scaling) | Vrai si Microsoft Excel met à l'échelle un graphique 3D afin qu'il soit plus proche en taille du graphique 2D équivalent.<br/> La propriété RightAngleAxes doit être True.|
| [height_percent](/cells/python-net/fr/aspose.cells.charts/chart/height_percent) | Renvoie ou définit la hauteur d'un graphique 3D en pourcentage de la largeur du graphique (entre 5 et 500 pour cent).|
| [perspective](/cells/python-net/fr/aspose.cells.charts/chart/perspective) |Renvoie ou définit la perspective du graphique 3D. Doit être compris entre 0 et 100.<br/> Cette propriété est ignorée si la propriété RightAngleAxes est True.|
| [is_3d](/cells/python-net/fr/aspose.cells.charts/chart/is_3d) | Indique si le graphique est un graphique 3D.|
| [depth_percent](/cells/python-net/fr/aspose.cells.charts/chart/depth_percent) | Représente la profondeur d'un graphique 3D en pourcentage de la largeur du graphique (entre 20 et 2 000 %).|
| [actual_chart_size](/cells/python-net/fr/aspose.cells.charts/chart/actual_chart_size) | Obtient la taille réelle du graphique en unités de pixels.|
| [placement](/cells/python-net/fr/aspose.cells.charts/chart/placement) | Représente la manière dont le graphique est attaché aux cellules situées en dessous.|
| [page_setup](/cells/python-net/fr/aspose.cells.charts/chart/page_setup) | Représente la description de la configuration de la page dans ce graphique.|
| [line](/cells/python-net/fr/aspose.cells.charts/chart/line) | Obtient la ligne.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`calculate(self)`](/cells/python-net/fr/aspose.cells.charts/chart/calculate/#) | Calcule la position personnalisée de la zone de tracé, des axes si leur position est attribuée automatiquement.|
| [`calculate(self, calculate_options)`](/cells/python-net/fr/aspose.cells.charts/chart/calculate/#aspose.cells.charts.chartcalculateoptions) | Calcule la position personnalisée de la zone de tracé, des axes si leur position est attribuée automatiquement, avec les options de calcul du graphique.|
| [`to_image(self, image_file)`](/cells/python-net/fr/aspose.cells.charts/chart/to_image/#str) | Crée l'image du graphique et l'enregistre dans un fichier.<br/> L'extension du nom de fichier détermine le format de l'image.|
| [`to_image(self, image_file, image_type)`](/cells/python-net/fr/aspose.cells.charts/chart/to_image/#str-aspose.cells.drawing.imagetype) | Crée l'image du graphique et l'enregistre dans un fichier dans le type d'image spécifié.|
| [`to_image(self, image_file, jpeg_quality)`](/cells/python-net/fr/aspose.cells.charts/chart/to_image/#str-int) |Crée l'image du graphique et l'enregistre dans un fichier au format Jpeg.|
| [`to_image(self, stream, jpeg_quality)`](/cells/python-net/fr/aspose.cells.charts/chart/to_image/#io.rawiobase-int) | Crée l'image du graphique et l'enregistre dans un flux au format Jpeg.|
| [`to_image(self, stream, image_type)`](/cells/python-net/fr/aspose.cells.charts/chart/to_image/#io.rawiobase-aspose.cells.drawing.imagetype) | Crée l'image du graphique et l'enregistre dans un flux au format spécifié.|
| [`to_image(self, image_file, options)`](/cells/python-net/fr/aspose.cells.charts/chart/to_image/#str-aspose.cells.rendering.imageorprintoptions) | Crée l'image du graphique et l'enregistre dans un fichier.<br/> L'extension du nom de fichier détermine le format de l'image.|
| [`to_image(self, stream, options)`](/cells/python-net/fr/aspose.cells.charts/chart/to_image/#io.rawiobase-aspose.cells.rendering.imageorprintoptions) | Crée l'image du graphique et l'enregistre dans un flux au format spécifié.|
| [`to_pdf(self, file_name)`](/cells/python-net/fr/aspose.cells.charts/chart/to_pdf/#str) | Enregistre le graphique dans un fichier PDF.|
| [`to_pdf(self, file_name, desired_page_width, desired_page_height, h_alignment_type, v_alignment_type)`](/cells/python-net/fr/aspose.cells.charts/chart/to_pdf/#str-float-float-aspose.cells.pagelayoutalignmenttype-aspose.cells.pagelayoutalignmenttype) | Enregistre le graphique dans un fichier PDF.|
| [`to_pdf(self, stream)`](/cells/python-net/fr/aspose.cells.charts/chart/to_pdf/#io.rawiobase) | Crée le graphique PDF et l'enregistre dans un flux.|
| [`to_pdf(self, stream, desired_page_width, desired_page_height, h_alignment_type, v_alignment_type)`](/cells/python-net/fr/aspose.cells.charts/chart/to_pdf/#io.rawiobase-float-float-aspose.cells.pagelayoutalignmenttype-aspose.cells.pagelayoutalignmenttype) | Crée le graphique PDF et l'enregistre dans un flux.|
| [`is_refered_by_chart(self, row_index, column_index)`](/cells/python-net/fr/aspose.cells.charts/chart/is_refered_by_chart/#int-int) | Renvoie si la cellule est référencée par le graphique.|
| [`is_cell_refered_by_chart(self, sheet_index, row_index, column_index)`](/cells/python-net/fr/aspose.cells.charts/chart/is_cell_refered_by_chart/#int-int-int) | Renvoie si la cellule est référencée par le graphique.|
| [`is_chart_data_changed(self)`](/cells/python-net/fr/aspose.cells.charts/chart/is_chart_data_changed/#) | Détecte si la source de données d'un graphique a changé.|
| [`refresh_pivot_data(self)`](/cells/python-net/fr/aspose.cells.charts/chart/refresh_pivot_data/#) | Actualise les données du graphique à partir du tableau croisé dynamique.|
| [`change_template(self, data)`](/cells/python-net/fr/aspose.cells.charts/chart/change_template/#bytes) | Changer le type de graphique avec un modèle prédéfini.|
| [`move(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column)`](/cells/python-net/fr/aspose.cells.charts/chart/move/#int-int-int-int) | Déplace le graphique vers un emplacement spécifié.|
| [`get_actual_size(self)`](/cells/python-net/fr/aspose.cells.charts/chart/get_actual_size/#) | Obtient la taille réelle du graphique en unités de pixels.|
| [`has_axis(self, aixs_type, is_primary)`](/cells/python-net/fr/aspose.cells.charts/chart/has_axis/#aspose.cells.charts.axistype-bool) | Renvoie les axes qui existent sur le graphique.|
| [`switch_row_column(self)`](/cells/python-net/fr/aspose.cells.charts/chart/switch_row_column/#) | Change de ligne/colonne.|
| [`get_chart_data_range(self)`](/cells/python-net/fr/aspose.cells.charts/chart/get_chart_data_range/#) | Obtient la plage de sources de données du graphique.|
| [`set_chart_data_range(self, area, is_vertical)`](/cells/python-net/fr/aspose.cells.charts/chart/set_chart_data_range/#str-bool) | Spécifie la plage de données pour un graphique.|



###  Exemple

Les codes suivants montrent comment créer un graphique avec des codes .Net.

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType

workbook = Workbook()
sheet = workbook.worksheets[0]
cells = sheet.cells
cells.get(0, 1).put_value("Income")
cells.get(1, 0).put_value("Company A")
cells.get(2, 0).put_value("Company B")
cells.get(3, 0).put_value("Company C")
cells.get(1, 1).put_value(10000)
cells.get(2, 1).put_value(20000)
cells.get(3, 1).put_value(30000)
chartIndex = sheet.charts.add(ChartType.COLUMN, 9, 9, 21, 15)
chart = sheet.charts[chartIndex]
chart.set_chart_data_range("A1:B4", True)
chart.show_legend = True
chart.title.text = "Income Analysis"

```

###  Voir également
* module [`aspose.cells.charts`](..)
* classe [`SeriesCollection`](/cells/python-net/fr/aspose.cells.charts/seriescollection)
