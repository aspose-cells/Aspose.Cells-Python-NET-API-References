---
title: CommentCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 300
url: /es/aspose.cells/commentcollection/
is_root: false
---
##  CommentCollection clase
Encapsula una colección de [`Comment`](/cells/python-net/es/aspose.cells/comment) objetos.



El tipo CommentCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells/commentcollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matriz.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [add_threaded_comment](/cells/python-net/es/aspose.cells/commentcollection/add_threaded_comment/#int-int-str-aspose.cells.ThreadedCommentAuthor) | Agrega un comentario encadenado.|
| [add_threaded_comment](/cells/python-net/es/aspose.cells/commentcollection/add_threaded_comment/#str-str-aspose.cells.ThreadedCommentAuthor) | Agrega un comentario encadenado.|
| [get_threaded_comments](/cells/python-net/es/aspose.cells/commentcollection/get_threaded_comments/#int-int) | Obtiene los comentarios encadenados por índice de fila y columna.|
| [get_threaded_comments](/cells/python-net/es/aspose.cells/commentcollection/get_threaded_comments/#str) |Obtiene los comentarios encadenados por nombre de celda.|
| [add](/cells/python-net/es/aspose.cells/commentcollection/add/#int-int) | Agrega un comentario a la colección.|
| [add](/cells/python-net/es/aspose.cells/commentcollection/add/#str) | Agrega un comentario a la colección.|
| [remove_at](/cells/python-net/es/aspose.cells/commentcollection/remove_at/#str) | Elimina el comentario de la celda específica.|
| [remove_at](/cells/python-net/es/aspose.cells/commentcollection/remove_at/#int-int) | Elimina el comentario de la celda específica.|
| [copy_to](/cells/python-net/es/aspose.cells/commentcollection/copy_to/#list) | Copia toda la lista de matrices en una lista de matrices unidimensional compatible, comenzando desde el principio de la lista de matrices de destino.|
| [copy_to](/cells/python-net/es/aspose.cells/commentcollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matriz a una lista de matriz unidimensional compatible, comenzando en el índice especificado de la lista de matriz de destino.|
| [index_of](/cells/python-net/es/aspose.cells/commentcollection/index_of/#aspose.cells.Comment-int) | Busca el objeto especificado y devuelve el índice de base cero de la primera aparición dentro del rango de elementos en la lista de matriz que se extiende desde el índice especificado hasta el último elemento.|
| [index_of](/cells/python-net/es/aspose.cells/commentcollection/index_of/#aspose.cells.Comment-int-int) |Busca el objeto especificado y devuelve el índice de base cero de la primera aparición dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene el número especificado de elementos.|
| [last_index_of](/cells/python-net/es/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro de toda la lista de la matriz.|
| [last_index_of](/cells/python-net/es/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment-int) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [last_index_of](/cells/python-net/es/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment-int-int) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro del rango de elementos en la lista de matriz que contiene el número especificado de elementos y termina en el índice especificado.|
| [binary_search](/cells/python-net/es/aspose.cells/commentcollection/binary_search/#aspose.cells.Comment) | Busca un elemento en toda la lista de matriz ordenada utilizando el comparador predeterminado y devuelve el índice de base cero del elemento.|



###  Ejemplo

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments

```

###  Ver también
* módulo [`aspose.cells`](..)
* clase [`Comment`](/cells/python-net/es/aspose.cells/comment)
