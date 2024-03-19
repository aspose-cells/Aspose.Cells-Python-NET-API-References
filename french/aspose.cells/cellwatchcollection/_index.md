---
title: CellWatchCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 180
url: /fr/aspose.cells/cellwatchcollection/
is_root: false
---
##  CellWatchCollection classe
Représente la collection de cellules de cette feuille de calcul surveillée dans la « fenêtre de surveillance ».



Le type CellWatchCollection expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [__init__](/cells/python-net/fr/aspose.cells/cellwatchcollection/__init__/#) | Construit une nouvelle instance de CellWatchCollection|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells/cellwatchcollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [add](/cells/python-net/fr/aspose.cells/cellwatchcollection/add/#int-int) | Ajoute [`CellWatch`](/cells/python-net/fr/aspose.cells/cellwatch) avec ligne et colonne.|
| [add](/cells/python-net/fr/aspose.cells/cellwatchcollection/add/#str) | Ajoute [`CellWatch`](/cells/python-net/fr/aspose.cells/cellwatch) avec le nom de la cellule.|
| [copy_to](/cells/python-net/fr/aspose.cells/cellwatchcollection/copy_to/#list) | Copie la liste entière des tableaux dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste des tableaux cible.|
| [copy_to](/cells/python-net/fr/aspose.cells/cellwatchcollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnels compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [index_of](/cells/python-net/fr/aspose.cells/cellwatchcollection/index_of/#aspose.cells.CellWatch-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste du tableau qui s'étend de l'index spécifié au dernier élément.|
| [index_of](/cells/python-net/fr/aspose.cells/cellwatchcollection/index_of/#aspose.cells.CellWatch-int-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [last_index_of](/cells/python-net/fr/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.CellWatch) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste entière du tableau.|
| [last_index_of](/cells/python-net/fr/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.CellWatch-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste du tableau qui s'étend du premier élément à l'index spécifié.|
| [last_index_of](/cells/python-net/fr/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.CellWatch-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [binary_search](/cells/python-net/fr/aspose.cells/cellwatchcollection/binary_search/#aspose.cells.CellWatch) | Recherche un élément dans toute la liste de tableaux triés à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



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
