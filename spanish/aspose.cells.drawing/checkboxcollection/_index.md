---
title: CheckBoxCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 100
url: /es/aspose.cells.drawing/checkboxcollection/
is_root: false
---
##  CheckBoxCollection clase
Representa una colección de [`CheckBox`](/cells/python-net/es/aspose.cells.drawing/checkbox) objetos en una hoja de cálculo.



El tipo CheckBoxCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells.drawing/checkboxcollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matrices.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/es/aspose.cells.drawing/checkboxcollection/copy_to/#list) |Copia la lista de matrices completa a una lista de matrices unidimensional compatible, comenzando por el principio de la lista de matrices de destino.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/es/aspose.cells.drawing/checkboxcollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matrices a una lista de matrices unidimensionales compatible, comenzando en el índice especificado de la lista de matrices de destino.|
| [`index_of(self, item, index)`](/cells/python-net/es/aspose.cells.drawing/checkboxcollection/index_of/#aspose.cells.drawing.checkbox-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de la matriz que se extiende desde el índice especificado hasta el último elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.drawing/checkboxcollection/index_of/#aspose.cells.drawing.checkbox-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene la cantidad especificada de elementos.|
| [`last_index_of(self, item)`](/cells/python-net/es/aspose.cells.drawing/checkboxcollection/last_index_of/#aspose.cells.drawing.checkbox) | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista de la matriz.|
| [`last_index_of(self, item, index)`](/cells/python-net/es/aspose.cells.drawing/checkboxcollection/last_index_of/#aspose.cells.drawing.checkbox-int) |Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.drawing/checkboxcollection/last_index_of/#aspose.cells.drawing.checkbox-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que contiene la cantidad especificada de elementos y termina en el índice especificado.|
| [`add(self, upper_left_row, upper_left_column, height, width)`](/cells/python-net/es/aspose.cells.drawing/checkboxcollection/add/#int-int-int-int) | Agrega una casilla de verificación a la colección.|
| [`binary_search(self, item)`](/cells/python-net/es/aspose.cells.drawing/checkboxcollection/binary_search/#aspose.cells.drawing.checkbox) | Busca en toda la lista de la matriz ordenada un elemento utilizando el comparador predeterminado y devuelve el índice basado en cero del elemento.|



###  Ejemplo

```python
from aspose.cells import Workbook

# Create a new Workbook.
workbook = Workbook()
# Get the first worksheet in the workbook.
sheet = workbook.worksheets[0]
index = sheet.check_boxes.add(15, 15, 20, 100)
checkBox = sheet.check_boxes[index]
checkBox.text = "Check Box 1"

```

###  Ver también
* módulo [`aspose.cells.drawing`](..)
* clase [`CheckBox`](/cells/python-net/es/aspose.cells.drawing/checkbox)
