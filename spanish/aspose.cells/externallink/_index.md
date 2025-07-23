---
title: ExternalLink clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 570
url: /es/aspose.cells/externallink/
is_root: false
---
##  ExternalLink clase
Representa un enlace externo en un libro de trabajo.



El tipo ExternalLink expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [type](/cells/python-net/es/aspose.cells/externallink/type) | Obtiene el tipo de enlace externo.|
| [path_type](/cells/python-net/es/aspose.cells/externallink/path_type) | Obtener el tipo de ruta de este enlace externo|
| [original_data_source](/cells/python-net/es/aspose.cells/externallink/original_data_source) | Representa la fuente de datos almacenados del enlace externo.|
| [data_source](/cells/python-net/es/aspose.cells/externallink/data_source) | Representa la fuente de datos del enlace externo.|
| [is_referred](/cells/python-net/es/aspose.cells/externallink/is_referred) | Indica si este enlace externo está referenciado por otros.|
| [is_visible](/cells/python-net/es/aspose.cells/externallink/is_visible) | Indica si este enlace externo es visible en MS Excel.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`add_external_name(self, text, refer_to)`](/cells/python-net/es/aspose.cells/externallink/add_external_name/#str-str) | Agrega un nombre externo.|



###  Ejemplo

```python
from aspose.cells import Workbook

# Open a file with external links
workbook = Workbook("book1.xls")
# Get External Link
externalLink = workbook.worksheets.external_links[0]
# Change External Link's Data Source
externalLink.data_source = "d:\\link.xls"

```

###  Ver también
* módulo [`aspose.cells`](..)
