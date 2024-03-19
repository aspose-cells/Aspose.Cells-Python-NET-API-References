---
title: CellWatchCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 180
url: /es/aspose.cells/cellwatchcollection/
is_root: false
---
##  CellWatchCollection clase
Representa la colección de celdas de esta hoja de trabajo que se están observando en la "ventana de observación".



El tipo CellWatchCollection expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [__init__](/cells/python-net/es/aspose.cells/cellwatchcollection/__init__/#) | Construye una nueva instancia de CellWatchCollection|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells/cellwatchcollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matriz.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [add](/cells/python-net/es/aspose.cells/cellwatchcollection/add/#int-int) | Agrega [`CellWatch`](/cells/python-net/es/aspose.cells/cellwatch) con fila y columna.|
| [add](/cells/python-net/es/aspose.cells/cellwatchcollection/add/#str) | Agrega [`CellWatch`](/cells/python-net/es/aspose.cells/cellwatch) con el nombre de la celda.|
| [copy_to](/cells/python-net/es/aspose.cells/cellwatchcollection/copy_to/#list) | Copia toda la lista de matrices en una lista de matrices unidimensional compatible, comenzando desde el principio de la lista de matrices de destino.|
| [copy_to](/cells/python-net/es/aspose.cells/cellwatchcollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matriz a una lista de matriz unidimensional compatible, comenzando en el índice especificado de la lista de matriz de destino.|
| [index_of](/cells/python-net/es/aspose.cells/cellwatchcollection/index_of/#aspose.cells.CellWatch-int) | Busca el objeto especificado y devuelve el índice de base cero de la primera aparición dentro del rango de elementos en la lista de matriz que se extiende desde el índice especificado hasta el último elemento.|
| [index_of](/cells/python-net/es/aspose.cells/cellwatchcollection/index_of/#aspose.cells.CellWatch-int-int) |Busca el objeto especificado y devuelve el índice de base cero de la primera aparición dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene el número especificado de elementos.|
| [last_index_of](/cells/python-net/es/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.CellWatch) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro de toda la lista de la matriz.|
| [last_index_of](/cells/python-net/es/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.CellWatch-int) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [last_index_of](/cells/python-net/es/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.CellWatch-int-int) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro del rango de elementos en la lista de matriz que contiene el número especificado de elementos y termina en el índice especificado.|
| [binary_search](/cells/python-net/es/aspose.cells/cellwatchcollection/binary_search/#aspose.cells.CellWatch) | Busca un elemento en toda la lista de matriz ordenada utilizando el comparador predeterminado y devuelve el índice de base cero del elemento.|



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
