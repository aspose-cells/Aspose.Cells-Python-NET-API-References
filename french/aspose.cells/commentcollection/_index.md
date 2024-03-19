---
title: CommentCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 300
url: /fr/aspose.cells/commentcollection/
is_root: false
---
##  CommentCollection classe
Encapsule une collection d’objets [`Comment`](/cells/python-net/fr/aspose.cells/comment).



Le type CommentCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells/commentcollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [add_threaded_comment](/cells/python-net/fr/aspose.cells/commentcollection/add_threaded_comment/#int-int-str-aspose.cells.ThreadedCommentAuthor) | Ajoute un commentaire dans le fil de discussion.|
| [add_threaded_comment](/cells/python-net/fr/aspose.cells/commentcollection/add_threaded_comment/#str-str-aspose.cells.ThreadedCommentAuthor) | Ajoute un commentaire dans le fil de discussion.|
| [get_threaded_comments](/cells/python-net/fr/aspose.cells/commentcollection/get_threaded_comments/#int-int) | Obtient les commentaires du fil de discussion par index de ligne et de colonne.|
| [get_threaded_comments](/cells/python-net/fr/aspose.cells/commentcollection/get_threaded_comments/#str) |Obtient les commentaires du fil de discussion par nom de cellule.|
| [add](/cells/python-net/fr/aspose.cells/commentcollection/add/#int-int) | Ajoute un commentaire à la collection.|
| [add](/cells/python-net/fr/aspose.cells/commentcollection/add/#str) | Ajoute un commentaire à la collection.|
| [remove_at](/cells/python-net/fr/aspose.cells/commentcollection/remove_at/#str) | Supprime le commentaire de la cellule spécifique.|
| [remove_at](/cells/python-net/fr/aspose.cells/commentcollection/remove_at/#int-int) | Supprime le commentaire de la cellule spécifique.|
| [copy_to](/cells/python-net/fr/aspose.cells/commentcollection/copy_to/#list) | Copie la liste entière des tableaux dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste des tableaux cible.|
| [copy_to](/cells/python-net/fr/aspose.cells/commentcollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnels compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [index_of](/cells/python-net/fr/aspose.cells/commentcollection/index_of/#aspose.cells.Comment-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste du tableau qui s'étend de l'index spécifié au dernier élément.|
| [index_of](/cells/python-net/fr/aspose.cells/commentcollection/index_of/#aspose.cells.Comment-int-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [last_index_of](/cells/python-net/fr/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste entière du tableau.|
| [last_index_of](/cells/python-net/fr/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste du tableau qui s'étend du premier élément à l'index spécifié.|
| [last_index_of](/cells/python-net/fr/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [binary_search](/cells/python-net/fr/aspose.cells/commentcollection/binary_search/#aspose.cells.Comment) | Recherche un élément dans toute la liste de tableaux triés à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Exemple

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments

```

###  Voir également
* module [`aspose.cells`](..)
* classe [`Comment`](/cells/python-net/fr/aspose.cells/comment)
