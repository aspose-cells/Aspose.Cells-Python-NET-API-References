---
title: CellWatchCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 150
url: /fr/aspose.cells/cellwatchcollection/
is_root: false
---
##  CellWatchCollection classe
Représente l'ensemble des cellules de cette feuille de calcul surveillées dans la « fenêtre de surveillance ».



Le type CellWatchCollection expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self)`](/cells/python-net/fr/aspose.cells/cellwatchcollection/__init__/#) | Construit une nouvelle instance de CellWatchCollection|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells/cellwatchcollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`add(self, row, column)`](/cells/python-net/fr/aspose.cells/cellwatchcollection/add/#int-int) | Ajoute [`CellWatch`](/cells/python-net/fr/aspose.cells/cellwatch) avec ligne et colonne.|
| [`add(self, cell_name)`](/cells/python-net/fr/aspose.cells/cellwatchcollection/add/#str) | Ajoute [`CellWatch`](/cells/python-net/fr/aspose.cells/cellwatch) avec le nom de la cellule.|
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells/cellwatchcollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells/cellwatchcollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells/cellwatchcollection/index_of/#aspose.cells.cellwatch-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells/cellwatchcollection/index_of/#aspose.cells.cellwatch-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`get(self, cell_name)`](/cells/python-net/fr/aspose.cells/cellwatchcollection/get/#str) | Obtient et définit [`CellWatch`](/cells/python-net/fr/aspose.cells/cellwatch) par le nom de la cellule.|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells/cellwatchcollection/binary_search/#aspose.cells.cellwatch) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Exemple

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet.
sheet = workbook.worksheets[0]
#  Add Cell Watch Item into the watch window
sheet.cell_watches.add("B2")

```

###  Voir également
* module [`aspose.cells`](..)
* classe [`CellWatch`](/cells/python-net/fr/aspose.cells/cellwatch)
