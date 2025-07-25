---
title: WorkbookMetadata clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells.metadata/workbookmetadata/
is_root: false
---
##  WorkbookMetadata clase
Representa los metadatos.



El tipo WorkbookMetadata expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self, file_name, options)`](/cells/python-net/es/aspose.cells.metadata/workbookmetadata/__init__/#str-aspose.cells.metadata.metadataoptions) | Crea el objeto de metadatos.|
| [`__init__(self, stream, options)`](/cells/python-net/es/aspose.cells.metadata/workbookmetadata/__init__/#io.rawiobase-aspose.cells.metadata.metadataoptions) | Crea el objeto de metadatos.|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [options](/cells/python-net/es/aspose.cells.metadata/workbookmetadata/options) | Obtiene las opciones de los metadatos.|
| [built_in_document_properties](/cells/python-net/es/aspose.cells.metadata/workbookmetadata/built_in_document_properties) | Devuelve una colección [`DocumentProperty`](/cells/python-net/es/aspose.cells.properties/documentproperty) que representa todas las propiedades de documento integradas de la hoja de cálculo.|
| [custom_document_properties](/cells/python-net/es/aspose.cells.metadata/workbookmetadata/custom_document_properties) | Devuelve una colección [`DocumentProperty`](/cells/python-net/es/aspose.cells.properties/documentproperty) que representa todas las propiedades del documento personalizado de la hoja de cálculo.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`save(self, file_name)`](/cells/python-net/es/aspose.cells.metadata/workbookmetadata/save/#str) | Guarde los metadatos modificados en el archivo.|
| [`save(self, stream)`](/cells/python-net/es/aspose.cells.metadata/workbookmetadata/save/#io.rawiobase) | Guarde los metadatos modificados en la transmisión.|



###  Ejemplo

El siguiente ejemplo crea un WorkbookMetadata.

```python
from aspose.cells.metadata import MetadataOptions, MetadataType, WorkbookMetadata

options = MetadataOptions(MetadataType.DOCUMENT_PROPERTIES)
meta = WorkbookMetadata("book1.xlsx", options)
meta.custom_document_properties.add("test", "test")
meta.save("book2.xlsx")

```

###  Ver también
* módulo [`aspose.cells.metadata`](..)
* clase [`DocumentProperty`](/cells/python-net/es/aspose.cells.properties/documentproperty)
