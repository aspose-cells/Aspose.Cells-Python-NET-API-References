---
title: CellWatchCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 170
url: /fr/aspose.cells/cellwatchcollection/
is_root: false
---
##  CellWatchCollection classe
Représente la collection de cellules de cette feuille de calcul surveillée dans la "fenêtre de surveillance".



Le type CellWatchCollection expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [CellWatchCollection()](/cells/python-net/fr/aspose.cells/cellwatchcollection/__init__/#) | Construit une nouvelle instance de CellWatchCollection|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells/cellwatchcollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableau peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [add(row, column)](/cells/python-net/fr/aspose.cells/cellwatchcollection/add/#int-int) | Ajoute [CellWatch](/cells/python-net/fr/aspose.cells/cellwatch) avec ligne et colonne.|
| [add(cell_name)](/cells/python-net/fr/aspose.cells/cellwatchcollection/add/#str) | Ajoute [CellWatch](/cells/python-net/fr/aspose.cells/cellwatch) avec le nom de la cellule.|
| [copy_to(array)](/cells/python-net/fr/aspose.cells/cellwatchcollection/copy_to/#list) | Copie la totalité de la liste de tableaux dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [copy_to(index, array, array_index, count)](/cells/python-net/fr/aspose.cells/cellwatchcollection/copy_to/#int-list-int-int) |Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [index_of(item, index)](/cells/python-net/fr/aspose.cells/cellwatchcollection/index_of/#CellWatch-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [index_of(item, index, count)](/cells/python-net/fr/aspose.cells/cellwatchcollection/index_of/#CellWatch-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [last_index_of(item)](/cells/python-net/fr/aspose.cells/cellwatchcollection/last_index_of/#CellWatch) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste complète du tableau.|
| [last_index_of(item, index)](/cells/python-net/fr/aspose.cells/cellwatchcollection/last_index_of/#CellWatch-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [last_index_of(item, index, count)](/cells/python-net/fr/aspose.cells/cellwatchcollection/last_index_of/#CellWatch-int-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre d'éléments spécifié et se termine à l'index spécifié.|
| [binary_search(item)](/cells/python-net/fr/aspose.cells/cellwatchcollection/binary_search/#CellWatch) | Recherche un élément dans toute la liste de tableaux triés à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



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
* module [aspose.cells](..)
* classe [CellWatch](/cells/python-net/fr/aspose.cells/cellwatch)
