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
Représente la liste des [VbaModule](/cells/python-net/fr/aspose.cells.vba/vbamodule)



Le type VbaModuleCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableau peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [add(sheet)](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/add/#Worksheet) |Ajoute un module pour une feuille de calcul.|
| [add(type, name)](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/add/#VbaModuleType-str) | Ajoute un module.|
| [copy_to(array)](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/copy_to/#list) | Copie la totalité de la liste de tableaux dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [copy_to(index, array, array_index, count)](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/copy_to/#int-list-int-int) |Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [index_of(item, index)](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/index_of/#VbaModule-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [index_of(item, index, count)](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/index_of/#VbaModule-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [last_index_of(item)](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/last_index_of/#VbaModule) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste complète du tableau.|
| [last_index_of(item, index)](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/last_index_of/#VbaModule-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [last_index_of(item, index, count)](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/last_index_of/#VbaModule-int-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre d'éléments spécifié et se termine à l'index spécifié.|
| [add_designer_storage(name, data)](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/add_designer_storage/#str-bytes) |  |
| [get_designer_storage(name)](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/get_designer_storage/#str) | Représente les données de Designer.|
| [binary_search(item)](/cells/python-net/fr/aspose.cells.vba/vbamodulecollection/binary_search/#VbaModule) | Recherche un élément dans toute la liste de tableaux triés à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



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
* module [aspose.cells.vba](..)
* classe [VbaModule](/cells/python-net/fr/aspose.cells.vba/vbamodule)
