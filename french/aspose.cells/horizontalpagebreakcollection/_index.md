---
title: HorizontalPageBreakCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 770
url: /fr/aspose.cells/horizontalpagebreakcollection/
is_root: false
---
##  HorizontalPageBreakCollection classe
Encapsule une collection de [`HorizontalPageBreak`](/cells/python-net/fr/aspose.cells/horizontalpagebreak) objets.



Le type HorizontalPageBreakCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells/horizontalpagebreakcollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`add(self, row, start_column, end_column)`](/cells/python-net/fr/aspose.cells/horizontalpagebreakcollection/add/#int-int-int) | Ajoute un saut de page horizontal à la collection.|
| [`add(self, row)`](/cells/python-net/fr/aspose.cells/horizontalpagebreakcollection/add/#int) | Ajoute un saut de page horizontal à la collection.|
| [`add(self, row, column)`](/cells/python-net/fr/aspose.cells/horizontalpagebreakcollection/add/#int-int) | Ajoute un saut de page horizontal à la collection.|
| [`add(self, cell_name)`](/cells/python-net/fr/aspose.cells/horizontalpagebreakcollection/add/#str) | Ajoute un saut de page horizontal à la collection.|
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells/horizontalpagebreakcollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells/horizontalpagebreakcollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells/horizontalpagebreakcollection/index_of/#aspose.cells.horizontalpagebreak-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells/horizontalpagebreakcollection/index_of/#aspose.cells.horizontalpagebreak-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.horizontalpagebreak) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.horizontalpagebreak-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.horizontalpagebreak-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`get(self, cell_name)`](/cells/python-net/fr/aspose.cells/horizontalpagebreakcollection/get/#str) | Obtient l'élément [`HorizontalPageBreak`](/cells/python-net/fr/aspose.cells/horizontalpagebreak) avec le nom de cellule spécifié.|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells/horizontalpagebreakcollection/binary_search/#aspose.cells.horizontalpagebreak) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Exemple

```python
from aspose.cells import Workbook

excel = Workbook()
# Add a pagebreak at G5
excel.worksheets[0].horizontal_page_breaks.add("G5")
excel.worksheets[0].vertical_page_breaks.add("G5")

```

###  Voir également
* module [`aspose.cells`](..)
* classe [`HorizontalPageBreak`](/cells/python-net/fr/aspose.cells/horizontalpagebreak)
