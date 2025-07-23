---
title: ChartCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 60
url: /es/aspose.cells.charts/chartcollection/
is_root: false
---
##  ChartCollection clase
Encapsula una colección de [`Chart`](/cells/python-net/es/aspose.cells.charts/chart) objetos.



El tipo ChartCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells.charts/chartcollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matrices.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`add(self, type, upper_left_row, upper_left_column, lower_right_row, lower_right_column)`](/cells/python-net/es/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-int-int-int-int) | Agrega un gráfico a la colección.|
| [`add(self, type, data_range, top_row, left_column, right_row, bottom_column)`](/cells/python-net/es/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-str-int-int-int-int) | Agrega un gráfico a la colección.|
| [`add(self, data, data_range, is_vertical, top_row, left_column, right_row, bottom_column)`](/cells/python-net/es/aspose.cells.charts/chartcollection/add/#bytes-str-bool-int-int-int-int) | Agrega un gráfico con plantilla preestablecida.|
| [`add(self, type, data_range, is_vertical, top_row, left_column, right_row, bottom_column)`](/cells/python-net/es/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-str-bool-int-int-int-int) | Agrega un gráfico a la colección.|
| [`get(self, index)`](/cells/python-net/es/aspose.cells.charts/chartcollection/get/#int) | Agregue API for Python a través de .Net.ya que este [int index] no es compatible|
| [`get(self, name)`](/cells/python-net/es/aspose.cells.charts/chartcollection/get/#str) | Agregue API for Python a través de .Net.ya que este [string Chart] no es compatible|
| [`copy_to(self, array)`](/cells/python-net/es/aspose.cells.charts/chartcollection/copy_to/#list) |Copia la lista de matrices completa a una lista de matrices unidimensional compatible, comenzando por el principio de la lista de matrices de destino.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/es/aspose.cells.charts/chartcollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matrices a una lista de matrices unidimensionales compatible, comenzando en el índice especificado de la lista de matrices de destino.|
| [`index_of(self, item, index)`](/cells/python-net/es/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.chart-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de la matriz que se extiende desde el índice especificado hasta el último elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.chart-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene la cantidad especificada de elementos.|
| [`last_index_of(self, item)`](/cells/python-net/es/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart) | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista de la matriz.|
| [`last_index_of(self, item, index)`](/cells/python-net/es/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart-int) |Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que contiene la cantidad especificada de elementos y termina en el índice especificado.|
| [`add_floating_chart(self, type, left, top, width, height)`](/cells/python-net/es/aspose.cells.charts/chartcollection/add_floating_chart/#aspose.cells.charts.charttype-int-int-int-int) | Agrega un gráfico a la colección.|
| [`binary_search(self, item)`](/cells/python-net/es/aspose.cells.charts/chartcollection/binary_search/#aspose.cells.charts.chart) | Busca en toda la lista de la matriz ordenada un elemento utilizando el comparador predeterminado y devuelve el índice basado en cero del elemento.|



###  Ejemplo

```python
from aspose.cells import Workbook

workbook = Workbook()
charts = workbook.worksheets[0].charts

```

###  Ver también
* módulo [`aspose.cells.charts`](..)
* clase [`Chart`](/cells/python-net/es/aspose.cells.charts/chart)
