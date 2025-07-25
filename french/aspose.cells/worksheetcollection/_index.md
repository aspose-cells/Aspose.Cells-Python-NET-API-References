---
title: WorksheetCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1610
url: /fr/aspose.cells/worksheetcollection/
is_root: false
---
##  WorksheetCollection classe
Encapsule une collection de [`Worksheet`](/cells/python-net/fr/aspose.cells/worksheet) objets.



Le type WorksheetCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [web_extension_task_panes](/cells/python-net/fr/aspose.cells/worksheetcollection/web_extension_task_panes) | Obtient la liste des volets de tâches.|
| [web_extensions](/cells/python-net/fr/aspose.cells/worksheetcollection/web_extensions) | Obtient la liste des volets de tâches.|
| [threaded_comment_authors](/cells/python-net/fr/aspose.cells/worksheetcollection/threaded_comment_authors) | Obtient la liste des auteurs de commentaires en fil de discussion.|
| [is_refresh_all_connections](/cells/python-net/fr/aspose.cells/worksheetcollection/is_refresh_all_connections) | Indique si toutes les connexions doivent être actualisées lors de l'ouverture du fichier dans MS Excel.|
| [names](/cells/python-net/fr/aspose.cells/worksheetcollection/names) | Obtient la collection de tous les objets Name dans la feuille de calcul.|
| [active_sheet_name](/cells/python-net/fr/aspose.cells/worksheetcollection/active_sheet_name) | Représente le nom de la feuille de calcul active lorsque la feuille de calcul est ouverte.|
| [active_sheet_index](/cells/python-net/fr/aspose.cells/worksheetcollection/active_sheet_index) | Représente l'index de la feuille de calcul active lorsque la feuille de calcul est ouverte.|
| [dxfs](/cells/python-net/fr/aspose.cells/worksheetcollection/dxfs) | Obtient les enregistrements de formatage différentiel maître.|
| [xml_maps](/cells/python-net/fr/aspose.cells/worksheetcollection/xml_maps) | Obtient et définit les cartes XML dans le classeur.|
| [built_in_document_properties](/cells/python-net/fr/aspose.cells/worksheetcollection/built_in_document_properties) | Renvoie une collection [`DocumentProperty`](/cells/python-net/fr/aspose.cells.properties/documentproperty) qui représente toutes les propriétés de document intégrées de la feuille de calcul.|
| [custom_document_properties](/cells/python-net/fr/aspose.cells/worksheetcollection/custom_document_properties) | Renvoie une collection [`DocumentProperty`](/cells/python-net/fr/aspose.cells.properties/documentproperty) qui représente toutes les propriétés de document personnalisées de la feuille de calcul.|
| [ole_size](/cells/python-net/fr/aspose.cells/worksheetcollection/ole_size) | Obtient et définit la taille affichée lorsque le fichier Workbook est utilisé comme objet Ole.|
| [external_links](/cells/python-net/fr/aspose.cells/worksheetcollection/external_links) |Représente les liens externes dans un classeur.|
| [table_styles](/cells/python-net/fr/aspose.cells/worksheetcollection/table_styles) | Obtient l'objet [`WorksheetCollection.table_styles`](/cells/python-net/fr/aspose.cells/worksheetcollection#table_styles).|
| [revision_logs](/cells/python-net/fr/aspose.cells/worksheetcollection/revision_logs) | Représente les journaux de révision.|
| [sensitivity_labels](/cells/python-net/fr/aspose.cells/worksheetcollection/sensitivity_labels) | Représente toutes les étiquettes de sensibilité.|
| [capacity](/cells/python-net/fr/aspose.cells/worksheetcollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|



Obtient l'élément [`Worksheet`](/cells/python-net/fr/aspose.cells/worksheet) à l'index spécifié.
###  Indexeur
| Nom| Description|
| :- | :- |
| [index] | L'indice de base zéro de l'élément.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`get(self, index)`](/cells/python-net/fr/aspose.cells/worksheetcollection/get/#int) | Ajoutez API for Python via .Net. puisque cet [index int] n'est pas pris en charge|
| [`get(self, sheet_name)`](/cells/python-net/fr/aspose.cells/worksheetcollection/get/#str) | Ajoutez API for Python via .Net. puisque cette [chaîne sheetName] n'est pas prise en charge|
| [`add(self, type)`](/cells/python-net/fr/aspose.cells/worksheetcollection/add/#aspose.cells.sheettype) | Ajoute une feuille de calcul à la collection.|
| [`add(self)`](/cells/python-net/fr/aspose.cells/worksheetcollection/add/#) | Ajoute une feuille de calcul à la collection.|
| [`add(self, sheet_name)`](/cells/python-net/fr/aspose.cells/worksheetcollection/add/#str) | Ajoute une feuille de calcul à la collection.|
| [`register_add_in_function(self, add_in_file, function_name, lib)`](/cells/python-net/fr/aspose.cells/worksheetcollection/register_add_in_function/#str-str-bool) | Ajoute une fonction complémentaire dans le classeur|
| [`register_add_in_function(self, id, function_name)`](/cells/python-net/fr/aspose.cells/worksheetcollection/register_add_in_function/#int-str) | Ajoute une fonction complémentaire dans le classeur|
| [`add_copy(self, sheet_name)`](/cells/python-net/fr/aspose.cells/worksheetcollection/add_copy/#str) | Ajoute une feuille de calcul à la collection et copie les données d'une feuille de calcul existante.|
| [`add_copy(self, sheet_index)`](/cells/python-net/fr/aspose.cells/worksheetcollection/add_copy/#int) | Ajoute une feuille de calcul à la collection et copie les données d'une feuille de calcul existante.|
| [`add_copy(self, source, dest_sheet_names)`](/cells/python-net/fr/aspose.cells/worksheetcollection/add_copy/#list-list) | Copiez un groupe de feuilles de travail.|
| [`get_range_by_name(self, range_name)`](/cells/python-net/fr/aspose.cells/worksheetcollection/get_range_by_name/#str) | Obtient l'objet Range par nom prédéfini.|
| [`get_range_by_name(self, range_name, current_sheet_index, include_table)`](/cells/python-net/fr/aspose.cells/worksheetcollection/get_range_by_name/#str-int-bool) | Obtient [`Range`](/cells/python-net/fr/aspose.cells/range) par nom prédéfini ou nom de table|
| [`refresh_pivot_tables(self)`](/cells/python-net/fr/aspose.cells/worksheetcollection/refresh_pivot_tables/#) | Actualise tous les tableaux croisés dynamiques du fichier Excel.|
| [`refresh_pivot_tables(self, option)`](/cells/python-net/fr/aspose.cells/worksheetcollection/refresh_pivot_tables/#aspose.cells.pivot.pivottablerefreshoption) | Actualise tous les tableaux croisés dynamiques du fichier Excel.|
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells/worksheetcollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells/worksheetcollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells/worksheetcollection/index_of/#aspose.cells.worksheet-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells/worksheetcollection/index_of/#aspose.cells.worksheet-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`create_range(self, address, sheet_index)`](/cells/python-net/fr/aspose.cells/worksheetcollection/create_range/#str-int) | Crée un objet [`Range`](/cells/python-net/fr/aspose.cells/range) à partir d'une adresse de la plage.|
| [`create_union_range(self, address, sheet_index)`](/cells/python-net/fr/aspose.cells/worksheetcollection/create_union_range/#str-int) | Crée un objet [`Range`](/cells/python-net/fr/aspose.cells/range) à partir d'une adresse de la plage.|
| [`get_sheet_by_code_name(self, code_name)`](/cells/python-net/fr/aspose.cells/worksheetcollection/get_sheet_by_code_name/#str) | Obtient la feuille de calcul par le nom de code.|
| [`sort_names(self)`](/cells/python-net/fr/aspose.cells/worksheetcollection/sort_names/#) | Trie les noms définis.|
| [`swap_sheet(self, sheet_index1, sheet_index2)`](/cells/python-net/fr/aspose.cells/worksheetcollection/swap_sheet/#int-int) | Échange les deux feuilles.|
| [`remove_by_name(self, name)`](/cells/python-net/fr/aspose.cells/worksheetcollection/remove_by_name/#str) | Supprimer une feuille par nom de feuille.(CELLSPYTHONNET-192)|
| [`remove_by_index(self, index)`](/cells/python-net/fr/aspose.cells/worksheetcollection/remove_by_index/#int) | Supprimer un index feuille par feuille|
| [`remove_at(self, name)`](/cells/python-net/fr/aspose.cells/worksheetcollection/remove_at/#str) | Supprime l'élément portant un nom spécifié.|
| [`get_named_ranges(self)`](/cells/python-net/fr/aspose.cells/worksheetcollection/get_named_ranges/#) | Obtient toutes les plages nommées prédéfinies dans la feuille de calcul.|
| [`get_named_ranges_and_tables(self)`](/cells/python-net/fr/aspose.cells/worksheetcollection/get_named_ranges_and_tables/#) | Obtient toutes les plages nommées prédéfinies dans la feuille de calcul.|
| [`set_ole_size(self, start_row, end_row, start_column, end_column)`](/cells/python-net/fr/aspose.cells/worksheetcollection/set_ole_size/#int-int-int-int) | Définit la taille affichée lorsque le fichier Workbook est utilisé comme objet Ole.|
| [`clear_pivottables(self)`](/cells/python-net/fr/aspose.cells/worksheetcollection/clear_pivottables/#) |Efface les tableaux croisés dynamiques de la feuille de calcul.|
| [`refresh_all(self)`](/cells/python-net/fr/aspose.cells/worksheetcollection/refresh_all/#) | Actualisez tous les tableaux croisés dynamiques et graphiques avec la source du pivot.|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells/worksheetcollection/binary_search/#aspose.cells.worksheet) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Exemple

```python
from aspose.cells import Workbook

workbook = Workbook()
sheets = workbook.worksheets
# Add a worksheet
sheets.add()
# Change the name of a worksheet
sheets[0].name = "First Sheet"
# Set the active sheet to the second worksheet
sheets.active_sheet_index = 1

```

###  Voir également
* module [`aspose.cells`](..)
* classe [`DocumentProperty`](/cells/python-net/fr/aspose.cells.properties/documentproperty)
* classe [`Range`](/cells/python-net/fr/aspose.cells/range)
* classe [`Worksheet`](/cells/python-net/fr/aspose.cells/worksheet)
