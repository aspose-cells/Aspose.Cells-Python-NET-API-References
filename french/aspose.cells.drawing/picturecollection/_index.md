---
title: PictureCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 440
url: /fr/aspose.cells.drawing/picturecollection/
is_root: false
---
##  PictureCollection classe
Encapsule une collection de [`Picture`](/cells/python-net/fr/aspose.cells.drawing/picture) objets.



Le type PictureCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells.drawing/picturecollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream)`](/cells/python-net/fr/aspose.cells.drawing/picturecollection/add/#int-int-int-int-io.rawiobase) | Ajoute une image à la collection.|
| [`add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name)`](/cells/python-net/fr/aspose.cells.drawing/picturecollection/add/#int-int-int-int-str) | Ajoute une image à la collection.|
| [`add(self, upper_left_row, upper_left_column, stream)`](/cells/python-net/fr/aspose.cells.drawing/picturecollection/add/#int-int-io.rawiobase) | Ajoute une image à la collection.|
| [`add(self, upper_left_row, upper_left_column, file_name)`](/cells/python-net/fr/aspose.cells.drawing/picturecollection/add/#int-int-str) | Ajoute une image à la collection.|
| [`add(self, upper_left_row, upper_left_column, stream, width_scale, height_scale)`](/cells/python-net/fr/aspose.cells.drawing/picturecollection/add/#int-int-io.rawiobase-int-int) | Ajoute une image à la collection.|
| [`add(self, upper_left_row, upper_left_column, file_name, width_scale, height_scale)`](/cells/python-net/fr/aspose.cells.drawing/picturecollection/add/#int-int-str-int-int) | Ajoute une image à la collection.|
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells.drawing/picturecollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells.drawing/picturecollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.drawing/picturecollection/index_of/#aspose.cells.drawing.picture-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.drawing/picturecollection/index_of/#aspose.cells.drawing.picture-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`camera(self, row, column, range)`](/cells/python-net/fr/aspose.cells.drawing/picturecollection/camera/#int-int-str) | Prend une photo de la gamme.|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells.drawing/picturecollection/binary_search/#aspose.cells.drawing.picture) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Exemple

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# get PictureCollection
pictures = workbook.worksheets[0].pictures
# do your business
# Save the excel file.
workbook.save("result.xlsx")

```

###  Voir également
* module [`aspose.cells.drawing`](..)
* classe [`Picture`](/cells/python-net/fr/aspose.cells.drawing/picture)
