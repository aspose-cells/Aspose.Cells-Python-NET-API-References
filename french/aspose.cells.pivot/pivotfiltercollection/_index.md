---
title: PivotFilterCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 150
url: /fr/aspose.cells.pivot/pivotfiltercollection/
is_root: false
---
##  PivotFilterCollection classe
Représente une collection de tous les objets PivotFilter



Le type PivotFilterCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells.pivot/pivotfiltercollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells.pivot/pivotfiltercollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells.pivot/pivotfiltercollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.pivot/pivotfiltercollection/index_of/#aspose.cells.pivot.pivotfilter-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.pivot/pivotfiltercollection/index_of/#aspose.cells.pivot.pivotfilter-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells.pivot/pivotfiltercollection/last_index_of/#aspose.cells.pivot.pivotfilter) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.pivot/pivotfiltercollection/last_index_of/#aspose.cells.pivot.pivotfilter-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.pivot/pivotfiltercollection/last_index_of/#aspose.cells.pivot.pivotfilter-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`add(self, field_index, type)`](/cells/python-net/fr/aspose.cells.pivot/pivotfiltercollection/add/#int-aspose.cells.pivot.pivotfiltertype) | Ajoute un objet PivotFilter au type spécifique|
| [`add_top_10_filter(self, base_field_index, value_field_index, type, is_top, item_count)`](/cells/python-net/fr/aspose.cells.pivot/pivotfiltercollection/add_top_10_filter/#int-int-aspose.cells.pivot.pivotfiltertype-bool-int) | Filtre par valeurs du champ pivot de données.|
| [`add_value_filter(self, base_field_index, value_field_index, type, value1, value2)`](/cells/python-net/fr/aspose.cells.pivot/pivotfiltercollection/add_value_filter/#int-int-aspose.cells.pivot.pivotfiltertype-float-float) | Filtre par valeurs du champ pivot de données.|
| [`add_label_filter(self, base_field_index, type, label1, label2)`](/cells/python-net/fr/aspose.cells.pivot/pivotfiltercollection/add_label_filter/#int-aspose.cells.pivot.pivotfiltertype-str-str) | Filtre par légendes de champ pivot de ligne ou de colonne.|
| [`add_date_filter(self, base_field_index, type, date_time1, date_time2)`](/cells/python-net/fr/aspose.cells.pivot/pivotfiltercollection/add_date_filter/#int-aspose.cells.pivot.pivotfiltertype-datetime-datetime) | Filtre par paramètre de date du champ pivot de ligne ou de colonne.|
| [`clear_filter(self, field_index)`](/cells/python-net/fr/aspose.cells.pivot/pivotfiltercollection/clear_filter/#int) | Effacer le filtre croisé dynamique du champ croisé dynamique spécifique|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells.pivot/pivotfiltercollection/binary_search/#aspose.cells.pivot.pivotfilter) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Voir également
* module [`aspose.cells.pivot`](..)
