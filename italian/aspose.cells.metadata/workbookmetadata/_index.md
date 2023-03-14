---
title: classe WorkbookMetadata
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 20
url: /it/aspose.cells.metadata/workbookmetadata/
is_root: false
---
##  classe WorkbookMetadata
Rappresenta i metadati.



Il tipo WorkbookMetadata espone i membri seguenti:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [WorkbookMetadata(file_name, options)](/cells/python-net/it/aspose.cells.metadata/workbookmetadata/__init__/#str-MetadataOptions) | Creare l'oggetto dei metadati.|
| [WorkbookMetadata(stream, options)](/cells/python-net/it/aspose.cells.metadata/workbookmetadata/__init__/#io.RawIOBase-MetadataOptions) | Creare l'oggetto dei metadati.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [options](/cells/python-net/it/aspose.cells.metadata/workbookmetadata/options) | Ottiene le opzioni dei metadati.|
| [built_in_document_properties](/cells/python-net/it/aspose.cells.metadata/workbookmetadata/built_in_document_properties) |Restituisce una raccolta [DocumentProperty](/cells/python-net/it/aspose.cells.properties/documentproperty) che rappresenta tutte le proprietà del documento predefinite del foglio di calcolo.|
| [custom_document_properties](/cells/python-net/it/aspose.cells.metadata/workbookmetadata/custom_document_properties) | Restituisce una raccolta [DocumentProperty](/cells/python-net/it/aspose.cells.properties/documentproperty) che rappresenta tutte le proprietà del documento personalizzato del foglio di calcolo.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [save(file_name)](/cells/python-net/it/aspose.cells.metadata/workbookmetadata/save/#str) | Salva i metadati modificati nel file.|
| [save(stream)](/cells/python-net/it/aspose.cells.metadata/workbookmetadata/save/#io.RawIOBase) | Salva i metadati modificati nello stream.|



###  Esempio

L'esempio seguente crea un WorkbookMetadata.

```python
from aspose.cells.metadata import MetadataOptions, MetadataType, WorkbookMetadata

options = MetadataOptions(MetadataType.DOCUMENT_PROPERTIES)
meta = WorkbookMetadata("book1.xlsx", options)
meta.custom_document_properties.add("test", "test")
meta.save("book2.xlsx")

```

###  Guarda anche
* modulo [aspose.cells.metadata](..)
* classe [DocumentProperty](/cells/python-net/it/aspose.cells.properties/documentproperty)
