---
title: CellWatchCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 150
url: /es/aspose.cells/cellwatchcollection/
is_root: false
---
##  CellWatchCollection clase
Representa la colección de celdas en esta hoja de cálculo que se están observando en la 'ventana de observación'.



El tipo CellWatchCollection expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self)`](/cells/python-net/es/aspose.cells/cellwatchcollection/__init__/#) | Construye una nueva instancia de CellWatchCollection|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells/cellwatchcollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matrices.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`add(self, row, column)`](/cells/python-net/es/aspose.cells/cellwatchcollection/add/#int-int) | Agrega [`CellWatch`](/cells/python-net/es/aspose.cells/cellwatch) con fila y columna.|
| [`add(self, cell_name)`](/cells/python-net/es/aspose.cells/cellwatchcollection/add/#str) | Agrega [`CellWatch`](/cells/python-net/es/aspose.cells/cellwatch) con el nombre de la celda.|
| [`copy_to(self, array)`](/cells/python-net/es/aspose.cells/cellwatchcollection/copy_to/#list) |Copia la lista de matrices completa a una lista de matrices unidimensional compatible, comenzando por el principio de la lista de matrices de destino.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/es/aspose.cells/cellwatchcollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matrices a una lista de matrices unidimensionales compatible, comenzando en el índice especificado de la lista de matrices de destino.|
| [`index_of(self, item, index)`](/cells/python-net/es/aspose.cells/cellwatchcollection/index_of/#aspose.cells.cellwatch-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de la matriz que se extiende desde el índice especificado hasta el último elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells/cellwatchcollection/index_of/#aspose.cells.cellwatch-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene la cantidad especificada de elementos.|
| [`last_index_of(self, item)`](/cells/python-net/es/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch) | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista de la matriz.|
| [`last_index_of(self, item, index)`](/cells/python-net/es/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch-int) |Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que contiene la cantidad especificada de elementos y termina en el índice especificado.|
| [`get(self, cell_name)`](/cells/python-net/es/aspose.cells/cellwatchcollection/get/#str) | Obtiene y establece [`CellWatch`](/cells/python-net/es/aspose.cells/cellwatch) por el nombre de la celda.|
| [`binary_search(self, item)`](/cells/python-net/es/aspose.cells/cellwatchcollection/binary_search/#aspose.cells.cellwatch) | Busca en toda la lista de la matriz ordenada un elemento utilizando el comparador predeterminado y devuelve el índice basado en cero del elemento.|



###  Ejemplo

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet.
sheet = workbook.worksheets[0]
#  Add Cell Watch Item into the watch window
sheet.cell_watches.add("B2")

```

###  Ver también
* módulo [`aspose.cells`](..)
* clase [`CellWatch`](/cells/python-net/es/aspose.cells/cellwatch)
