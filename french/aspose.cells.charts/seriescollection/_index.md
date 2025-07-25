---
title: SeriesCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 250
url: /fr/aspose.cells.charts/seriescollection/
is_root: false
---
##  SeriesCollection classe
Encapsule une collection de [`Series`](/cells/python-net/fr/aspose.cells.charts/series) objets.



Le type SeriesCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [category_data](/cells/python-net/fr/aspose.cells.charts/seriescollection/category_data) | Obtient ou définit la plage de valeurs de l'axe des catégories.<br/> Il peut s'agir d'une plage de cellules (par exemple, « d1:e10 »),<br/> ou une séquence de valeurs (telle que « {2,6,8,10} »).|
| [second_category_data](/cells/python-net/fr/aspose.cells.charts/seriescollection/second_category_data) | Obtient ou définit la plage de valeurs de l'axe de la deuxième catégorie.<br/> Il peut s'agir d'une plage de cellules (par exemple, « d1:e10 »),<br/> ou une séquence de valeurs (telle que « {2,6,8,10} »).<br/> Effets uniquement lorsque certaines séries ASeries sont tracées sur le deuxième axe.|
| [is_color_varied](/cells/python-net/fr/aspose.cells.charts/seriescollection/is_color_varied) | Représente si la couleur des points est variée.|
| [capacity](/cells/python-net/fr/aspose.cells.charts/seriescollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`add(self, area, is_vertical)`](/cells/python-net/fr/aspose.cells.charts/seriescollection/add/#str-bool) | Ajoute la collection [`Series`](/cells/python-net/fr/aspose.cells.charts/series) à un graphique.|
| [`add(self, area, is_vertical, check_labels)`](/cells/python-net/fr/aspose.cells.charts/seriescollection/add/#str-bool-bool) | Ajoute la collection [`Series`](/cells/python-net/fr/aspose.cells.charts/series) à un graphique.|
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells.charts/seriescollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells.charts/seriescollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.charts/seriescollection/index_of/#aspose.cells.charts.series-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.charts/seriescollection/index_of/#aspose.cells.charts.series-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.series) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.series-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.series-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`get_series_by_order(self, order)`](/cells/python-net/fr/aspose.cells.charts/seriescollection/get_series_by_order/#int) | Obtient l'élément [`Series`](/cells/python-net/fr/aspose.cells.charts/series) par ordre.|
| [`change_series_order(self, source_index, dest_index)`](/cells/python-net/fr/aspose.cells.charts/seriescollection/change_series_order/#int-int) | Change directement l'ordre des deux séries.|
| [`swap_series(self, source_index, dest_index)`](/cells/python-net/fr/aspose.cells.charts/seriescollection/swap_series/#int-int) | Change directement l'ordre des deux séries.|
| [`set_series_names(self, start_index, area, is_vertical)`](/cells/python-net/fr/aspose.cells.charts/seriescollection/set_series_names/#int-str-bool) | Définit le nom de toutes les séries du graphique.|
| [`add_r1c1(self, area, is_vertical)`](/cells/python-net/fr/aspose.cells.charts/seriescollection/add_r1c1/#str-bool) | Ajoute la collection [`Series`](/cells/python-net/fr/aspose.cells.charts/series) à un graphique.|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells.charts/seriescollection/binary_search/#aspose.cells.charts.series) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Exemple

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Excel object
sheetIndex = workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[sheetIndex]
# Adding a sample value to "A1" cell
worksheet.cells.get("A1").put_value(50)
# Adding a sample value to "A2" cell
worksheet.cells.get("A2").put_value(100)
# Adding a sample value to "A3" cell
worksheet.cells.get("A3").put_value(150)
# Adding a sample value to "A4" cell
worksheet.cells.get("A4").put_value(200)
# Adding a sample value to "B1" cell
worksheet.cells.get("B1").put_value(60)
# Adding a sample value to "B2" cell
worksheet.cells.get("B2").put_value(32)
# Adding a sample value to "B3" cell
worksheet.cells.get("B3").put_value(50)
# Adding a sample value to "B4" cell
worksheet.cells.get("B4").put_value(40)
# Adding a sample value to "C1" cell as category data
worksheet.cells.get("C1").put_value("Q1")
# Adding a sample value to "C2" cell as category data
worksheet.cells.get("C2").put_value("Q2")
# Adding a sample value to "C3" cell as category data
worksheet.cells.get("C3").put_value("Y1")
# Adding a sample value to "C4" cell as category data
worksheet.cells.get("C4").put_value("Y2")
# Adding a chart to the worksheet
chartIndex = worksheet.charts.add(ChartType.COLUMN, 5, 0, 15, 5)
# Accessing the instance of the newly added chart
chart = worksheet.charts[chartIndex]
# Adding NSeries (chart data source) to the chart ranging from "A1" cell to "B4"
chart.n_series.add("A1:B4", True)
# Setting the data source for the category data of NSeries
chart.n_series.category_data = "C1:C4"
# Saving the Excel file
workbook.save("book1.xls")

```

###  Voir également
* module [`aspose.cells.charts`](..)
* classe [`Series`](/cells/python-net/fr/aspose.cells.charts/series)
