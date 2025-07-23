---
title: método add
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells.timelines/timelinecollection/add/
is_root: false
---
##  add(self, pivot, dest_cell_name, base_field_name) {#aspose.cells.pivot.PivotTable-str-str}
Agregar una nueva línea de tiempo usando una tabla dinámica como fuente de datos


###  Devoluciones

El nuevo índice de la línea de tiempo add


```python

def add(self, pivot, dest_cell_name, base_field_name):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | objeto de tabla dinámica|
| dest_cell_name | str | El nombre de la celda en la esquina superior izquierda del rango de la línea de tiempo.|
| base_field_name | str | El nombre de PivotField en PivotTable.BaseFields|

###  Ejemplo

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, "i15", "date")

```


##  add(self, pivot, dest_cell_name, base_field_index) {#aspose.cells.pivot.PivotTable-str-int}
Agregar una nueva línea de tiempo usando una tabla dinámica como fuente de datos


###  Devoluciones

El nuevo índice de la línea de tiempo add


```python

def add(self, pivot, dest_cell_name, base_field_index):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | objeto de tabla dinámica|
| dest_cell_name | str | El nombre de la celda en la esquina superior izquierda del rango de la línea de tiempo.|
| base_field_index | int | El índice de PivotField en PivotTable.BaseFields|

###  Ejemplo

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, "i5", 1)

```


##  add(self, pivot, dest_cell_name, base_field) {#aspose.cells.pivot.PivotTable-str-aspose.cells.pivot.PivotField}
Agregar una nueva línea de tiempo usando una tabla dinámica como fuente de datos


###  Devoluciones

El nuevo índice de la línea de tiempo add


```python

def add(self, pivot, dest_cell_name, base_field):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | objeto de tabla dinámica|
| dest_cell_name | str | El nombre de la celda en la esquina superior izquierda del rango de la línea de tiempo.|
| base_field | aspose.cells.pivot.PivotField | El campo dinámico en PivotTable.BaseFields|

###  Ejemplo

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, "i10", pivot.base_fields[1])

```


##  add(self, pivot, row, column, base_field_name) {#aspose.cells.pivot.PivotTable-int-int-str}
Agregar una nueva línea de tiempo usando una tabla dinámica como fuente de datos


###  Devoluciones

El nuevo índice de la línea de tiempo add


```python

def add(self, pivot, row, column, base_field_name):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | objeto de tabla dinámica|
| row | int |Índice de fila de la celda en la esquina superior izquierda del rango de la línea de tiempo.|
| column | int | Índice de columna de la celda en la esquina superior izquierda del rango de la línea de tiempo.|
| base_field_name | str | El nombre de PivotField en PivotTable.BaseFields|

###  Ejemplo

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, 10, 5, "date")

```


##  add(self, pivot, row, column, base_field_index) {#aspose.cells.pivot.PivotTable-int-int-int}
Agregar una nueva línea de tiempo usando una tabla dinámica como fuente de datos


###  Devoluciones

El nuevo índice de la línea de tiempo add


```python

def add(self, pivot, row, column, base_field_index):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | objeto de tabla dinámica|
| row | int |Índice de fila de la celda en la esquina superior izquierda del rango de la línea de tiempo.|
| column | int | Índice de columna de la celda en la esquina superior izquierda del rango de la línea de tiempo.|
| base_field_index | int | El índice de PivotField en PivotTable.BaseFields|

###  Ejemplo

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, 15, 5, 1)

```


##  add(self, pivot, row, column, base_field) {#aspose.cells.pivot.PivotTable-int-int-aspose.cells.pivot.PivotField}
Agregar una nueva línea de tiempo usando una tabla dinámica como fuente de datos


###  Devoluciones

El nuevo índice de la línea de tiempo add


```python

def add(self, pivot, row, column, base_field):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | objeto de tabla dinámica|
| row | int |Índice de fila de la celda en la esquina superior izquierda del rango de la línea de tiempo.|
| column | int | Índice de columna de la celda en la esquina superior izquierda del rango de la línea de tiempo.|
| base_field | aspose.cells.pivot.PivotField | El campo dinámico en PivotTable.BaseFields|

###  Ejemplo

```python

# Add a new Timeline using PivotTable as data source
sheet.timelines.add(pivot, 20, 5, pivot.base_fields[1])

```



###  Ver también
* módulo [`aspose.cells.timelines`](../../)
* clase [`TimelineCollection`](/cells/python-net/es/aspose.cells.timelines/timelinecollection)
