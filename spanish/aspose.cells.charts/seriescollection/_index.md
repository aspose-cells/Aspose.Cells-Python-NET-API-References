---
title: SeriesCollection clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 250
url: /es/aspose.cells.charts/seriescollection/
is_root: false
---
##  SeriesCollection clase
Encapsula una colección de [`Series`](/cells/python-net/es/aspose.cells.charts/series) objetos.



El tipo SeriesCollection expone los siguientes miembros:

###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [category_data](/cells/python-net/es/aspose.cells.charts/seriescollection/category_data) | Obtiene o establece el rango de valores del eje de categoría.<br/> Puede ser un rango de celdas (como "d1:e10"),<br/> o una secuencia de valores (como "{2,6,8,10}").|
| [second_category_data](/cells/python-net/es/aspose.cells.charts/seriescollection/second_category_data) | Obtiene o establece el rango de valores del eje de segunda categoría.<br/> Puede ser un rango de celdas (como "d1:e10"),<br/> o una secuencia de valores (como "{2,6,8,10}").<br/> Solo afecta cuando algunas ASeries trazan en el segundo eje.|
| [is_color_varied](/cells/python-net/es/aspose.cells.charts/seriescollection/is_color_varied) |Representa si se varía el color de los puntos.|
| [capacity](/cells/python-net/es/aspose.cells.charts/seriescollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matriz.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [add](/cells/python-net/es/aspose.cells.charts/seriescollection/add/#str-bool) | Agrega la colección [`Series`](/cells/python-net/es/aspose.cells.charts/series) a un gráfico.|
| [add](/cells/python-net/es/aspose.cells.charts/seriescollection/add/#str-bool-bool) | Agrega la colección [`Series`](/cells/python-net/es/aspose.cells.charts/series) a un gráfico.|
| [copy_to](/cells/python-net/es/aspose.cells.charts/seriescollection/copy_to/#list) | Copia toda la lista de matrices en una lista de matrices unidimensional compatible, comenzando desde el principio de la lista de matrices de destino.|
| [copy_to](/cells/python-net/es/aspose.cells.charts/seriescollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matriz a una lista de matriz unidimensional compatible, comenzando en el índice especificado de la lista de matriz de destino.|
| [index_of](/cells/python-net/es/aspose.cells.charts/seriescollection/index_of/#aspose.cells.charts.Series-int) | Busca el objeto especificado y devuelve el índice de base cero de la primera aparición dentro del rango de elementos en la lista de matriz que se extiende desde el índice especificado hasta el último elemento.|
| [index_of](/cells/python-net/es/aspose.cells.charts/seriescollection/index_of/#aspose.cells.charts.Series-int-int) |Busca el objeto especificado y devuelve el índice de base cero de la primera aparición dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene el número especificado de elementos.|
| [last_index_of](/cells/python-net/es/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.Series) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro de toda la lista de la matriz.|
| [last_index_of](/cells/python-net/es/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.Series-int) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [last_index_of](/cells/python-net/es/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.Series-int-int) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro del rango de elementos en la lista de matriz que contiene el número especificado de elementos y termina en el índice especificado.|
| [get_series_by_order](/cells/python-net/es/aspose.cells.charts/seriescollection/get_series_by_order/#int) | Obtiene el elemento [`Series`](/cells/python-net/es/aspose.cells.charts/series) por orden.|
| [change_series_order](/cells/python-net/es/aspose.cells.charts/seriescollection/change_series_order/#int-int) | Cambia directamente el orden de las dos series.|
| [set_series_names](/cells/python-net/es/aspose.cells.charts/seriescollection/set_series_names/#int-str-bool) | Establece el nombre de todas las series del gráfico.|
| [add_r1c1](/cells/python-net/es/aspose.cells.charts/seriescollection/add_r1c1/#str-bool) | Agrega la colección [`Series`](/cells/python-net/es/aspose.cells.charts/series) a un gráfico.|
| [binary_search](/cells/python-net/es/aspose.cells.charts/seriescollection/binary_search/#aspose.cells.charts.Series) | Busca un elemento en toda la lista de matriz ordenada utilizando el comparador predeterminado y devuelve el índice de base cero del elemento.|



###  Ejemplo

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Excel object
sheetIndex = workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[sheetIndex]
# Adding a sample value to "A1" cell
worksheet.cells.get("A1").put_value(50)
# Adding a sample value to "A2" cell
worksheet.cells.get("A2").put_value(100)
# Adding a sample value to "A3" cell
worksheet.cells.get("A3").put_value(150)
# Adding a sample value to "A4" cell
worksheet.cells.get("A4").put_value(200)
# Adding a sample value to "B1" cell
worksheet.cells.get("B1").put_value(60)
# Adding a sample value to "B2" cell
worksheet.cells.get("B2").put_value(32)
# Adding a sample value to "B3" cell
worksheet.cells.get("B3").put_value(50)
# Adding a sample value to "B4" cell
worksheet.cells.get("B4").put_value(40)
# Adding a sample value to "C1" cell as category data
worksheet.cells.get("C1").put_value("Q1")
# Adding a sample value to "C2" cell as category data
worksheet.cells.get("C2").put_value("Q2")
# Adding a sample value to "C3" cell as category data
worksheet.cells.get("C3").put_value("Y1")
# Adding a sample value to "C4" cell as category data
worksheet.cells.get("C4").put_value("Y2")
# Adding a chart to the worksheet
chartIndex = worksheet.charts.add(ChartType.COLUMN, 5, 0, 15, 5)
# Accessing the instance of the newly added chart
chart = worksheet.charts[chartIndex]
# Adding NSeries (chart data source) to the chart ranging from "A1" cell to "B4"
chart.n_series.add("A1:B4", True)
# Setting the data source for the category data of NSeries
chart.n_series.category_data = "C1:C4"
# Saving the Excel file
workbook.save("book1.xls")

```

###  Ver también
* módulo [`aspose.cells.charts`](..)
* clase [`Series`](/cells/python-net/es/aspose.cells.charts/series)
