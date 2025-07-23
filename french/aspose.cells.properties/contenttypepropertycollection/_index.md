---
title: ContentTypePropertyCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 30
url: /fr/aspose.cells.properties/contenttypepropertycollection/
is_root: false
---
##  ContentTypePropertyCollection classe
Une collection de [`ContentTypeProperty`](/cells/python-net/fr/aspose.cells.properties/contenttypeproperty) objets qui représentent des informations supplémentaires.



Le type ContentTypePropertyCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells.properties/contenttypepropertycollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`add(self, name, value)`](/cells/python-net/fr/aspose.cells.properties/contenttypepropertycollection/add/#str-str) | Ajoute des informations sur la propriété du type de contenu.|
| [`add(self, name, value, type)`](/cells/python-net/fr/aspose.cells.properties/contenttypepropertycollection/add/#str-str-str) | Ajoute des informations sur la propriété du type de contenu.|
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells.properties/contenttypepropertycollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells.properties/contenttypepropertycollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.properties/contenttypepropertycollection/index_of/#aspose.cells.properties.contenttypeproperty-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.properties/contenttypepropertycollection/index_of/#aspose.cells.properties.contenttypeproperty-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells.properties/contenttypepropertycollection/last_index_of/#aspose.cells.properties.contenttypeproperty) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.properties/contenttypepropertycollection/last_index_of/#aspose.cells.properties.contenttypeproperty-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.properties/contenttypepropertycollection/last_index_of/#aspose.cells.properties.contenttypeproperty-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`get(self, name)`](/cells/python-net/fr/aspose.cells.properties/contenttypepropertycollection/get/#str) | Obtient la propriété de type de contenu par le nom de la propriété.|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells.properties/contenttypepropertycollection/binary_search/#aspose.cells.properties.contenttypeproperty) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Exemple

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Add a new property.
workbook.content_type_properties.add("Admin", "Aspose", "text")
# Save the Excel file
workbook.save("book1.xlsm")

```

###  Voir également
* module [`aspose.cells.properties`](..)
* classe [`ContentTypeProperty`](/cells/python-net/fr/aspose.cells.properties/contenttypeproperty)
