---
title: TrendlineCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 350
url: /es/aspose.cells.charts/trendlinecollection/
is_root: false
---
##  TrendlineCollection clase
Representa una colección de todos los [`Trendline`](/cells/python-net/es/aspose.cells.charts/trendline) objetos para la serie de datos especificada.



El tipo TrendlineCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells.charts/trendlinecollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matrices.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [`add(self, type)`](/cells/python-net/es/aspose.cells.charts/trendlinecollection/add/#aspose.cells.charts.trendlinetype) | Agrega un objeto [`Trendline`](/cells/python-net/es/aspose.cells.charts/trendline) a esta colección con el tipo especificado.|
| [`add(self, type, name)`](/cells/python-net/es/aspose.cells.charts/trendlinecollection/add/#aspose.cells.charts.trendlinetype-str) | Agrega un objeto [`Trendline`](/cells/python-net/es/aspose.cells.charts/trendline) a esta colección con el tipo y nombre especificados.|
| [`copy_to(self, array)`](/cells/python-net/es/aspose.cells.charts/trendlinecollection/copy_to/#list) |Copia la lista de matrices completa a una lista de matrices unidimensional compatible, comenzando por el principio de la lista de matrices de destino.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/es/aspose.cells.charts/trendlinecollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matrices a una lista de matrices unidimensionales compatible, comenzando en el índice especificado de la lista de matrices de destino.|
| [`index_of(self, item, index)`](/cells/python-net/es/aspose.cells.charts/trendlinecollection/index_of/#aspose.cells.charts.trendline-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de la matriz que se extiende desde el índice especificado hasta el último elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.charts/trendlinecollection/index_of/#aspose.cells.charts.trendline-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la primera ocurrencia dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene la cantidad especificada de elementos.|
| [`last_index_of(self, item)`](/cells/python-net/es/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.trendline) | Busca el objeto especificado y devuelve el índice basado en cero de la última aparición dentro de toda la lista de la matriz.|
| [`last_index_of(self, item, index)`](/cells/python-net/es/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.trendline-int) |Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/es/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.trendline-int-int) | Busca el objeto especificado y devuelve el índice basado en cero de la última ocurrencia dentro del rango de elementos en la lista de matriz que contiene la cantidad especificada de elementos y termina en el índice especificado.|
| [`binary_search(self, item)`](/cells/python-net/es/aspose.cells.charts/trendlinecollection/binary_search/#aspose.cells.charts.trendline) | Busca en toda la lista de la matriz ordenada un elemento utilizando el comparador predeterminado y devuelve el índice basado en cero del elemento.|



###  Ejemplo

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType, TrendlineType
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Excel object
sheetIndex = workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[sheetIndex]
worksheet.cells.get("A1").put_value(50)
worksheet.cells.get("A2").put_value(100)
worksheet.cells.get("A3").put_value(150)
worksheet.cells.get("A4").put_value(200)
worksheet.cells.get("B1").put_value(60)
worksheet.cells.get("B2").put_value(32)
worksheet.cells.get("B3").put_value(50)
worksheet.cells.get("B4").put_value(40)
# Adding a chart to the worksheet
chartIndex = workbook.worksheets[0].charts.add(ChartType.COLUMN, 3, 3, 15, 10)
chart = workbook.worksheets[0].charts[chartIndex]
chart.n_series.add("A1:a3", True)
chart.n_series[0].trend_lines.add(TrendlineType.LINEAR, "MyTrendLine")
line = chart.n_series[0].trend_lines[0]
line.display_equation = True
line.display_r_squared = True
line.color = Color.red

```

###  Ver también
* módulo [`aspose.cells.charts`](..)
* clase [`Trendline`](/cells/python-net/es/aspose.cells.charts/trendline)
