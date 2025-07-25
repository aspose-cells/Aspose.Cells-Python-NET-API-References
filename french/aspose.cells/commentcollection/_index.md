---
title: CommentCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 270
url: /fr/aspose.cells/commentcollection/
is_root: false
---
##  CommentCollection classe
Encapsule une collection de [`Comment`](/cells/python-net/fr/aspose.cells/comment) objets.



Le type CommentCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells/commentcollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`add_threaded_comment(self, row, column, text, author)`](/cells/python-net/fr/aspose.cells/commentcollection/add_threaded_comment/#int-int-str-aspose.cells.threadedcommentauthor) | Ajoute un commentaire fileté.|
| [`add_threaded_comment(self, cell_name, text, author)`](/cells/python-net/fr/aspose.cells/commentcollection/add_threaded_comment/#str-str-aspose.cells.threadedcommentauthor) | Ajoute un commentaire fileté.|
| [`get_threaded_comments(self, row, column)`](/cells/python-net/fr/aspose.cells/commentcollection/get_threaded_comments/#int-int) | Obtient les commentaires threadés par index de ligne et de colonne.|
| [`get_threaded_comments(self, cell_name)`](/cells/python-net/fr/aspose.cells/commentcollection/get_threaded_comments/#str) | Obtient les commentaires en fil de discussion par nom de cellule.|
| [`add(self, row, column)`](/cells/python-net/fr/aspose.cells/commentcollection/add/#int-int) | Ajoute un commentaire à la collection.|
| [`add(self, cell_name)`](/cells/python-net/fr/aspose.cells/commentcollection/add/#str) | Ajoute un commentaire à la collection.|
| [`get(self, row, column)`](/cells/python-net/fr/aspose.cells/commentcollection/get/#int-int) | Ajoutez API for Python via .Net. puisque ceci [int, int] n'est pas pris en charge|
| [`get(self, index)`](/cells/python-net/fr/aspose.cells/commentcollection/get/#int) | Obtient l'élément [`Comment`](/cells/python-net/fr/aspose.cells/comment) à l'index spécifié.|
| [`get(self, cell_name)`](/cells/python-net/fr/aspose.cells/commentcollection/get/#str) | Obtient l'élément [`Comment`](/cells/python-net/fr/aspose.cells/comment) dans la cellule spécifiée.|
| [`remove_at(self, cell_name)`](/cells/python-net/fr/aspose.cells/commentcollection/remove_at/#str) | Supprime le commentaire de la cellule spécifique.|
| [`remove_at(self, row, column)`](/cells/python-net/fr/aspose.cells/commentcollection/remove_at/#int-int) | Supprime le commentaire de la cellule spécifique.|
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells/commentcollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells/commentcollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells/commentcollection/index_of/#aspose.cells.comment-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells/commentcollection/index_of/#aspose.cells.comment-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells/commentcollection/binary_search/#aspose.cells.comment) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Exemple

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments

```

###  Voir également
* module [`aspose.cells`](..)
* classe [`Comment`](/cells/python-net/fr/aspose.cells/comment)
