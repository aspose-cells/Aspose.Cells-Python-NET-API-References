---
title: TextBoxCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 670
url: /es/aspose.cells.drawing/textboxcollection/
is_root: false
---
##  TextBoxCollection clase
Encapsula una colección de [`TextBox`](/cells/python-net/es/aspose.cells.drawing/textbox) objetos.



El tipo TextBoxCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells.drawing/textboxcollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matrices.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/es/aspose.cells.drawing/textboxcollection/copy_to/#list) |Copia la lista de matrices completa a una lista de matrices unidimensional compatible, comenzando por el principio de la lista de matrices de destino.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/es/aspose.cells.drawing/textboxcollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matrices a una lista de matrices unidimensionales compatible, comenzando en el índice especificado de la lista de matrices de destino.|
| [`index_of(self, item, index)`](/cells/python-net/es/aspose.cells.drawing/textboxcollection/index_of/#aspose.cells.drawing.textbox-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de la matriz que se extiende desde el índice especificado hasta el último elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.drawing/textboxcollection/index_of/#aspose.cells.drawing.textbox-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene la cantidad especificada de elementos.|
| [`last_index_of(self, item)`](/cells/python-net/es/aspose.cells.drawing/textboxcollection/last_index_of/#aspose.cells.drawing.textbox) | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista de la matriz.|
| [`last_index_of(self, item, index)`](/cells/python-net/es/aspose.cells.drawing/textboxcollection/last_index_of/#aspose.cells.drawing.textbox-int) |Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.drawing/textboxcollection/last_index_of/#aspose.cells.drawing.textbox-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que contiene la cantidad especificada de elementos y termina en el índice especificado.|
| [`get(self, name)`](/cells/python-net/es/aspose.cells.drawing/textboxcollection/get/#str) | Obtiene el elemento [`TextBox`](/cells/python-net/es/aspose.cells.drawing/textbox) por el nombre.|
| [`add(self, upper_left_row, upper_left_column, height, width)`](/cells/python-net/es/aspose.cells.drawing/textboxcollection/add/#int-int-int-int) | Agrega un cuadro de texto a la colección.|
| [`binary_search(self, item)`](/cells/python-net/es/aspose.cells.drawing/textboxcollection/binary_search/#aspose.cells.drawing.textbox) | Busca en toda la lista de la matriz ordenada un elemento utilizando el comparador predeterminado y devuelve el índice basado en cero del elemento.|



###  Ejemplo

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# get collection object
textBoxCollection = workbook.worksheets[0].text_boxes
# add a textbox
textBoxCollection.add(1, 1, 50, 100)
for tbox in textBoxCollection:
    pass

```

###  Ver también
* módulo [`aspose.cells.drawing`](..)
* clase [`TextBox`](/cells/python-net/es/aspose.cells.drawing/textbox)
