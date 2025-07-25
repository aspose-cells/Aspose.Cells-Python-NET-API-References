---
title: WorkbookMetadata klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells.metadata/workbookmetadata/
is_root: false
---
##  WorkbookMetadata klass
Representerar metadata.



Typen WorkbookMetadata avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self, file_name, options)`](/cells/python-net/sv/aspose.cells.metadata/workbookmetadata/__init__/#str-aspose.cells.metadata.metadataoptions) | Skapa metadataobjektet.|
| [`__init__(self, stream, options)`](/cells/python-net/sv/aspose.cells.metadata/workbookmetadata/__init__/#io.rawiobase-aspose.cells.metadata.metadataoptions) | Skapa metadataobjektet.|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [options](/cells/python-net/sv/aspose.cells.metadata/workbookmetadata/options) | Hämtar alternativen för metadata.|
| [built_in_document_properties](/cells/python-net/sv/aspose.cells.metadata/workbookmetadata/built_in_document_properties) | Returnerar en [`DocumentProperty`](/cells/python-net/sv/aspose.cells.properties/documentproperty)-samling som representerar alla inbyggda dokumentegenskaper i kalkylarket.|
| [custom_document_properties](/cells/python-net/sv/aspose.cells.metadata/workbookmetadata/custom_document_properties) | Returnerar en [`DocumentProperty`](/cells/python-net/sv/aspose.cells.properties/documentproperty)-samling som representerar alla anpassade dokumentegenskaper i kalkylarket.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`save(self, file_name)`](/cells/python-net/sv/aspose.cells.metadata/workbookmetadata/save/#str) | Spara de ändrade metadata till filen.|
| [`save(self, stream)`](/cells/python-net/sv/aspose.cells.metadata/workbookmetadata/save/#io.rawiobase) | Spara de ändrade metadata i strömmen.|



###  Exempel

Följande exempel skapar en WorkbookMetadata.

```python
from aspose.cells.metadata import MetadataOptions, MetadataType, WorkbookMetadata

options = MetadataOptions(MetadataType.DOCUMENT_PROPERTIES)
meta = WorkbookMetadata("book1.xlsx", options)
meta.custom_document_properties.add("test", "test")
meta.save("book2.xlsx")

```

###  Se även
* modul [`aspose.cells.metadata`](..)
* klass [`DocumentProperty`](/cells/python-net/sv/aspose.cells.properties/documentproperty)
