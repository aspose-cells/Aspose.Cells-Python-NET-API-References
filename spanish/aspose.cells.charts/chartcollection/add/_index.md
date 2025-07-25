---
title: método add
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells.charts/chartcollection/add/
is_root: false
---
##  add(self, type, upper_left_row, upper_left_column, lower_right_row, lower_right_column) {#aspose.cells.charts.ChartType-int-int-int-int}
Agrega un gráfico a la colección.


###  Devoluciones

Índice de objeto [`Chart`](/cells/python-net/es/aspose.cells.charts/chart).


```python

def add(self, type, upper_left_row, upper_left_column, lower_right_row, lower_right_column):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| type | [`ChartType`](/cells/python-net/es/aspose.cells.charts/charttype) | Tipo de gráfico|
| upper_left_row | int | Índice de la fila superior izquierda.|
| upper_left_column | int | Índice de la columna superior izquierda.|
| lower_right_row | int | Índice de la fila inferior derecha|
| lower_right_column | int | Índice de la columna inferior derecha|


##  add(self, type, data_range, top_row, left_column, right_row, bottom_column) {#aspose.cells.charts.ChartType-str-int-int-int-int}
Agrega un gráfico a la colección.


###  Devoluciones

Índice de objeto [`Chart`](/cells/python-net/es/aspose.cells.charts/chart).


```python

def add(self, type, data_range, top_row, left_column, right_row, bottom_column):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| type | [`ChartType`](/cells/python-net/es/aspose.cells.charts/charttype) | Tipo de gráfico|
| data_range | str | Especifica el rango de datos del gráfico.|
| top_row | int | Índice de la fila superior izquierda.|
| left_column | int | Índice de la columna superior izquierda.|
| right_row | int | Índice de la fila inferior derecha|
| bottom_column | int | Índice de la columna inferior derecha|
###  Observaciones

NOTA: Este miembro ya no está disponible. En su lugar,
Por favor utilice la propiedad [`ChartCollection.add`](/cells/python-net/es/aspose.cells.charts/chartcollection/add).
 Esta propiedad será eliminada 12 meses después desde mayo de 2022.
Aspose le pide disculpas por cualquier inconveniente que pueda haber experimentado.

##  add(self, data, data_range, is_vertical, top_row, left_column, right_row, bottom_column) {#bytes-str-bool-int-int-int-int}
Agrega un gráfico con plantilla preestablecida.


###  Devoluciones

Índice de objeto [`Chart`](/cells/python-net/es/aspose.cells.charts/chart).


```python

def add(self, data, data_range, is_vertical, top_row, left_column, right_row, bottom_column):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| data | bytes | Los datos del archivo de plantilla de gráfico (.crtx).|
| data_range | str | Especifica el rango de datos del gráfico.|
| is_vertical | bool | Especifica si se debe trazar la serie a partir de un rango de valores de celda por fila o por columna.|
| top_row | int | Índice de la fila superior izquierda.|
| left_column | int | Índice de la columna superior izquierda.|
| right_row | int | Índice de la fila inferior derecha|
| bottom_column | int | Índice de la columna inferior derecha|


##  add(self, type, data_range, is_vertical, top_row, left_column, right_row, bottom_column) {#aspose.cells.charts.ChartType-str-bool-int-int-int-int}
Agrega un gráfico a la colección.


###  Devoluciones

Índice de objeto [`Chart`](/cells/python-net/es/aspose.cells.charts/chart).


```python

def add(self, type, data_range, is_vertical, top_row, left_column, right_row, bottom_column):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| type | [`ChartType`](/cells/python-net/es/aspose.cells.charts/charttype) | Tipo de gráfico|
| data_range | str | Especifica el rango de datos del gráfico.|
| is_vertical | bool | Especifica si se debe trazar la serie a partir de un rango de valores de celda por fila o por columna.|
| top_row | int | Índice de la fila superior izquierda.|
| left_column | int | Índice de la columna superior izquierda.|
| right_row | int | Índice de la fila inferior derecha|
| bottom_column | int | Índice de la columna inferior derecha|



###  Ver también
* módulo [`aspose.cells.charts`](../../)
* clase [`Chart`](/cells/python-net/es/aspose.cells.charts/chart)
* clase [`ChartCollection`](/cells/python-net/es/aspose.cells.charts/chartcollection)
