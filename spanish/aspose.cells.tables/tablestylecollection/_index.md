---
title: TableStyleCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 60
url: /es/aspose.cells.tables/tablestylecollection/
is_root: false
---
##  TableStyleCollection clase
Representa todos los estilos de tabla personalizados.



El tipo TableStyleCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [default_table_style_name](/cells/python-net/es/aspose.cells.tables/tablestylecollection/default_table_style_name) | Obtiene y establece el nombre de estilo predeterminado de la tabla.|
| [default_pivot_style_name](/cells/python-net/es/aspose.cells.tables/tablestylecollection/default_pivot_style_name) | Obtiene y establece el nombre de estilo predeterminado de la tabla dinámica.|
| [capacity](/cells/python-net/es/aspose.cells.tables/tablestylecollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matrices.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/es/aspose.cells.tables/tablestylecollection/copy_to/#list) |Copia la lista de matrices completa a una lista de matrices unidimensional compatible, comenzando por el principio de la lista de matrices de destino.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/es/aspose.cells.tables/tablestylecollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matrices a una lista de matrices unidimensionales compatible, comenzando en el índice especificado de la lista de matrices de destino.|
| [`index_of(self, item, index)`](/cells/python-net/es/aspose.cells.tables/tablestylecollection/index_of/#aspose.cells.tables.tablestyle-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de la matriz que se extiende desde el índice especificado hasta el último elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.tables/tablestylecollection/index_of/#aspose.cells.tables.tablestyle-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene la cantidad especificada de elementos.|
| [`last_index_of(self, item)`](/cells/python-net/es/aspose.cells.tables/tablestylecollection/last_index_of/#aspose.cells.tables.tablestyle) | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista de la matriz.|
| [`last_index_of(self, item, index)`](/cells/python-net/es/aspose.cells.tables/tablestylecollection/last_index_of/#aspose.cells.tables.tablestyle-int) |Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.tables/tablestylecollection/last_index_of/#aspose.cells.tables.tablestyle-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que contiene la cantidad especificada de elementos y termina en el índice especificado.|
| [`add_table_style(self, name)`](/cells/python-net/es/aspose.cells.tables/tablestylecollection/add_table_style/#str) | Agrega un estilo de tabla personalizado.|
| [`add_pivot_table_style(self, name)`](/cells/python-net/es/aspose.cells.tables/tablestylecollection/add_pivot_table_style/#str) | Agrega un estilo de tabla dinámica personalizado.|
| [`get(self, name)`](/cells/python-net/es/aspose.cells.tables/tablestylecollection/get/#str) | Obtiene el estilo de tabla por nombre.|
| [`get_builtin_table_style(self, type)`](/cells/python-net/es/aspose.cells.tables/tablestylecollection/get_builtin_table_style/#aspose.cells.tables.tablestyletype) | Obtiene el estilo de tabla incorporado|
| [`binary_search(self, item)`](/cells/python-net/es/aspose.cells.tables/tablestylecollection/binary_search/#aspose.cells.tables.tablestyle) | Busca en toda la lista de la matriz ordenada un elemento utilizando el comparador predeterminado y devuelve el índice basado en cero del elemento.|



###  Ver también
* módulo [`aspose.cells.tables`](..)
