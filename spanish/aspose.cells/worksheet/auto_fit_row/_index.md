---
title: auto_fit_row método
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 60
url: /es/aspose.cells/worksheet/auto_fit_row/
is_root: false
---
##  auto_fit_row(row_index) {#int}
Ajusta automáticamente la altura de la fila.



```python
def auto_fit_row(self, row_index):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| row_index | int | Índice de fila.|
###  Observaciones

AutoFitRow es una función imprecisa.

##  auto_fit_row(row_index, first_column, last_column) {#int-int-int}

Ajusta automáticamente la altura de la fila.



```python
def auto_fit_row(self, row_index, first_column, last_column):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| row_index | int | Índice de fila.|
| first_column | int | Índice de la primera columna.|
| last_column | int | Índice de la última columna.|
###  Observaciones

Este método ajusta automáticamente una fila según el contenido de un rango de celdas dentro de la fila.

##  auto_fit_row(row_index, first_column, last_column, options) {#int-int-int-AutoFitterOptions}

Ajusta automáticamente la altura de la fila.



```python
def auto_fit_row(self, row_index, first_column, last_column, options):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| row_index | int | Índice de fila.|
| first_column | int | Índice de la primera columna.|
| last_column | int | Índice de la última columna.|
| options | [AutoFitterOptions](/cells/python-net/es/aspose.cells/autofitteroptions) | Las opciones del instalador automático|
###  Observaciones

Este método ajusta automáticamente una fila según el contenido de un rango de celdas dentro de la fila.

##  auto_fit_row(start_row, end_row, start_column, end_column) {#int-int-int-int}

Ajusta automáticamente la altura de la fila en un rango de rectángulo.



```python
def auto_fit_row(self, start_row, end_row, start_column, end_column):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| start_row | int | Índice de fila de inicio.|
| end_row | int | Índice de fila final.|
| start_column | int | Índice de la columna de inicio.|
| end_column | int | Índice de columna final.|



###  Ver también
* módulo [aspose.cells](../../)
* clase [Worksheet](/cells/python-net/es/aspose.cells/worksheet)
