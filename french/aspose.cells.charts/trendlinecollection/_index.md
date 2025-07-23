---
title: TrendlineCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 350
url: /fr/aspose.cells.charts/trendlinecollection/
is_root: false
---
##  TrendlineCollection classe
Représente une collection de tous les [`Trendline`](/cells/python-net/fr/aspose.cells.charts/trendline) objets pour la série de données spécifiée.



Le type TrendlineCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells.charts/trendlinecollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`add(self, type)`](/cells/python-net/fr/aspose.cells.charts/trendlinecollection/add/#aspose.cells.charts.trendlinetype) | Ajoute un objet [`Trendline`](/cells/python-net/fr/aspose.cells.charts/trendline) à cette collection avec le type spécifié.|
| [`add(self, type, name)`](/cells/python-net/fr/aspose.cells.charts/trendlinecollection/add/#aspose.cells.charts.trendlinetype-str) | Ajoute un objet [`Trendline`](/cells/python-net/fr/aspose.cells.charts/trendline) à cette collection avec le type et le nom spécifiés.|
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells.charts/trendlinecollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells.charts/trendlinecollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.charts/trendlinecollection/index_of/#aspose.cells.charts.trendline-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.charts/trendlinecollection/index_of/#aspose.cells.charts.trendline-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.trendline) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.trendline-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.trendline-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells.charts/trendlinecollection/binary_search/#aspose.cells.charts.trendline) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Exemple

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType, TrendlineType
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Excel object
sheetIndex = workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[sheetIndex]
worksheet.cells.get("A1").put_value(50)
worksheet.cells.get("A2").put_value(100)
worksheet.cells.get("A3").put_value(150)
worksheet.cells.get("A4").put_value(200)
worksheet.cells.get("B1").put_value(60)
worksheet.cells.get("B2").put_value(32)
worksheet.cells.get("B3").put_value(50)
worksheet.cells.get("B4").put_value(40)
# Adding a chart to the worksheet
chartIndex = workbook.worksheets[0].charts.add(ChartType.COLUMN, 3, 3, 15, 10)
chart = workbook.worksheets[0].charts[chartIndex]
chart.n_series.add("A1:a3", True)
chart.n_series[0].trend_lines.add(TrendlineType.LINEAR, "MyTrendLine")
line = chart.n_series[0].trend_lines[0]
line.display_equation = True
line.display_r_squared = True
line.color = Color.red

```

###  Voir également
* module [`aspose.cells.charts`](..)
* classe [`Trendline`](/cells/python-net/fr/aspose.cells.charts/trendline)
