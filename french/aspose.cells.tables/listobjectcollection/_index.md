---
title: ListObjectCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 40
url: /fr/aspose.cells.tables/listobjectcollection/
is_root: false
---
##  ListObjectCollection classe
Représente une collection de [`ListObject`](/cells/python-net/fr/aspose.cells.tables/listobject) objets dans la feuille de calcul.



Le type ListObjectCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells.tables/listobjectcollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`get(self, index)`](/cells/python-net/fr/aspose.cells.tables/listobjectcollection/get/#int) | Ajoutez API for Python via .Net. puisque ceci [int] n'est pas pris en charge|
| [`get(self, table_name)`](/cells/python-net/fr/aspose.cells.tables/listobjectcollection/get/#str) | Ajoutez API for Python via .Net. puisque cette [chaîne] n'est pas prise en charge|
| [`add(self, start_row, start_column, end_row, end_column, has_headers)`](/cells/python-net/fr/aspose.cells.tables/listobjectcollection/add/#int-int-int-int-bool) | Ajoute un ListObject à la feuille de calcul.|
| [`add(self, start_cell, end_cell, has_headers)`](/cells/python-net/fr/aspose.cells.tables/listobjectcollection/add/#str-str-bool) | Ajoute un ListObject à la feuille de calcul.|
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells.tables/listobjectcollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells.tables/listobjectcollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.tables/listobjectcollection/index_of/#aspose.cells.tables.listobject-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.tables/listobjectcollection/index_of/#aspose.cells.tables.listobject-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells.tables/listobjectcollection/last_index_of/#aspose.cells.tables.listobject) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.tables/listobjectcollection/last_index_of/#aspose.cells.tables.listobject-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.tables/listobjectcollection/last_index_of/#aspose.cells.tables.listobject-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`update_column_name(self)`](/cells/python-net/fr/aspose.cells.tables/listobjectcollection/update_column_name/#) | Mettre à jour tous les noms de colonnes des tables.|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells.tables/listobjectcollection/binary_search/#aspose.cells.tables.listobject) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Voir également
* module [`aspose.cells.tables`](..)
* classe [`ListObject`](/cells/python-net/fr/aspose.cells.tables/listobject)
