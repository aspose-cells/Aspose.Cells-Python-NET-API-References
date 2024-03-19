---
title: método freeze_panes
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 140
url: /es/aspose.cells/worksheet/freeze_panes/
is_root: false
---
##  freeze_panes {#str-int-int}
Congela paneles en la celda especificada de la hoja de trabajo.



```python
def freeze_panes(self, cell_name, freezed_rows, freezed_columns):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| cell_name | str | Cell nombre.|
| freezed_rows | int | Número de filas visibles en el panel superior, no más que el índice de filas.|
| freezed_columns | int | Número de columnas visibles en el panel izquierdo, no más que el índice de columna.|
###  Observaciones

El índice de fila y el índice de columna no pueden ser todos cero. Número de filas y número de columnas.
Tampoco todos pueden ser cero.

##  freeze_panes {#int-int-int-int}
Congela paneles en la celda especificada de la hoja de trabajo.



```python
def freeze_panes(self, row, column, freezed_rows, freezed_columns):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| row | int | Índice de fila.|
| column | int | Índice de columnas.|
| freezed_rows | int | Número de filas visibles en el panel superior, no más que el índice de filas.|
| freezed_columns | int | Número de columnas visibles en el panel izquierdo, no más que el índice de columna.|
###  Observaciones

El índice de fila y el índice de columna no pueden ser todos cero. Número de filas y número de columnas.
Tampoco todos pueden ser cero.


Los dos primeros parámetros especifican la posición congelada y los dos últimos parámetros especifican el área congelada en el panel superior izquierdo.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Worksheet`](/cells/python-net/es/aspose.cells/worksheet)
