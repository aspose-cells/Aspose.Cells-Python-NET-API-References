---
title: NameCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1010
url: /fr/aspose.cells/namecollection/
is_root: false
---
##  NameCollection classe
Représente une collection de tous les [`Name`](/cells/python-net/fr/aspose.cells/name) objets de la feuille de calcul.



Le type NameCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells/namecollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`get(self, index)`](/cells/python-net/fr/aspose.cells/namecollection/get/#int) | Ajoutez API for Python via .Net. puisque cet [index int] n'est pas pris en charge|
| [`get(self, text)`](/cells/python-net/fr/aspose.cells/namecollection/get/#str) | Ajoutez API for Python via .Net. puisque cette [chaîne de texte] n'est pas prise en charge|
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells/namecollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells/namecollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells/namecollection/index_of/#aspose.cells.name-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells/namecollection/index_of/#aspose.cells.name-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells/namecollection/last_index_of/#aspose.cells.name) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells/namecollection/last_index_of/#aspose.cells.name-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells/namecollection/last_index_of/#aspose.cells.name-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`add(self, text)`](/cells/python-net/fr/aspose.cells/namecollection/add/#str) | Définit un nouveau nom.|
| [`filter(self, type, sheet_index)`](/cells/python-net/fr/aspose.cells/namecollection/filter/#aspose.cells.namescopetype-int) | Obtient tous les noms définis par portée.|
| [`remove_a_name(self, text)`](/cells/python-net/fr/aspose.cells/namecollection/remove_a_name/#str) | Supprimer le nom.|
| [`remove_names_by_array(self, names)`](/cells/python-net/fr/aspose.cells/namecollection/remove_names_by_array/#list) | Supprimer un tableau de noms|
| [`remove_duplicate_names(self)`](/cells/python-net/fr/aspose.cells/namecollection/remove_duplicate_names/#) | Supprimer les noms définis en double|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells/namecollection/binary_search/#aspose.cells.name) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Voir également
* module [`aspose.cells`](..)
* classe [`Name`](/cells/python-net/fr/aspose.cells/name)
