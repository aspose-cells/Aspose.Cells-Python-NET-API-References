---
title: método add
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells.slicers/slicercollection/add/
is_root: false
---
##  add(self, pivot, dest_cell_name, base_field_name) {#aspose.cells.pivot.PivotTable-str-str}
Agregar una nueva segmentación de datos usando una tabla dinámica como fuente de datos


###  Devoluciones

El nuevo índice Slicer add


```python

def add(self, pivot, dest_cell_name, base_field_name):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | objeto de tabla dinámica|
| dest_cell_name | str | La celda en la esquina superior izquierda del rango de Slicer.|
| base_field_name | str | El nombre de PivotField en PivotTable.BaseFields|

###  Ejemplo

```python

slicers.add(pivot, "E3", "fruit")

```


##  add(self, pivot, dest_cell_name, base_field_index) {#aspose.cells.pivot.PivotTable-str-int}
Agregar una nueva segmentación de datos usando una tabla dinámica como fuente de datos


###  Devoluciones

El nuevo índice Slicer add


```python

def add(self, pivot, dest_cell_name, base_field_index):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | objeto de tabla dinámica|
| dest_cell_name | str | La celda en la esquina superior izquierda del rango de Slicer.|
| base_field_index | int | El índice de PivotField en PivotTable.BaseFields|

###  Ejemplo

```python

slicers.add(pivot, "E20", 0)

```


##  add(self, pivot, dest_cell_name, base_field) {#aspose.cells.pivot.PivotTable-str-aspose.cells.pivot.PivotField}
Agregar una nueva segmentación de datos usando una tabla dinámica como fuente de datos


###  Devoluciones

El nuevo índice Slicer add


```python

def add(self, pivot, dest_cell_name, base_field):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | objeto de tabla dinámica|
| dest_cell_name | str | La celda en la esquina superior izquierda del rango de Slicer.|
| base_field | aspose.cells.pivot.PivotField | El campo dinámico en PivotTable.BaseFields|

###  Ejemplo

```python

slicers.add(pivot, "I3", pivot.base_fields[0])

```


##  add(self, table, index, dest_cell_name) {#aspose.cells.tables.ListObject-int-str}
Agregar un nuevo Slicer usando ListObjet como fuente de datos


###  Devoluciones

El nuevo índice Slicer add


```python

def add(self, table, index, dest_cell_name):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| table | aspose.cells.tables.ListObject | objeto ListObject|
| index | int | El índice de ListColumn en ListObject.ListColumns|
| dest_cell_name | str | La celda en la esquina superior izquierda del rango de Slicer.|

###  Ejemplo

```python

slicers.add(table, 1, "E38")

```


##  add(self, table, list_column, dest_cell_name) {#aspose.cells.tables.ListObject-aspose.cells.tables.ListColumn-str}
Agregar un nuevo Slicer usando ListObjet como fuente de datos


###  Devoluciones

El nuevo índice Slicer add


```python

def add(self, table, list_column, dest_cell_name):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| table | aspose.cells.tables.ListObject | objeto ListObject|
| list_column | aspose.cells.tables.ListColumn | La ListColumn en ListObject.ListColumns|
| dest_cell_name | str | La celda en la esquina superior izquierda del rango de Slicer.|

###  Ejemplo

```python

slicers.add(table, table.list_columns[1], "I38")

```


##  add(self, pivot, row, column, base_field_name) {#aspose.cells.pivot.PivotTable-int-int-str}
Agregar una nueva segmentación de datos usando una tabla dinámica como fuente de datos


###  Devoluciones

El nuevo índice Slicer add


```python

def add(self, pivot, row, column, base_field_name):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | objeto de tabla dinámica|
| row | int | Índice de fila de la celda en la esquina superior izquierda del rango de la segmentación de datos.|
| column | int | Índice de columna de la celda en la esquina superior izquierda del rango de la segmentación de datos.|
| base_field_name | str | El nombre de PivotField en PivotTable.BaseFields|

###  Ejemplo

```python

slicers.add(pivot, 20, 12, "fruit")

```


##  add(self, pivot, row, column, base_field_index) {#aspose.cells.pivot.PivotTable-int-int-int}
Agregar una nueva segmentación de datos usando una tabla dinámica como fuente de datos


###  Devoluciones

El nuevo índice Slicer add


```python

def add(self, pivot, row, column, base_field_index):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | objeto de tabla dinámica|
| row | int | Índice de fila de la celda en la esquina superior izquierda del rango de la segmentación de datos.|
| column | int | Índice de columna de la celda en la esquina superior izquierda del rango de la segmentación de datos.|
| base_field_index | int | El índice de PivotField en PivotTable.BaseFields|

###  Ejemplo

```python

slicers.add(pivot, 20, 8, 0)

```


##  add(self, pivot, row, column, base_field) {#aspose.cells.pivot.PivotTable-int-int-aspose.cells.pivot.PivotField}
Agregar una nueva segmentación de datos usando una tabla dinámica como fuente de datos


###  Devoluciones

El nuevo índice Slicer add


```python

def add(self, pivot, row, column, base_field):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| pivot | aspose.cells.pivot.PivotTable | objeto de tabla dinámica|
| row | int | Índice de fila de la celda en la esquina superior izquierda del rango de la segmentación de datos.|
| column | int | Índice de columna de la celda en la esquina superior izquierda del rango de la segmentación de datos.|
| base_field | aspose.cells.pivot.PivotField | El campo dinámico en PivotTable.BaseFields|

###  Ejemplo

```python

slicers.add(pivot, 3, 12, pivot.base_fields[0])

```


##  add(self, table, list_column, row, column) {#aspose.cells.tables.ListObject-aspose.cells.tables.ListColumn-int-int}
Agregar un nuevo Slicer usando ListObjet como fuente de datos


###  Devoluciones

El nuevo índice Slicer add


```python

def add(self, table, list_column, row, column):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| table | aspose.cells.tables.ListObject | objeto ListObject|
| list_column | aspose.cells.tables.ListColumn | La ListColumn en ListObject.ListColumns|
| row | int | Índice de fila de la celda en la esquina superior izquierda del rango de la segmentación de datos.|
| column | int | Índice de columna de la celda en la esquina superior izquierda del rango de la segmentación de datos.|

###  Ejemplo

```python

slicers.add(table, table.list_columns[1], 38, 12)

```



###  Ver también
* módulo [`aspose.cells.slicers`](../../)
* clase [`SlicerCollection`](/cells/python-net/es/aspose.cells.slicers/slicercollection)
