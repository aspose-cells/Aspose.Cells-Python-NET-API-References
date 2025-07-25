---
title: método freeze_panes
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 140
url: /es/aspose.cells/worksheet/freeze_panes/
is_root: false
---
##  freeze_panes(self, cell_name, freezed_rows, freezed_columns) {#str-int-int}
Congela los paneles en la celda especificada en la hoja de cálculo.



```python

def freeze_panes(self, cell_name, freezed_rows, freezed_columns):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| cell_name | str | Cell nombre.|
| freezed_rows | int | Número de filas visibles en el panel superior, no más que el índice de fila.|
| freezed_columns | int | Número de columnas visibles en el panel izquierdo, no más que el índice de la columna.|
###  Observaciones

El índice de fila y el índice de columna no pueden ser todos cero. Número de filas y número de columnas.
Tampoco todos pueden ser cero.

##  freeze_panes(self, row, column, freezed_rows, freezed_columns) {#int-int-int-int}
Congela los paneles en la celda especificada en la hoja de cálculo.



```python

def freeze_panes(self, row, column, freezed_rows, freezed_columns):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| row | int | Índice de fila.|
| column | int | Índice de columna.|
| freezed_rows | int | Número de filas visibles en el panel superior, no más que el índice de fila.|
| freezed_columns | int | Número de columnas visibles en el panel izquierdo, no más que el índice de la columna.|
###  Observaciones

El índice de fila y el índice de columna no pueden ser todos cero. Número de filas y número de columnas.
Tampoco todos pueden ser cero.


Los dos primeros parámetros especifican la posición congelada y los dos últimos parámetros especifican el área congelada en el panel superior izquierdo.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Worksheet`](/cells/python-net/es/aspose.cells/worksheet)
