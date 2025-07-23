---
title: CustomDocumentPropertyCollection Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 40
url: /de/aspose.cells.properties/customdocumentpropertycollection/
is_root: false
---
##  CustomDocumentPropertyCollection Klasse
Eine Sammlung benutzerdefinierter Dokumenteigenschaften.



**Nachlass:** [`CustomDocumentPropertyCollection`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection)



Der Typ CustomDocumentPropertyCollection macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [capacity](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection/capacity) | Ruft die Anzahl der Elemente ab, die die Array-Liste enthalten kann, oder legt diese fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`get(self, name)`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection/get/#str) |  |
| [`get(self, index)`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection/get/#int) |  |
| [`index_of(self, name)`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection/index_of/#str) |  |
| [`index_of(self, item, index)`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection/index_of/#aspose.cells.properties.documentproperty-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom angegebenen Index bis zum letzten Element erstreckt.|
| [`index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection/index_of/#aspose.cells.properties.documentproperty-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des ersten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der am angegebenen Index beginnt und die angegebene Anzahl von Elementen enthält.|
| [`copy_to(self, array)`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection/copy_to/#list) |Kopiert die gesamte Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am Anfang der Ziel-Array-Liste.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection/copy_to/#int-list-int-int) | Kopiert einen Bereich von Elementen aus der Array-Liste in eine kompatible eindimensionale Array-Liste, beginnend am angegebenen Index der Ziel-Array-Liste.|
| [`last_index_of(self, item)`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb der gesamten Arrayliste zurück.|
| [`last_index_of(self, item, index)`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty-int) |Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der sich vom ersten Element bis zum angegebenen Index erstreckt.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection/last_index_of/#aspose.cells.properties.documentproperty-int-int) | Sucht nach dem angegebenen Objekt und gibt den nullbasierten Index des letzten Vorkommens innerhalb des Elementbereichs in der Array-Liste zurück, der die angegebene Anzahl von Elementen enthält und am angegebenen Index endet.|
| [`add(self, name, value)`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection/add/#str-str) | Erstellt eine neue benutzerdefinierte Dokumenteigenschaft des**PropertyType.String** Datentyp.|
| [`add(self, name, value)`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection/add/#str-int) | Erstellt eine neue benutzerdefinierte Dokumenteigenschaft des**Eigenschaftstyp.Nummer** Datentyp.|
| [`add(self, name, value)`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection/add/#str-datetime) | Erstellt eine neue benutzerdefinierte Dokumenteigenschaft des**Eigenschaftstyp.Datum/Uhrzeit** Datentyp.|
| [`add(self, name, value)`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection/add/#str-bool) | Erstellt eine neue benutzerdefinierte Dokumenteigenschaft des**PropertyType.Boolean** Datentyp.|
| [`add(self, name, value)`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection/add/#str-float) | Erstellt eine neue benutzerdefinierte Dokumenteigenschaft des**PropertyType.Float** Datentyp.|
| [`binary_search(self, item)`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection/binary_search/#aspose.cells.properties.documentproperty) | Durchsucht die gesamte sortierte Array-Liste mithilfe des Standardvergleichers nach einem Element und gibt den nullbasierten Index des Elements zurück.|
| [`add_link_to_content(self, name, source)`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection/add_link_to_content/#str-str) |Erstellt eine neue benutzerdefinierte Dokumenteigenschaft, die auf den Inhalt verweist.|
| [`update_linked_property_value(self)`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection/update_linked_property_value/#) | Aktualisieren Sie den benutzerdefinierten Dokument-Eigenschaftswert, der auf den Inhalt verweist.|
| [`update_linked_range(self)`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection/update_linked_range/#) | Aktualisieren Sie den Wert der benutzerdefinierten Dokumenteigenschaft auf den verknüpften Bereich.|



###  Bemerkungen

Jedes [`DocumentProperty`](/cells/python-net/de/aspose.cells.properties/documentproperty)-Objekt stellt eine benutzerdefinierte Eigenschaft eines Containerdokuments dar.

###  Beispiel

```python
from aspose.cells import Workbook

# Instantiate a Workbook object
workbook = Workbook("book1.xls")
# Retrieve a list of all custom document properties of the Excel file
customProperties = workbook.worksheets.custom_document_properties

```

###  Siehe auch
* Modul [`aspose.cells.properties`](..)
* Klasse [`CustomDocumentPropertyCollection`](/cells/python-net/de/aspose.cells.properties/customdocumentpropertycollection)
* Klasse [`DocumentProperty`](/cells/python-net/de/aspose.cells.properties/documentproperty)
