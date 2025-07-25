---
title: CheckBoxCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 100
url: /fr/aspose.cells.drawing/checkboxcollection/
is_root: false
---
##  CheckBoxCollection classe
Représente une collection de [`CheckBox`](/cells/python-net/fr/aspose.cells.drawing/checkbox) objets dans une feuille de calcul.



Le type CheckBoxCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells.drawing/checkboxcollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells.drawing/checkboxcollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells.drawing/checkboxcollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.drawing/checkboxcollection/index_of/#aspose.cells.drawing.checkbox-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.drawing/checkboxcollection/index_of/#aspose.cells.drawing.checkbox-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells.drawing/checkboxcollection/last_index_of/#aspose.cells.drawing.checkbox) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.drawing/checkboxcollection/last_index_of/#aspose.cells.drawing.checkbox-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.drawing/checkboxcollection/last_index_of/#aspose.cells.drawing.checkbox-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`add(self, upper_left_row, upper_left_column, height, width)`](/cells/python-net/fr/aspose.cells.drawing/checkboxcollection/add/#int-int-int-int) | Ajoute une case à cocher à la collection.|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells.drawing/checkboxcollection/binary_search/#aspose.cells.drawing.checkbox) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Exemple

```python
from aspose.cells import Workbook

# Create a new Workbook.
workbook = Workbook()
# Get the first worksheet in the workbook.
sheet = workbook.worksheets[0]
index = sheet.check_boxes.add(15, 15, 20, 100)
checkBox = sheet.check_boxes[index]
checkBox.text = "Check Box 1"

```

###  Voir également
* module [`aspose.cells.drawing`](..)
* classe [`CheckBox`](/cells/python-net/fr/aspose.cells.drawing/checkbox)
