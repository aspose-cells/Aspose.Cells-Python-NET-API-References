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
| [capacity](/cells/python-net/es/aspose.cells.charts/chartcollection/capacity) | Obtiene o establece el número de elementos que puede contener la lista de matriz.|


###  Métodos
| Método| Descripción|
| :- | :- |
| [add](/cells/python-net/es/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.ChartType-int-int-int-int) | Agrega un gráfico a la colección.|
| [add](/cells/python-net/es/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.ChartType-str-int-int-int-int) | Agrega un gráfico a la colección.|
| [add](/cells/python-net/es/aspose.cells.charts/chartcollection/add/#bytes-str-bool-int-int-int-int) | Agrega un gráfico con una plantilla preestablecida.|
| [add](/cells/python-net/es/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.ChartType-str-bool-int-int-int-int) | Agrega un gráfico a la colección.|
| [get](/cells/python-net/es/aspose.cells.charts/chartcollection/get/#int) | Agregue API for Python a través de .Net, ya que este [índice int] no es compatible|
| [get](/cells/python-net/es/aspose.cells.charts/chartcollection/get/#str) | Agregue API for Python a través de .Net, ya que este [gráfico de cadenas] no es compatible|
| [copy_to](/cells/python-net/es/aspose.cells.charts/chartcollection/copy_to/#list) | Copia toda la lista de matrices en una lista de matrices unidimensional compatible, comenzando desde el principio de la lista de matrices de destino.|
| [copy_to](/cells/python-net/es/aspose.cells.charts/chartcollection/copy_to/#int-list-int-int) | Copia un rango de elementos de la lista de matriz a una lista de matriz unidimensional compatible, comenzando en el índice especificado de la lista de matriz de destino.|
| [index_of](/cells/python-net/es/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.Chart-int) | Busca el objeto especificado y devuelve el índice de base cero de la primera aparición dentro del rango de elementos en la lista de matriz que se extiende desde el índice especificado hasta el último elemento.|
| [index_of](/cells/python-net/es/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.Chart-int-int) |Busca el objeto especificado y devuelve el índice de base cero de la primera aparición dentro del rango de elementos en la lista de matriz que comienza en el índice especificado y contiene el número especificado de elementos.|
| [last_index_of](/cells/python-net/es/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.Chart) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro de toda la lista de la matriz.|
| [last_index_of](/cells/python-net/es/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.Chart-int) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro del rango de elementos en la lista de matriz que se extiende desde el primer elemento hasta el índice especificado.|
| [last_index_of](/cells/python-net/es/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.Chart-int-int) | Busca el objeto especificado y devuelve el índice de base cero de la última aparición dentro del rango de elementos en la lista de matriz que contiene el número especificado de elementos y termina en el índice especificado.|
| [add_floating_chart](/cells/python-net/es/aspose.cells.charts/chartcollection/add_floating_chart/#aspose.cells.charts.ChartType-int-int-int-int) | Agrega un gráfico a la colección.|
| [binary_search](/cells/python-net/es/aspose.cells.charts/chartcollection/binary_search/#aspose.cells.charts.Chart) | Busca un elemento en toda la lista de matriz ordenada utilizando el comparador predeterminado y devuelve el índice de base cero del elemento.|



###  Ejemplo

```python
from aspose.cells import Workbook

workbook = Workbook()
charts = workbook.worksheets[0].charts

```

###  Ver también
* módulo [`aspose.cells.charts`](..)
* clase [`Chart`](/cells/python-net/es/aspose.cells.charts/chart)
