---
title: VbaModuleCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells.vba/vbamodulecollection/
is_root: false
---
##  VbaModuleCollection classe
Représente la liste de [`VbaModule`](/cells/python-net/fr/aspose.cells.vba/vbamodule)



Le type VbaModuleCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`add(self, sheet)`](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.worksheet) | Ajoute un module pour une feuille de calcul.|
| [`add(self, type, name)`](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.vba.vbamoduletype-str) | Ajoute un module.|
| [`get(self, index)`](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/get/#int) | Obtient [`VbaModule`](/cells/python-net/fr/aspose.cells.vba/vbamodule) dans la liste par l'index.|
| [`get(self, name)`](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/get/#str) | Obtient [`VbaModule`](/cells/python-net/fr/aspose.cells.vba/vbamodule) dans la liste par le nom.|
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.vbamodule-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.vbamodule-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`add_designer_storage(self, name, data)`](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/add_designer_storage/#str-bytes) |  |
| [`get_designer_storage(self, name)`](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/get_designer_storage/#str) | Représente les données du Designer.|
| [`add_user_form(self, name, codes, designer_storage)`](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/add_user_form/#str-str-bytes) | Insérer le formulaire utilisateur dans le projet VBA.|
| [`remove_by_worksheet(self, sheet)`](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/remove_by_worksheet/#aspose.cells.worksheet) | Supprime le module d'une feuille de calcul.|
| [`remove_by_name(self, name)`](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/remove_by_name/#str) | Supprimer le module par le nom|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/binary_search/#aspose.cells.vba.vbamodule) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Exemple

```python
from aspose.cells import Workbook
from aspose.cells.vba import VbaModuleType

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
#  Add a new module.
vbaProject.modules.add(VbaModuleType.CLASS, "test")
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  Voir également
* module [`aspose.cells.vba`](..)
* classe [`VbaModule`](/cells/python-net/fr/aspose.cells.vba/vbamodule)
