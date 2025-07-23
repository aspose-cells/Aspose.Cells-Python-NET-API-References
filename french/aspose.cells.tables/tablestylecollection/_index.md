---
title: TableStyleCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 60
url: /fr/aspose.cells.tables/tablestylecollection/
is_root: false
---
##  TableStyleCollection classe
Représente tous les styles de table personnalisés.



Le type TableStyleCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [default_table_style_name](/cells/python-net/fr/aspose.cells.tables/tablestylecollection/default_table_style_name) | Obtient et définit le nom de style par défaut de la table.|
| [default_pivot_style_name](/cells/python-net/fr/aspose.cells.tables/tablestylecollection/default_pivot_style_name) | Obtient et définit le nom de style par défaut du tableau croisé dynamique.|
| [capacity](/cells/python-net/fr/aspose.cells.tables/tablestylecollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells.tables/tablestylecollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells.tables/tablestylecollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.tables/tablestylecollection/index_of/#aspose.cells.tables.tablestyle-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.tables/tablestylecollection/index_of/#aspose.cells.tables.tablestyle-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells.tables/tablestylecollection/last_index_of/#aspose.cells.tables.tablestyle) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.tables/tablestylecollection/last_index_of/#aspose.cells.tables.tablestyle-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.tables/tablestylecollection/last_index_of/#aspose.cells.tables.tablestyle-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`add_table_style(self, name)`](/cells/python-net/fr/aspose.cells.tables/tablestylecollection/add_table_style/#str) | Ajoute un style de tableau personnalisé.|
| [`add_pivot_table_style(self, name)`](/cells/python-net/fr/aspose.cells.tables/tablestylecollection/add_pivot_table_style/#str) | Ajoute un style de tableau croisé dynamique personnalisé.|
| [`get(self, name)`](/cells/python-net/fr/aspose.cells.tables/tablestylecollection/get/#str) | Obtient le style de la table par le nom.|
| [`get_builtin_table_style(self, type)`](/cells/python-net/fr/aspose.cells.tables/tablestylecollection/get_builtin_table_style/#aspose.cells.tables.tablestyletype) | Obtient le style de table intégré|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells.tables/tablestylecollection/binary_search/#aspose.cells.tables.tablestyle) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Voir également
* module [`aspose.cells.tables`](..)
