---
title: SparklineGroupCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 300
url: /fr/aspose.cells.charts/sparklinegroupcollection/
is_root: false
---
##  SparklineGroupCollection classe
Encapsule une collection de [`SparklineGroup`](/cells/python-net/fr/aspose.cells.charts/sparklinegroup) objets.



Le type SparklineGroupCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells.charts/sparklinegroupcollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`add(self, type)`](/cells/python-net/fr/aspose.cells.charts/sparklinegroupcollection/add/#aspose.cells.charts.sparklinetype) | Ajoute un [`SparklineGroup`](/cells/python-net/fr/aspose.cells.charts/sparklinegroup) avec un [`Sparkline`](/cells/python-net/fr/aspose.cells.charts/sparkline) à la collection.|
| [`add(self, type, data_range, is_vertical, location_range)`](/cells/python-net/fr/aspose.cells.charts/sparklinegroupcollection/add/#aspose.cells.charts.sparklinetype-str-bool-aspose.cells.cellarea) | Ajoute un [`SparklineGroup`](/cells/python-net/fr/aspose.cells.charts/sparklinegroup) avec [`Sparkline`](/cells/python-net/fr/aspose.cells.charts/sparkline) à la collection.|
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells.charts/sparklinegroupcollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells.charts/sparklinegroupcollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.charts/sparklinegroupcollection/index_of/#aspose.cells.charts.sparklinegroup-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.charts/sparklinegroupcollection/index_of/#aspose.cells.charts.sparklinegroup-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`clear_sparklines(self, cell_area)`](/cells/python-net/fr/aspose.cells.charts/sparklinegroupcollection/clear_sparklines/#aspose.cells.cellarea) | Efface les sparklines qui se trouvent à l'intérieur d'une zone de cellules.|
| [`clear_sparkline_groups(self, cell_area)`](/cells/python-net/fr/aspose.cells.charts/sparklinegroupcollection/clear_sparkline_groups/#aspose.cells.cellarea) | Efface les groupes de sparklines qui chevauchent une zone de cellules.|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells.charts/sparklinegroupcollection/binary_search/#aspose.cells.charts.sparklinegroup) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Exemple

```python
from aspose.cells import CellArea, SaveFormat, Workbook
from aspose.cells.charts import SparklineType

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
book.save("output.xlsx", SaveFormat.XLSX)

```

###  Voir également
* module [`aspose.cells.charts`](..)
* classe [`Sparkline`](/cells/python-net/fr/aspose.cells.charts/sparkline)
* classe [`SparklineGroup`](/cells/python-net/fr/aspose.cells.charts/sparklinegroup)
