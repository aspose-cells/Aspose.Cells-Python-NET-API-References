---
title: WorkbookMetadata Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells.metadata/workbookmetadata/
is_root: false
---
##  WorkbookMetadata Klasse
Stellt die Metadaten dar.



Der Typ WorkbookMetadata macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self, file_name, options)`](/cells/python-net/de/aspose.cells.metadata/workbookmetadata/__init__/#str-aspose.cells.metadata.metadataoptions) | Erstellen Sie das Metadatenobjekt.|
| [`__init__(self, stream, options)`](/cells/python-net/de/aspose.cells.metadata/workbookmetadata/__init__/#io.rawiobase-aspose.cells.metadata.metadataoptions) | Erstellen Sie das Metadatenobjekt.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [options](/cells/python-net/de/aspose.cells.metadata/workbookmetadata/options) | Ruft die Optionen der Metadaten ab.|
| [built_in_document_properties](/cells/python-net/de/aspose.cells.metadata/workbookmetadata/built_in_document_properties) | Gibt eine [`DocumentProperty`](/cells/python-net/de/aspose.cells.properties/documentproperty)-Sammlung zurück, die alle integrierten Dokumenteigenschaften der Tabelle darstellt.|
| [custom_document_properties](/cells/python-net/de/aspose.cells.metadata/workbookmetadata/custom_document_properties) | Gibt eine [`DocumentProperty`](/cells/python-net/de/aspose.cells.properties/documentproperty)-Sammlung zurück, die alle benutzerdefinierten Dokumenteigenschaften der Tabelle darstellt.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`save(self, file_name)`](/cells/python-net/de/aspose.cells.metadata/workbookmetadata/save/#str) | Speichern Sie die geänderten Metadaten in der Datei.|
| [`save(self, stream)`](/cells/python-net/de/aspose.cells.metadata/workbookmetadata/save/#io.rawiobase) | Speichern Sie die geänderten Metadaten im Stream.|



###  Beispiel

Das folgende Beispiel erstellt eine WorkbookMetadata.

```python
from aspose.cells.metadata import MetadataOptions, MetadataType, WorkbookMetadata

options = MetadataOptions(MetadataType.DOCUMENT_PROPERTIES)
meta = WorkbookMetadata("book1.xlsx", options)
meta.custom_document_properties.add("test", "test")
meta.save("book2.xlsx")

```

###  Siehe auch
* Modul [`aspose.cells.metadata`](..)
* Klasse [`DocumentProperty`](/cells/python-net/de/aspose.cells.properties/documentproperty)
