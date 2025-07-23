---
title: WorksheetCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1610
url: /es/aspose.cells/worksheetcollection/
is_root: false
---
##  WorksheetCollection clase
Encapsula una colección de [`Worksheet`](/cells/python-net/es/aspose.cells/worksheet) objetos.



El tipo WorksheetCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [web_extension_task_panes](/cells/python-net/es/aspose.cells/worksheetcollection/web_extension_task_panes) | Obtiene la lista de paneles de tareas.|
| [web_extensions](/cells/python-net/es/aspose.cells/worksheetcollection/web_extensions) | Obtiene la lista de paneles de tareas.|
| [threaded_comment_authors](/cells/python-net/es/aspose.cells/worksheetcollection/threaded_comment_authors) | Obtiene la lista de autores de comentarios enhebrados.|
| [is_refresh_all_connections](/cells/python-net/es/aspose.cells/worksheetcollection/is_refresh_all_connections) | Indica si se deben actualizar todas las conexiones al abrir un archivo en MS Excel.|
| [names](/cells/python-net/es/aspose.cells/worksheetcollection/names) | Obtiene la colección de todos los objetos Nombre en la hoja de cálculo.|
| [active_sheet_name](/cells/python-net/es/aspose.cells/worksheetcollection/active_sheet_name) | Representa el nombre de la hoja de trabajo activa cuando se abre la hoja de cálculo.|
| [active_sheet_index](/cells/python-net/es/aspose.cells/worksheetcollection/active_sheet_index) | Representa el índice de la hoja de trabajo activa cuando se abre la hoja de cálculo.|
| [dxfs](/cells/python-net/es/aspose.cells/worksheetcollection/dxfs) | Obtiene los registros de formato diferencial maestro.|
| [xml_maps](/cells/python-net/es/aspose.cells/worksheetcollection/xml_maps) | Obtiene y establece los mapas XML en el libro de trabajo.|
| [built_in_document_properties](/cells/python-net/es/aspose.cells/worksheetcollection/built_in_document_properties) | Devuelve una colección [`DocumentProperty`](/cells/python-net/es/aspose.cells.properties/documentproperty) que representa todas las propiedades de documento integradas de la hoja de cálculo.|
| [custom_document_properties](/cells/python-net/es/aspose.cells/worksheetcollection/custom_document_properties) | Devuelve una colección [`DocumentProperty`](/cells/python-net/es/aspose.cells.properties/documentproperty) que representa todas las propiedades del documento personalizado de la hoja de cálculo.|
| [ole_size](/cells/python-net/es/aspose.cells/worksheetcollection/ole_size) | Obtiene y establece el tamaño mostrado cuando el archivo de libro de trabajo se utiliza como un objeto Ole.|
| [external_links](/cells/python-net/es/aspose.cells/worksheetcollection/external_links) |Representa enlaces externos en un libro de trabajo.|
| [table_styles](/cells/python-net/es/aspose.cells/worksheetcollection/table_styles) | Obtiene el objeto [`WorksheetCollection.table_styles`](/cells/python-net/es/aspose.cells/worksheetcollection#table_styles).|
| [revision_logs](/cells/python-net/es/aspose.cells/worksheetcollection/revision_logs) | Representa registros de revisión.|
| [sensitivity_labels](/cells/python-net/es/aspose.cells/worksheetcollection/sensitivity_labels) | Representa todas las etiquetas de sensibilidad.|
| [capacity](/cells/python-net/es/aspose.cells/worksheetcollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matrices.|



Obtiene el elemento [`Worksheet`](/cells/python-net/es/aspose.cells/worksheet) en el índice especificado.
###  Indexador
| Nombre| Descripción|
| :- | :- |
| [index] | El índice basado en cero del elemento.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`get(self, index)`](/cells/python-net/es/aspose.cells/worksheetcollection/get/#int) | Agregue API for Python a través de .Net.ya que este [int index] no es compatible|
| [`get(self, sheet_name)`](/cells/python-net/es/aspose.cells/worksheetcollection/get/#str) | Agregue API for Python a través de .Net.ya que esta [string sheetName] no es compatible|
| [`add(self, type)`](/cells/python-net/es/aspose.cells/worksheetcollection/add/#aspose.cells.sheettype) | Agrega una hoja de trabajo a la colección.|
| [`add(self)`](/cells/python-net/es/aspose.cells/worksheetcollection/add/#) | Agrega una hoja de trabajo a la colección.|
| [`add(self, sheet_name)`](/cells/python-net/es/aspose.cells/worksheetcollection/add/#str) | Agrega una hoja de trabajo a la colección.|
| [`register_add_in_function(self, add_in_file, function_name, lib)`](/cells/python-net/es/aspose.cells/worksheetcollection/register_add_in_function/#str-str-bool) | Añade una función complementaria al libro de trabajo.|
| [`register_add_in_function(self, id, function_name)`](/cells/python-net/es/aspose.cells/worksheetcollection/register_add_in_function/#int-str) | Añade una función complementaria al libro de trabajo.|
| [`add_copy(self, sheet_name)`](/cells/python-net/es/aspose.cells/worksheetcollection/add_copy/#str) | Agrega una hoja de cálculo a la colección y copia datos de una hoja de cálculo existente.|
| [`add_copy(self, sheet_index)`](/cells/python-net/es/aspose.cells/worksheetcollection/add_copy/#int) | Agrega una hoja de cálculo a la colección y copia datos de una hoja de cálculo existente.|
| [`add_copy(self, source, dest_sheet_names)`](/cells/python-net/es/aspose.cells/worksheetcollection/add_copy/#list-list) | Copiar un grupo de hojas de trabajo.|
| [`get_range_by_name(self, range_name)`](/cells/python-net/es/aspose.cells/worksheetcollection/get_range_by_name/#str) | Obtiene el objeto Range por nombre predefinido.|
| [`get_range_by_name(self, range_name, current_sheet_index, include_table)`](/cells/python-net/es/aspose.cells/worksheetcollection/get_range_by_name/#str-int-bool) | Obtiene [`Range`](/cells/python-net/es/aspose.cells/range) por nombre predefinido o nombre de la tabla|
| [`refresh_pivot_tables(self)`](/cells/python-net/es/aspose.cells/worksheetcollection/refresh_pivot_tables/#) | Actualiza todas las tablas dinámicas en el archivo Excel.|
| [`refresh_pivot_tables(self, option)`](/cells/python-net/es/aspose.cells/worksheetcollection/refresh_pivot_tables/#aspose.cells.pivot.pivottablerefreshoption) | Actualiza todas las tablas dinámicas en el archivo Excel.|
| [`copy_to(self, array)`](/cells/python-net/es/aspose.cells/worksheetcollection/copy_to/#list) |Copia la lista de matrices completa a una lista de matrices unidimensional compatible, comenzando por el principio de la lista de matrices de destino.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/es/aspose.cells/worksheetcollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matrices a una lista de matrices unidimensionales compatible, comenzando en el índice especificado de la lista de matrices de destino.|
| [`index_of(self, item, index)`](/cells/python-net/es/aspose.cells/worksheetcollection/index_of/#aspose.cells.worksheet-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de la matriz que se extiende desde el índice especificado hasta el último elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells/worksheetcollection/index_of/#aspose.cells.worksheet-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene la cantidad especificada de elementos.|
| [`last_index_of(self, item)`](/cells/python-net/es/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet) | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista de la matriz.|
| [`last_index_of(self, item, index)`](/cells/python-net/es/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet-int) |Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells/worksheetcollection/last_index_of/#aspose.cells.worksheet-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que contiene la cantidad especificada de elementos y termina en el índice especificado.|
| [`create_range(self, address, sheet_index)`](/cells/python-net/es/aspose.cells/worksheetcollection/create_range/#str-int) | Crea un objeto [`Range`](/cells/python-net/es/aspose.cells/range) a partir de una dirección del rango.|
| [`create_union_range(self, address, sheet_index)`](/cells/python-net/es/aspose.cells/worksheetcollection/create_union_range/#str-int) | Crea un objeto [`Range`](/cells/python-net/es/aspose.cells/range) a partir de una dirección del rango.|
| [`get_sheet_by_code_name(self, code_name)`](/cells/python-net/es/aspose.cells/worksheetcollection/get_sheet_by_code_name/#str) | Obtiene la hoja de trabajo por el nombre del código.|
| [`sort_names(self)`](/cells/python-net/es/aspose.cells/worksheetcollection/sort_names/#) | Ordena los nombres definidos.|
| [`swap_sheet(self, sheet_index1, sheet_index2)`](/cells/python-net/es/aspose.cells/worksheetcollection/swap_sheet/#int-int) | Intercambia las dos hojas.|
| [`remove_by_name(self, name)`](/cells/python-net/es/aspose.cells/worksheetcollection/remove_by_name/#str) | Eliminar una hoja por nombre de hoja.(CELLSPYTHONNET-192)|
| [`remove_by_index(self, index)`](/cells/python-net/es/aspose.cells/worksheetcollection/remove_by_index/#int) | Eliminar hoja por hoja índice|
| [`remove_at(self, name)`](/cells/python-net/es/aspose.cells/worksheetcollection/remove_at/#str) | Elimina el elemento con un nombre especificado.|
| [`get_named_ranges(self)`](/cells/python-net/es/aspose.cells/worksheetcollection/get_named_ranges/#) | Obtiene todos los rangos con nombre predefinidos en la hoja de cálculo.|
| [`get_named_ranges_and_tables(self)`](/cells/python-net/es/aspose.cells/worksheetcollection/get_named_ranges_and_tables/#) | Obtiene todos los rangos con nombre predefinidos en la hoja de cálculo.|
| [`set_ole_size(self, start_row, end_row, start_column, end_column)`](/cells/python-net/es/aspose.cells/worksheetcollection/set_ole_size/#int-int-int-int) | Establece el tamaño mostrado cuando el archivo de libro de trabajo se utiliza como un objeto Ole.|
| [`clear_pivottables(self)`](/cells/python-net/es/aspose.cells/worksheetcollection/clear_pivottables/#) |Borra las tablas dinámicas de la hoja de cálculo.|
| [`refresh_all(self)`](/cells/python-net/es/aspose.cells/worksheetcollection/refresh_all/#) | Actualice todas las tablas dinámicas y gráficos con la fuente dinámica.|
| [`binary_search(self, item)`](/cells/python-net/es/aspose.cells/worksheetcollection/binary_search/#aspose.cells.worksheet) | Busca en toda la lista de la matriz ordenada un elemento utilizando el comparador predeterminado y devuelve el índice basado en cero del elemento.|



###  Ejemplo

```python
from aspose.cells import Workbook

workbook = Workbook()
sheets = workbook.worksheets
# Add a worksheet
sheets.add()
# Change the name of a worksheet
sheets[0].name = "First Sheet"
# Set the active sheet to the second worksheet
sheets.active_sheet_index = 1

```

###  Ver también
* módulo [`aspose.cells`](..)
* clase [`DocumentProperty`](/cells/python-net/es/aspose.cells.properties/documentproperty)
* clase [`Range`](/cells/python-net/es/aspose.cells/range)
* clase [`Worksheet`](/cells/python-net/es/aspose.cells/worksheet)
