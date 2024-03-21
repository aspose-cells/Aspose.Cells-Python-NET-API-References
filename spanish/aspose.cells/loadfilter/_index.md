---
title: LoadFilter clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1050
url: /es/aspose.cells/loadfilter/
is_root: false
---
##  LoadFilter clase
Representa el filtro que proporciona opciones para cargar datos al cargar un libro desde una plantilla.



El tipo LoadFilter expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [__init__](/cells/python-net/es/aspose.cells/loadfilter/__init__/#) | Construye un LoadFilter con opciones de filtro predeterminadas LoadDataFilterOptions.All.|
| [__init__](/cells/python-net/es/aspose.cells/loadfilter/__init__/#aspose.cells.LoadDataFilterOptions) | Construye un LoadFilter con las opciones de filtro dadas.|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [load_data_filter_options](/cells/python-net/es/aspose.cells/loadfilter/load_data_filter_options) | Las opciones de filtro para indicar qué datos deben cargarse.|
| [sheets_in_loading_order](/cells/python-net/es/aspose.cells/loadfilter/sheets_in_loading_order) | Especifica las hojas (índices) y el orden que se cargarán.<br/>El valor predeterminado es nulo, lo que indica que se deben cargar todas las hojas en el orden predeterminado en el archivo de plantilla.<br/> Si no es nulo y el índice de alguna hoja no está en la matriz devuelta, entonces la hoja no se cargará.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [start_sheet](/cells/python-net/es/aspose.cells/loadfilter/start_sheet/#aspose.cells.Worksheet) | Prepara opciones de filtro antes de cargar la hoja de trabajo determinada.<br/>La implementación de LoadFilter por parte del usuario puede cambiar LoadDataFilterOptions aquí<br/> para indicar cómo cargar datos para esta hoja de trabajo.|



###  Observaciones

El usuario puede especificar las opciones de filtro o implementar su propio LoadFilter para especificar cómo cargar datos.

###  Ver también
* módulo [`aspose.cells`](..)
