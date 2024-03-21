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
Encapsule une collection d’objets [`Chart`](/cells/python-net/fr/aspose.cells.charts/chart).



Le type ChartCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells.charts/chartcollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [add](/cells/python-net/fr/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.ChartType-int-int-int-int) | Ajoute un graphique à la collection.|
| [add](/cells/python-net/fr/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.ChartType-str-int-int-int-int) | Ajoute un graphique à la collection.|
| [add](/cells/python-net/fr/aspose.cells.charts/chartcollection/add/#bytes-str-bool-int-int-int-int) | Ajoute un graphique avec un modèle prédéfini.|
| [add](/cells/python-net/fr/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.ChartType-str-bool-int-int-int-int) | Ajoute un graphique à la collection.|
| [get](/cells/python-net/fr/aspose.cells.charts/chartcollection/get/#int) | Ajoutez API for Python via .Net. puisque cet [index int] n'est pas pris en charge|
| [get](/cells/python-net/fr/aspose.cells.charts/chartcollection/get/#str) | Ajoutez API for Python via .Net. puisque ce [string Chart] n'est pas pris en charge|
| [copy_to](/cells/python-net/fr/aspose.cells.charts/chartcollection/copy_to/#list) | Copie la liste entière des tableaux dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste des tableaux cible.|
| [copy_to](/cells/python-net/fr/aspose.cells.charts/chartcollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnels compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [index_of](/cells/python-net/fr/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.Chart-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste du tableau qui s'étend de l'index spécifié au dernier élément.|
| [index_of](/cells/python-net/fr/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.Chart-int-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [last_index_of](/cells/python-net/fr/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.Chart) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste entière du tableau.|
| [last_index_of](/cells/python-net/fr/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.Chart-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste du tableau qui s'étend du premier élément à l'index spécifié.|
| [last_index_of](/cells/python-net/fr/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.Chart-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [add_floating_chart](/cells/python-net/fr/aspose.cells.charts/chartcollection/add_floating_chart/#aspose.cells.charts.ChartType-int-int-int-int) | Ajoute un graphique à la collection.|
| [binary_search](/cells/python-net/fr/aspose.cells.charts/chartcollection/binary_search/#aspose.cells.charts.Chart) | Recherche un élément dans toute la liste de tableaux triés à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Exemple

```python
from aspose.cells import Workbook

workbook = Workbook()
charts = workbook.worksheets[0].charts

```

###  Voir également
* module [`aspose.cells.charts`](..)
* classe [`Chart`](/cells/python-net/fr/aspose.cells.charts/chart)
