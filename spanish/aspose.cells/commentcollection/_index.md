---
title: CommentCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 270
url: /es/aspose.cells/commentcollection/
is_root: false
---
##  CommentCollection clase
Encapsula una colección de [`Comment`](/cells/python-net/es/aspose.cells/comment) objetos.



El tipo CommentCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells/commentcollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matrices.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`add_threaded_comment(self, row, column, text, author)`](/cells/python-net/es/aspose.cells/commentcollection/add_threaded_comment/#int-int-str-aspose.cells.threadedcommentauthor) | Agrega un comentario en hilo.|
| [`add_threaded_comment(self, cell_name, text, author)`](/cells/python-net/es/aspose.cells/commentcollection/add_threaded_comment/#str-str-aspose.cells.threadedcommentauthor) | Agrega un comentario en hilo.|
| [`get_threaded_comments(self, row, column)`](/cells/python-net/es/aspose.cells/commentcollection/get_threaded_comments/#int-int) | Obtiene los comentarios enhebrados por índice de fila y columna.|
| [`get_threaded_comments(self, cell_name)`](/cells/python-net/es/aspose.cells/commentcollection/get_threaded_comments/#str) | Obtiene los comentarios enhebrados por nombre de celda.|
| [`add(self, row, column)`](/cells/python-net/es/aspose.cells/commentcollection/add/#int-int) | Agrega un comentario a la colección.|
| [`add(self, cell_name)`](/cells/python-net/es/aspose.cells/commentcollection/add/#str) | Agrega un comentario a la colección.|
| [`get(self, row, column)`](/cells/python-net/es/aspose.cells/commentcollection/get/#int-int) | Agregar API for Python a través de .Net.ya que este [int, int] no es compatible|
| [`get(self, index)`](/cells/python-net/es/aspose.cells/commentcollection/get/#int) | Obtiene el elemento [`Comment`](/cells/python-net/es/aspose.cells/comment) en el índice especificado.|
| [`get(self, cell_name)`](/cells/python-net/es/aspose.cells/commentcollection/get/#str) | Obtiene el elemento [`Comment`](/cells/python-net/es/aspose.cells/comment) en la celda especificada.|
| [`remove_at(self, cell_name)`](/cells/python-net/es/aspose.cells/commentcollection/remove_at/#str) | Elimina el comentario de la celda específica.|
| [`remove_at(self, row, column)`](/cells/python-net/es/aspose.cells/commentcollection/remove_at/#int-int) | Elimina el comentario de la celda específica.|
| [`copy_to(self, array)`](/cells/python-net/es/aspose.cells/commentcollection/copy_to/#list) |Copia la lista de matrices completa a una lista de matrices unidimensional compatible, comenzando por el principio de la lista de matrices de destino.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/es/aspose.cells/commentcollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matrices a una lista de matrices unidimensionales compatible, comenzando en el índice especificado de la lista de matrices de destino.|
| [`index_of(self, item, index)`](/cells/python-net/es/aspose.cells/commentcollection/index_of/#aspose.cells.comment-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de la matriz que se extiende desde el índice especificado hasta el último elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells/commentcollection/index_of/#aspose.cells.comment-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene la cantidad especificada de elementos.|
| [`last_index_of(self, item)`](/cells/python-net/es/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment) | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista de la matriz.|
| [`last_index_of(self, item, index)`](/cells/python-net/es/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment-int) |Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que contiene la cantidad especificada de elementos y termina en el índice especificado.|
| [`binary_search(self, item)`](/cells/python-net/es/aspose.cells/commentcollection/binary_search/#aspose.cells.comment) | Busca en toda la lista de la matriz ordenada un elemento utilizando el comparador predeterminado y devuelve el índice basado en cero del elemento.|



###  Ejemplo

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments

```

###  Ver también
* módulo [`aspose.cells`](..)
* clase [`Comment`](/cells/python-net/es/aspose.cells/comment)
