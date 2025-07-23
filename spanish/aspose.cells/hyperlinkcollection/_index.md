---
title: HyperlinkCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 830
url: /es/aspose.cells/hyperlinkcollection/
is_root: false
---
##  HyperlinkCollection clase
Encapsula una colección de [`Hyperlink`](/cells/python-net/es/aspose.cells/hyperlink) objetos.



El tipo HyperlinkCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells/hyperlinkcollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matrices.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`add(self, first_row, first_column, total_rows, total_columns, address)`](/cells/python-net/es/aspose.cells/hyperlinkcollection/add/#int-int-int-int-str) | Agrega un hipervínculo a una celda específica o a un rango de celdas.|
| [`add(self, cell_name, total_rows, total_columns, address)`](/cells/python-net/es/aspose.cells/hyperlinkcollection/add/#str-int-int-str) | Agrega un hipervínculo a una celda específica o a un rango de celdas.|
| [`add(self, start_cell_name, end_cell_name, address, text_to_display, screen_tip)`](/cells/python-net/es/aspose.cells/hyperlinkcollection/add/#str-str-str-str-str) | Agrega un hipervínculo a una celda específica o a un rango de celdas.|
| [`copy_to(self, array)`](/cells/python-net/es/aspose.cells/hyperlinkcollection/copy_to/#list) |Copia la lista de matrices completa a una lista de matrices unidimensional compatible, comenzando por el principio de la lista de matrices de destino.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/es/aspose.cells/hyperlinkcollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matrices a una lista de matrices unidimensionales compatible, comenzando en el índice especificado de la lista de matrices de destino.|
| [`index_of(self, item, index)`](/cells/python-net/es/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.hyperlink-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de la matriz que se extiende desde el índice especificado hasta el último elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.hyperlink-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene la cantidad especificada de elementos.|
| [`last_index_of(self, item)`](/cells/python-net/es/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.hyperlink) | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista de la matriz.|
| [`last_index_of(self, item, index)`](/cells/python-net/es/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.hyperlink-int) |Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.hyperlink-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que contiene la cantidad especificada de elementos y termina en el índice especificado.|
| [`binary_search(self, item)`](/cells/python-net/es/aspose.cells/hyperlinkcollection/binary_search/#aspose.cells.hyperlink) | Busca en toda la lista de la matriz ordenada un elemento utilizando el comparador predeterminado y devuelve el índice basado en cero del elemento.|



###  Ejemplo

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Get Hyperlinks Collection
hyperlinks = worksheet.hyperlinks
# Adding a hyperlink to a URL at "A1" cell
hyperlinks.add("A1", 1, 1, "http://www.aspose.com")
# Saving the Excel file
workbook.save("book1.xls")

```

###  Ver también
* módulo [`aspose.cells`](..)
* clase [`Hyperlink`](/cells/python-net/es/aspose.cells/hyperlink)
