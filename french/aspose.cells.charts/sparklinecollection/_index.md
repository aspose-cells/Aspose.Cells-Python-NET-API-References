---
title: SparklineCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 280
url: /fr/aspose.cells.charts/sparklinecollection/
is_root: false
---
##  SparklineCollection classe
Encapsule une collection de [`Sparkline`](/cells/python-net/fr/aspose.cells.charts/sparkline) objets.



Le type SparklineCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells.charts/sparklinecollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells.charts/sparklinecollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells.charts/sparklinecollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.charts/sparklinecollection/index_of/#aspose.cells.charts.sparkline-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.charts/sparklinecollection/index_of/#aspose.cells.charts.sparkline-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells.charts/sparklinecollection/last_index_of/#aspose.cells.charts.sparkline) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.charts/sparklinecollection/last_index_of/#aspose.cells.charts.sparkline-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.charts/sparklinecollection/last_index_of/#aspose.cells.charts.sparkline-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`add(self, data_range, row, column)`](/cells/python-net/fr/aspose.cells.charts/sparklinecollection/add/#str-int-int) | Ajoutez un sparkline.|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells.charts/sparklinecollection/binary_search/#aspose.cells.charts.sparkline) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



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
idx = sheet.sparkline_groups.add(SparklineType.LINE, sheet.name + "!A1:D1", False, ca)
group = sheet.sparkline_groups[idx]
group.sparklines.add(sheet.name + "!A1:D1", 0, 4)
book.save("output.xlsx", SaveFormat.XLSX)

```

###  Voir également
* module [`aspose.cells.charts`](..)
* classe [`Sparkline`](/cells/python-net/fr/aspose.cells.charts/sparkline)
