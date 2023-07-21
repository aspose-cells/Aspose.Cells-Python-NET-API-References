﻿---
title: WorkbookMetadata class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells.metadata/workbookmetadata/
is_root: false
---

## WorkbookMetadata class

Represents the meta data.



The WorkbookMetadata type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/cells/python-net/aspose.cells.metadata/workbookmetadata/__init__/#str-aspose.cells.metadata.MetadataOptions) | Create the meta data object. |
| [__init__](/cells/python-net/aspose.cells.metadata/workbookmetadata/__init__/#io.RawIOBase-aspose.cells.metadata.MetadataOptions) | Create the meta data object. |


### Properties
| Property | Description |
| :- | :- |
| [options](/cells/python-net/aspose.cells.metadata/workbookmetadata/options) | Gets the options of the metadata. |
| [built_in_document_properties](/cells/python-net/aspose.cells.metadata/workbookmetadata/built_in_document_properties) | Returns a [`DocumentProperty`](/cells/python-net/aspose.cells.properties/documentproperty) collection that represents all the  built-in document properties of the spreadsheet. |
| [custom_document_properties](/cells/python-net/aspose.cells.metadata/workbookmetadata/custom_document_properties) | Returns a [`DocumentProperty`](/cells/python-net/aspose.cells.properties/documentproperty) collection that represents all the custom document properties of the spreadsheet. |


### Methods
| Method | Description |
| :- | :- |
| [save](/cells/python-net/aspose.cells.metadata/workbookmetadata/save/#str) | Save the modified metadata to the file. |
| [save](/cells/python-net/aspose.cells.metadata/workbookmetadata/save/#io.RawIOBase) | Save the modified metadata to the stream. |



### Example 


The following example creates a WorkbookMetadata.

```python
from aspose.cells.metadata import MetadataOptions, MetadataType, WorkbookMetadata

options = MetadataOptions(MetadataType.DOCUMENT_PROPERTIES)
meta = WorkbookMetadata("book1.xlsx", options)
meta.custom_document_properties.add("test", "test")
meta.save("book2.xlsx")

```

### See Also
* module [`aspose.cells.metadata`](..)
* class [`DocumentProperty`](/cells/python-net/aspose.cells.properties/documentproperty)
