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
Representa una colección de todos los objetos [`Trendline`](/cells/python-net/es/aspose.cells.charts/trendline) de la serie de datos especificada.



El tipo TrendlineCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [capacity](/cells/python-net/es/aspose.cells.charts/trendlinecollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matriz.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [add](/cells/python-net/es/aspose.cells.charts/trendlinecollection/add/#aspose.cells.charts.TrendlineType) | Agrega un objeto [`Trendline`](/cells/python-net/es/aspose.cells.charts/trendline) a esta colección con el tipo especificado.|
| [add](/cells/python-net/es/aspose.cells.charts/trendlinecollection/add/#aspose.cells.charts.TrendlineType-str) | Agrega un objeto [`Trendline`](/cells/python-net/es/aspose.cells.charts/trendline) a esta colección con el tipo y nombre especificados.|
| [copy_to](/cells/python-net/es/aspose.cells.charts/trendlinecollection/copy_to/#list) | Copia toda la lista de matrices en una lista de matrices unidimensional compatible, comenzando desde el principio de la lista de matrices de destino.|
| [copy_to](/cells/python-net/es/aspose.cells.charts/trendlinecollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matriz a una lista de matriz unidimensional compatible, comenzando en el índice especificado de la lista de matriz de destino.|
| [index_of](/cells/python-net/es/aspose.cells.charts/trendlinecollection/index_of/#aspose.cells.charts.Trendline-int) | Busca el objeto especificado y devuelve el índice de base cero de la primera aparición dentro del rango de elementos en la lista de matriz que se extiende desde el índice especificado hasta el último elemento.|
| [index_of](/cells/python-net/es/aspose.cells.charts/trendlinecollection/index_of/#aspose.cells.charts.Trendline-int-int) |Busca el objeto especificado y devuelve el índice de base cero de la primera aparición dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene el número especificado de elementos.|
| [last_index_of](/cells/python-net/es/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.Trendline) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro de toda la lista de la matriz.|
| [last_index_of](/cells/python-net/es/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.Trendline-int) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [last_index_of](/cells/python-net/es/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.Trendline-int-int) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro del rango de elementos en la lista de matriz que contiene el número especificado de elementos y termina en el índice especificado.|
| [binary_search](/cells/python-net/es/aspose.cells.charts/trendlinecollection/binary_search/#aspose.cells.charts.Trendline) | Busca un elemento en toda la lista de matriz ordenada utilizando el comparador predeterminado y devuelve el índice de base cero del elemento.|



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
