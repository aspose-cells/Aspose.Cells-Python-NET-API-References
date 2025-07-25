---
title: ChartCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 60
url: /fr/aspose.cells.charts/chartcollection/
is_root: false
---
##  ChartCollection classe
Encapsule une collection de [`Chart`](/cells/python-net/fr/aspose.cells.charts/chart) objets.



Le type ChartCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells.charts/chartcollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`add(self, type, upper_left_row, upper_left_column, lower_right_row, lower_right_column)`](/cells/python-net/fr/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-int-int-int-int) | Ajoute un graphique à la collection.|
| [`add(self, type, data_range, top_row, left_column, right_row, bottom_column)`](/cells/python-net/fr/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-str-int-int-int-int) | Ajoute un graphique à la collection.|
| [`add(self, data, data_range, is_vertical, top_row, left_column, right_row, bottom_column)`](/cells/python-net/fr/aspose.cells.charts/chartcollection/add/#bytes-str-bool-int-int-int-int) | Ajoute un graphique avec un modèle prédéfini.|
| [`add(self, type, data_range, is_vertical, top_row, left_column, right_row, bottom_column)`](/cells/python-net/fr/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-str-bool-int-int-int-int) | Ajoute un graphique à la collection.|
| [`get(self, index)`](/cells/python-net/fr/aspose.cells.charts/chartcollection/get/#int) | Ajoutez API for Python via .Net. puisque cet [index int] n'est pas pris en charge|
| [`get(self, name)`](/cells/python-net/fr/aspose.cells.charts/chartcollection/get/#str) | Ajoutez API for Python via .Net. puisque ce [chaîne de caractères] n'est pas pris en charge|
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells.charts/chartcollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells.charts/chartcollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.chart-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.chart-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`add_floating_chart(self, type, left, top, width, height)`](/cells/python-net/fr/aspose.cells.charts/chartcollection/add_floating_chart/#aspose.cells.charts.charttype-int-int-int-int) | Ajoute un graphique à la collection.|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells.charts/chartcollection/binary_search/#aspose.cells.charts.chart) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Exemple

```python
from aspose.cells import Workbook

workbook = Workbook()
charts = workbook.worksheets[0].charts

```

###  Voir également
* module [`aspose.cells.charts`](..)
* classe [`Chart`](/cells/python-net/fr/aspose.cells.charts/chart)
