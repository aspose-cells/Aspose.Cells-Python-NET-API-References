---
title: sort método
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 40
url: /es/aspose.cells/datasorter/sort/
is_root: false
---
##  sort() {#}
Ordenar los datos en el rango.


###  Devoluciones

los índices originales (posición absoluta, por ejemplo, la columna A es 0, B es 1, ...) de las filas/columnas ordenadas.
Si no es necesario mover filas/columnas mediante esta operación de clasificación, se devolverá un valor nulo.


```python
def sort(self):
    ...
```




##  sort(cells, area) {#Cells-CellArea}
Ordenar los datos del área.


###  Devoluciones

los índices originales (posición absoluta, por ejemplo, la columna A es 0, B es 1, ...) de las filas/columnas ordenadas.
Si no es necesario mover filas/columnas mediante esta operación de clasificación, se devolverá un valor nulo.


```python
def sort(self, cells, area):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| cells | [Cells](/cells/python-net/es/aspose.cells/cells) | Las celdas contienen el área de datos.|
| area | [CellArea](/cells/python-net/es/aspose.cells/cellarea) | El área necesaria para ordenar|


##  sort(cells, start_row, start_column, end_row, end_column) {#Cells-int-int-int-int}
Ordena los datos del área.


###  Devoluciones

los índices originales (posición absoluta, por ejemplo, la columna A es 0, B es 1, ...) de las filas/columnas ordenadas.
Si no es necesario mover filas/columnas mediante esta operación de clasificación, se devolverá un valor nulo.


```python
def sort(self, cells, start_row, start_column, end_row, end_column):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| cells | [Cells](/cells/python-net/es/aspose.cells/cells) | Las celdas contienen el área de datos.|
| start_row | int | La fila de inicio del área.|
| start_column | int | La columna de inicio del área.|
| end_row | int | La fila final del área.|
| end_column | int | La columna final del área.|



###  Ver también
* módulo [aspose.cells](../../)
* clase [DataSorter](/cells/python-net/es/aspose.cells/datasorter)
