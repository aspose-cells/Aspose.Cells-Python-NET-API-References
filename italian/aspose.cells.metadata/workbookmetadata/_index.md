---
title: WorkbookMetadata classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells.metadata/workbookmetadata/
is_root: false
---
##  WorkbookMetadata classe
Rappresenta i metadati.



Il tipo WorkbookMetadata espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self, file_name, options)`](/cells/python-net/it/aspose.cells.metadata/workbookmetadata/__init__/#str-aspose.cells.metadata.metadataoptions) | Creare l'oggetto metadati.|
| [`__init__(self, stream, options)`](/cells/python-net/it/aspose.cells.metadata/workbookmetadata/__init__/#io.rawiobase-aspose.cells.metadata.metadataoptions) | Creare l'oggetto metadati.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [options](/cells/python-net/it/aspose.cells.metadata/workbookmetadata/options) | Ottiene le opzioni dei metadati.|
| [built_in_document_properties](/cells/python-net/it/aspose.cells.metadata/workbookmetadata/built_in_document_properties) | Restituisce una raccolta [`DocumentProperty`](/cells/python-net/it/aspose.cells.properties/documentproperty) che rappresenta tutte le proprietà del documento integrate nel foglio di calcolo.|
| [custom_document_properties](/cells/python-net/it/aspose.cells.metadata/workbookmetadata/custom_document_properties) | Restituisce una raccolta [`DocumentProperty`](/cells/python-net/it/aspose.cells.properties/documentproperty) che rappresenta tutte le proprietà personalizzate del documento del foglio di calcolo.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`save(self, file_name)`](/cells/python-net/it/aspose.cells.metadata/workbookmetadata/save/#str) | Salvare i metadati modificati nel file.|
| [`save(self, stream)`](/cells/python-net/it/aspose.cells.metadata/workbookmetadata/save/#io.rawiobase) | Salva i metadati modificati nel flusso.|



###  Esempio

L'esempio seguente crea WorkbookMetadata.

```python
from aspose.cells.metadata import MetadataOptions, MetadataType, WorkbookMetadata

options = MetadataOptions(MetadataType.DOCUMENT_PROPERTIES)
meta = WorkbookMetadata("book1.xlsx", options)
meta.custom_document_properties.add("test", "test")
meta.save("book2.xlsx")

```

###  Guarda anche
* modulo [`aspose.cells.metadata`](..)
* classe [`DocumentProperty`](/cells/python-net/it/aspose.cells.properties/documentproperty)
