---
title: HorizontalPageBreakCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 770
url: /es/aspose.cells/horizontalpagebreakcollection/
is_root: false
---
##  HorizontalPageBreakCollection clase
Encapsula una colección de [`HorizontalPageBreak`](/cells/python-net/es/aspose.cells/horizontalpagebreak) objetos.



El tipo HorizontalPageBreakCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matrices.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`add(self, row, start_column, end_column)`](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/add/#int-int-int) | Agrega un salto de página horizontal a la colección.|
| [`add(self, row)`](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/add/#int) | Agrega un salto de página horizontal a la colección.|
| [`add(self, row, column)`](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/add/#int-int) | Agrega un salto de página horizontal a la colección.|
| [`add(self, cell_name)`](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/add/#str) | Agrega un salto de página horizontal a la colección.|
| [`copy_to(self, array)`](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/copy_to/#list) |Copia la lista de matrices completa a una lista de matrices unidimensional compatible, comenzando por el principio de la lista de matrices de destino.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matrices a una lista de matrices unidimensionales compatible, comenzando en el índice especificado de la lista de matrices de destino.|
| [`index_of(self, item, index)`](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/index_of/#aspose.cells.horizontalpagebreak-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de la matriz que se extiende desde el índice especificado hasta el último elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/index_of/#aspose.cells.horizontalpagebreak-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene la cantidad especificada de elementos.|
| [`last_index_of(self, item)`](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.horizontalpagebreak) | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista de la matriz.|
| [`last_index_of(self, item, index)`](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.horizontalpagebreak-int) |Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.horizontalpagebreak-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que contiene la cantidad especificada de elementos y termina en el índice especificado.|
| [`get(self, cell_name)`](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/get/#str) | Obtiene el elemento [`HorizontalPageBreak`](/cells/python-net/es/aspose.cells/horizontalpagebreak) con el nombre de celda especificado.|
| [`binary_search(self, item)`](/cells/python-net/es/aspose.cells/horizontalpagebreakcollection/binary_search/#aspose.cells.horizontalpagebreak) | Busca en toda la lista de la matriz ordenada un elemento utilizando el comparador predeterminado y devuelve el índice basado en cero del elemento.|



###  Ejemplo

```python
from aspose.cells import Workbook

excel = Workbook()
# Add a pagebreak at G5
excel.worksheets[0].horizontal_page_breaks.add("G5")
excel.worksheets[0].vertical_page_breaks.add("G5")

```

###  Ver también
* módulo [`aspose.cells`](..)
* clase [`HorizontalPageBreak`](/cells/python-net/es/aspose.cells/horizontalpagebreak)
