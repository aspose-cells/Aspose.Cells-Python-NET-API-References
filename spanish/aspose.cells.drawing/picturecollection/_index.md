---
title: PictureCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 440
url: /es/aspose.cells.drawing/picturecollection/
is_root: false
---
##  PictureCollection clase
Encapsula una colección de [`Picture`](/cells/python-net/es/aspose.cells.drawing/picture) objetos.



El tipo PictureCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells.drawing/picturecollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matrices.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream)`](/cells/python-net/es/aspose.cells.drawing/picturecollection/add/#int-int-int-int-io.rawiobase) | Añade una imagen a la colección.|
| [`add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name)`](/cells/python-net/es/aspose.cells.drawing/picturecollection/add/#int-int-int-int-str) | Añade una imagen a la colección.|
| [`add(self, upper_left_row, upper_left_column, stream)`](/cells/python-net/es/aspose.cells.drawing/picturecollection/add/#int-int-io.rawiobase) | Añade una imagen a la colección.|
| [`add(self, upper_left_row, upper_left_column, file_name)`](/cells/python-net/es/aspose.cells.drawing/picturecollection/add/#int-int-str) | Añade una imagen a la colección.|
| [`add(self, upper_left_row, upper_left_column, stream, width_scale, height_scale)`](/cells/python-net/es/aspose.cells.drawing/picturecollection/add/#int-int-io.rawiobase-int-int) | Añade una imagen a la colección.|
| [`add(self, upper_left_row, upper_left_column, file_name, width_scale, height_scale)`](/cells/python-net/es/aspose.cells.drawing/picturecollection/add/#int-int-str-int-int) | Añade una imagen a la colección.|
| [`copy_to(self, array)`](/cells/python-net/es/aspose.cells.drawing/picturecollection/copy_to/#list) |Copia la lista de matrices completa a una lista de matrices unidimensional compatible, comenzando por el principio de la lista de matrices de destino.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/es/aspose.cells.drawing/picturecollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matrices a una lista de matrices unidimensionales compatible, comenzando en el índice especificado de la lista de matrices de destino.|
| [`index_of(self, item, index)`](/cells/python-net/es/aspose.cells.drawing/picturecollection/index_of/#aspose.cells.drawing.picture-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de la matriz que se extiende desde el índice especificado hasta el último elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.drawing/picturecollection/index_of/#aspose.cells.drawing.picture-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene la cantidad especificada de elementos.|
| [`last_index_of(self, item)`](/cells/python-net/es/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture) | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista de la matriz.|
| [`last_index_of(self, item, index)`](/cells/python-net/es/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture-int) |Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que contiene la cantidad especificada de elementos y termina en el índice especificado.|
| [`camera(self, row, column, range)`](/cells/python-net/es/aspose.cells.drawing/picturecollection/camera/#int-int-str) | Toma una fotografía del rango.|
| [`binary_search(self, item)`](/cells/python-net/es/aspose.cells.drawing/picturecollection/binary_search/#aspose.cells.drawing.picture) | Busca en toda la lista de la matriz ordenada un elemento utilizando el comparador predeterminado y devuelve el índice basado en cero del elemento.|



###  Ejemplo

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# get PictureCollection
pictures = workbook.worksheets[0].pictures
# do your business
# Save the excel file.
workbook.save("result.xlsx")

```

###  Ver también
* módulo [`aspose.cells.drawing`](..)
* clase [`Picture`](/cells/python-net/es/aspose.cells.drawing/picture)
