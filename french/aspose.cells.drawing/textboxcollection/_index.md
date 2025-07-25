---
title: TextBoxCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 670
url: /fr/aspose.cells.drawing/textboxcollection/
is_root: false
---
##  TextBoxCollection classe
Encapsule une collection de [`TextBox`](/cells/python-net/fr/aspose.cells.drawing/textbox) objets.



Le type TextBoxCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells.drawing/textboxcollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells.drawing/textboxcollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells.drawing/textboxcollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.drawing/textboxcollection/index_of/#aspose.cells.drawing.textbox-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.drawing/textboxcollection/index_of/#aspose.cells.drawing.textbox-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells.drawing/textboxcollection/last_index_of/#aspose.cells.drawing.textbox) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.drawing/textboxcollection/last_index_of/#aspose.cells.drawing.textbox-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.drawing/textboxcollection/last_index_of/#aspose.cells.drawing.textbox-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`get(self, name)`](/cells/python-net/fr/aspose.cells.drawing/textboxcollection/get/#str) | Obtient l'élément [`TextBox`](/cells/python-net/fr/aspose.cells.drawing/textbox) par le nom.|
| [`add(self, upper_left_row, upper_left_column, height, width)`](/cells/python-net/fr/aspose.cells.drawing/textboxcollection/add/#int-int-int-int) | Ajoute une zone de texte à la collection.|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells.drawing/textboxcollection/binary_search/#aspose.cells.drawing.textbox) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Exemple

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# get collection object
textBoxCollection = workbook.worksheets[0].text_boxes
# add a textbox
textBoxCollection.add(1, 1, 50, 100)
for tbox in textBoxCollection:
    pass

```

###  Voir également
* module [`aspose.cells.drawing`](..)
* classe [`TextBox`](/cells/python-net/fr/aspose.cells.drawing/textbox)
