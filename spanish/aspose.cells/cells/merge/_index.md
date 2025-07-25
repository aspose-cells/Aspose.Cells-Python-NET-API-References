---
title: método merge
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 800
url: /es/aspose.cells/cells/merge/
is_root: false
---
##  merge(self, first_row, first_column, total_rows, total_columns) {#int-int-int-int}
Fusiona un rango específico de celdas en una sola celda.



```python

def merge(self, first_row, first_column, total_rows, total_columns):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| first_row | int | Primera fila de este rango (basado en cero)|
| first_column | int | Primera columna de este rango (basado en cero)|
| total_rows | int |Número de filas (basado en uno)|
| total_columns | int | Número de columnas (basadas en una)|
###  Observaciones

Haga referencia a la celda fusionada a través de la dirección de la celda superior izquierda en el rango.

##  merge(self, first_row, first_column, total_rows, total_columns, merge_conflict) {#int-int-int-int-bool}

Fusiona un rango específico de celdas en una sola celda.



```python

def merge(self, first_row, first_column, total_rows, total_columns, merge_conflict):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| first_row | int | Primera fila de este rango (basado en cero)|
| first_column | int | Primera columna de este rango (basado en cero)|
| total_rows | int |Número de filas (basado en uno)|
| total_columns | int | Número de columnas (basadas en una)|
| merge_conflict | bool | Fusionar rangos fusionados en conflicto.|
###  Observaciones

Haga referencia a la celda fusionada a través de la dirección de la celda superior izquierda en el rango.
Si mergeConflict es verdadero y el rango fusionado entra en conflicto con otras celdas fusionadas,
Las demás celdas fusionadas se eliminarán automáticamente.

##  merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict) {#int-int-int-int-bool-bool}
Fusiona un rango específico de celdas en una sola celda.



```python

def merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| first_row | int | Primera fila de este rango (basado en cero)|
| first_column | int | Primera columna de este rango (basado en cero)|
| total_rows | int |Número de filas (basado en uno)|
| total_columns | int | Número de columnas (basadas en una)|
| check_conflict | bool | Indica si la verificación de celdas fusionadas interseca otras celdas fusionadas|
| merge_conflict | bool | Fusionar rangos fusionados en conflicto.|
###  Observaciones

Haga referencia a la celda fusionada a través de la dirección de la celda superior izquierda en el rango.
Si mergeConflict es verdadero y el rango fusionado entra en conflicto con otras celdas fusionadas,
Las demás celdas fusionadas se eliminarán automáticamente.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cells`](/cells/python-net/es/aspose.cells/cells)
