---
title: ChartDataTable classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 70
url: /fr/aspose.cells.charts/chartdatatable/
is_root: false
---
##  ChartDataTable classe
Représente un tableau de données de graphique.



Le type ChartDataTable expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [font](/cells/python-net/fr/aspose.cells.charts/chartdatatable/font) | Obtient un objet [`ChartDataTable.font`](/cells/python-net/fr/aspose.cells.charts/chartdatatable#font) qui représente le paramètre de police de la table de données de graphique spécifiée.|
| [auto_scale_font](/cells/python-net/fr/aspose.cells.charts/chartdatatable/auto_scale_font) | Vrai si le texte de l'objet change de taille de police lorsque la taille de l'objet change.<br/> La valeur par défaut est True.|
| [background_mode](/cells/python-net/fr/aspose.cells.charts/chartdatatable/background_mode) | Obtient et définit le mode d'affichage de l'arrière-plan|
| [has_border_horizontal](/cells/python-net/fr/aspose.cells.charts/chartdatatable/has_border_horizontal) | Vrai si le tableau de données du graphique comporte des bordures de cellules horizontales|
| [has_horizontal_border](/cells/python-net/fr/aspose.cells.charts/chartdatatable/has_horizontal_border) | Vrai si le tableau de données du graphique comporte des bordures de cellules horizontales|
| [has_border_vertical](/cells/python-net/fr/aspose.cells.charts/chartdatatable/has_border_vertical) |Vrai si le tableau de données du graphique comporte des bordures de cellules verticales|
| [has_vertical_border](/cells/python-net/fr/aspose.cells.charts/chartdatatable/has_vertical_border) |Vrai si le tableau de données du graphique comporte des bordures de cellules verticales|
| [has_border_outline](/cells/python-net/fr/aspose.cells.charts/chartdatatable/has_border_outline) | Vrai si le tableau de données du graphique comporte des bordures de contour|
| [has_outline_border](/cells/python-net/fr/aspose.cells.charts/chartdatatable/has_outline_border) | Vrai si le tableau de données du graphique comporte des bordures de contour|
| [show_legend_key](/cells/python-net/fr/aspose.cells.charts/chartdatatable/show_legend_key) | Vrai si la clé de légende de l'étiquette de données est visible.|
| [border](/cells/python-net/fr/aspose.cells.charts/chartdatatable/border) | Renvoie un objet Border qui représente la bordure de l'objet|



###  Exemple

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Adding a sample value to "A1" cell
worksheet.cells.get("A1").put_value(50)
# Adding a sample value to "A2" cell
worksheet.cells.get("A2").put_value(100)
# Adding a sample value to "A3" cell
worksheet.cells.get("A3").put_value(150)
# Adding a sample value to "B1" cell
worksheet.cells.get("B1").put_value(60)
# Adding a sample value to "B2" cell
worksheet.cells.get("B2").put_value(32)
# Adding a sample value to "B3" cell
worksheet.cells.get("B3").put_value(50)
# Adding a chart to the worksheet
chartIndex = worksheet.charts.add(ChartType.COLUMN, 5, 0, 25, 10)
# Accessing the instance of the newly added chart
chart = worksheet.charts[chartIndex]
# Adding NSeries (chart data source) to the chart ranging from "A1" cell to "B3"
chart.n_series.add("A1:B3", True)
chart.show_data_table = True
# Getting Chart Table
chartTable = chart.chart_data_table
# Setting Chart Table Font Color
chartTable.font.color = Color.red
# Setting Legend Key VisibilityOptions
chartTable.show_legend_key = False
# Saving the Excel file
workbook.save("book1.xls")

```

###  Voir également
* module [`aspose.cells.charts`](..)
