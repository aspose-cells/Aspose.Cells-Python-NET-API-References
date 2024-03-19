---
title: método merge
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 780
url: /es/aspose.cells/cells/merge/
is_root: false
---
##  merge {#int-int-int-int}
Fusiona un rango específico de celdas en una sola celda.



```python
def merge(self, first_row, first_column, total_rows, total_columns):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| first_row | int | Primera fila de este rango (base cero)|
| first_column | int | Primera columna de este rango (base cero)|
| total_rows | int | Número de filas (una basada)|
| total_columns | int | Número de columnas (una basada)|
###  Observaciones

Haga referencia a la celda fusionada a través de la dirección de la celda superior izquierda en el rango.

##  merge {#int-int-int-int-bool}

Fusiona un rango específico de celdas en una sola celda.



```python
def merge(self, first_row, first_column, total_rows, total_columns, merge_conflict):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| first_row | int | Primera fila de este rango (base cero)|
| first_column | int | Primera columna de este rango (base cero)|
| total_rows | int | Número de filas (una basada)|
| total_columns | int | Número de columnas (una basada)|
| merge_conflict | bool | Fusionar rangos fusionados en conflicto.|
###  Observaciones

Haga referencia a la celda fusionada a través de la dirección de la celda superior izquierda en el rango.
Si mergeConflict es verdadero y el rango fusionado entra en conflicto con otras celdas fusionadas,
otras celdas fusionadas se eliminarán automáticamente.

##  merge {#int-int-int-int-bool-bool}
Fusiona un rango específico de celdas en una sola celda.



```python
def merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| first_row | int | Primera fila de este rango (base cero)|
| first_column | int | Primera columna de este rango (base cero)|
| total_rows | int | Número de filas (una basada)|
| total_columns | int | Número de columnas (una basada)|
| check_conflict | bool | Indica si verificar que las celdas fusionadas se cruzan con otras celdas fusionadas|
| merge_conflict | bool | Fusionar rangos fusionados en conflicto.|
###  Observaciones

Haga referencia a la celda fusionada a través de la dirección de la celda superior izquierda en el rango.
Si mergeConflict es verdadero y el rango fusionado entra en conflicto con otras celdas fusionadas,
otras celdas fusionadas se eliminarán automáticamente.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cells`](/cells/python-net/es/aspose.cells/cells)
