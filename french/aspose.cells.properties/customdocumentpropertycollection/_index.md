---
title: CustomDocumentPropertyCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 40
url: /fr/aspose.cells.properties/customdocumentpropertycollection/
is_root: false
---
##  CustomDocumentPropertyCollection classe
Une collection de propriétés de document personnalisées.



**Héritage:** [`CustomDocumentPropertyCollection`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection)



Le type CustomDocumentPropertyCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`get(self, name)`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection/get/#str) |  |
| [`get(self, index)`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection/get/#int) |  |
| [`index_of(self, name)`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection/index_of/#str) |  |
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection/index_of/#aspose.cells.properties.documentproperty-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection/index_of/#aspose.cells.properties.documentproperty-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`add(self, name, value)`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection/add/#str-str) | Crée une nouvelle propriété de document personnalisée du**PropertyType.String** type de données.|
| [`add(self, name, value)`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection/add/#str-int) | Crée une nouvelle propriété de document personnalisée du**PropertyType.Number** type de données.|
| [`add(self, name, value)`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection/add/#str-datetime) | Crée une nouvelle propriété de document personnalisée du**Type de propriété.DateHeure** type de données.|
| [`add(self, name, value)`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection/add/#str-bool) | Crée une nouvelle propriété de document personnalisée du**PropertyType.Booléen** type de données.|
| [`add(self, name, value)`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection/add/#str-float) | Crée une nouvelle propriété de document personnalisée du**PropertyType.Float** type de données.|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection/binary_search/#aspose.cells.properties.documentproperty) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|
| [`add_link_to_content(self, name, source)`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection/add_link_to_content/#str-str) |Crée une nouvelle propriété de document personnalisée qui renvoie au contenu.|
| [`update_linked_property_value(self)`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection/update_linked_property_value/#) | Mettre à jour la valeur de la propriété du document personnalisé qui renvoie au contenu.|
| [`update_linked_range(self)`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection/update_linked_range/#) | Mettre à jour la valeur de la propriété du document personnalisé sur la plage liée.|



###  Remarques

Chaque objet [`DocumentProperty`](/cells/python-net/fr/aspose.cells.properties/documentproperty) représente une propriété personnalisée d'un document conteneur.

###  Exemple

```python
from aspose.cells import Workbook

# Instantiate a Workbook object
workbook = Workbook("book1.xls")
# Retrieve a list of all custom document properties of the Excel file
customProperties = workbook.worksheets.custom_document_properties

```

###  Voir également
* module [`aspose.cells.properties`](..)
* classe [`CustomDocumentPropertyCollection`](/cells/python-net/fr/aspose.cells.properties/customdocumentpropertycollection)
* classe [`DocumentProperty`](/cells/python-net/fr/aspose.cells.properties/documentproperty)
