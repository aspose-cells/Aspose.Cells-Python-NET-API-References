---
title: método sort
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 50
url: /es/aspose.cells/datasorter/sort/
is_root: false
---
##  sort(self) {#}
Ordenar los datos en el rango.


###  Devoluciones

los índices originales (posición absoluta, por ejemplo, la columna A es 0, B es 1, ...) de las filas/columnas ordenadas.
Si no es necesario mover filas ni columnas mediante esta operación de clasificación, se devolverá nulo.


```python

def sort(self):
    ...
```




##  sort(self, cells, area) {#aspose.cells.Cells-aspose.cells.CellArea}
Ordenar los datos del área.


###  Devoluciones

los índices originales (posición absoluta, por ejemplo, la columna A es 0, B es 1, ...) de las filas/columnas ordenadas.
Si no es necesario mover filas ni columnas mediante esta operación de clasificación, se devolverá nulo.


```python

def sort(self, cells, area):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| cells | [`Cells`](/cells/python-net/es/aspose.cells/cells) | Las celdas contienen el área de datos.|
| area | [`CellArea`](/cells/python-net/es/aspose.cells/cellarea) | El área que se necesita ordenar|


##  sort(self, cells, start_row, start_column, end_row, end_column) {#aspose.cells.Cells-int-int-int-int}
Ordena los datos del área.


###  Devoluciones

los índices originales (posición absoluta, por ejemplo, la columna A es 0, B es 1, ...) de las filas/columnas ordenadas.
Si no es necesario mover filas ni columnas mediante esta operación de clasificación, se devolverá nulo.


```python

def sort(self, cells, start_row, start_column, end_row, end_column):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| cells | [`Cells`](/cells/python-net/es/aspose.cells/cells) | Las celdas contienen el área de datos.|
| start_row | int | La fila inicial del área.|
| start_column | int | La columna de inicio del área.|
| end_row | int | La última fila del área.|
| end_column | int | La columna final del área.|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`DataSorter`](/cells/python-net/es/aspose.cells/datasorter)
