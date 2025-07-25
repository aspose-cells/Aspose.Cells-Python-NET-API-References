---
title: ExternalLinkCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 580
url: /es/aspose.cells/externallinkcollection/
is_root: false
---
##  ExternalLinkCollection clase
Representa la colección de enlaces externos en un libro de trabajo.



El tipo ExternalLinkCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [count](/cells/python-net/es/aspose.cells/externallinkcollection/count) | Obtiene el número de elementos realmente contenidos en la colección.|



Obtiene el elemento [`ExternalLink`](/cells/python-net/es/aspose.cells/externallink) en el índice especificado.
###  Indexador
| Nombre| Descripción|
| :- | :- |
| [index] | El índice basado en cero del elemento.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`add(self, file_name, sheet_names)`](/cells/python-net/es/aspose.cells/externallinkcollection/add/#str-list) | Agrega un enlace externo.|
| [`add(self, directory_type, file_name, sheet_names)`](/cells/python-net/es/aspose.cells/externallinkcollection/add/#aspose.cells.directorytype-str-list) | Añadir un enlace externo .|
| [`clear(self)`](/cells/python-net/es/aspose.cells/externallinkcollection/clear/#) | Elimina todos los enlaces externos.|
| [`clear(self, update_references_as_local)`](/cells/python-net/es/aspose.cells/externallinkcollection/clear/#bool) | Elimina todos los enlaces externos.|
| [`remove_at(self, index)`](/cells/python-net/es/aspose.cells/externallinkcollection/remove_at/#int) | Elimina el enlace externo especificado del libro de trabajo.|
| [`remove_at(self, index, update_references_as_local)`](/cells/python-net/es/aspose.cells/externallinkcollection/remove_at/#int-bool) | Elimina el enlace externo especificado del libro de trabajo.|



###  Ejemplo

```python
from aspose.cells import Workbook

# Open a file with external links
workbook = Workbook("book1.xls")
# Change external link data source
workbook.worksheets.external_links[0].data_source = "d:\\link.xls"

```

###  Ver también
* módulo [`aspose.cells`](..)
* clase [`ExternalLink`](/cells/python-net/es/aspose.cells/externallink)
