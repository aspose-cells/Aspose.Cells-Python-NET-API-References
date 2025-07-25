---
title: método add
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells.drawing/picturecollection/add/
is_root: false
---
##  add(self, upper_left_row, upper_left_column, stream) {#int-int-io.RawIOBase}
Añade una imagen a la colección.


###  Devoluciones

Índice de objeto [`Picture`](/cells/python-net/es/aspose.cells.drawing/picture).


```python

def add(self, upper_left_row, upper_left_column, stream):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| upper_left_row | int | Índice de la fila superior izquierda.|
| upper_left_column | int | Índice de la columna superior izquierda.|
| stream | io.RawIOBase | Objeto de flujo que contiene los datos de la imagen.|

###  Ejemplo

```python

# add a picture
with open("image.jpg", "rb") as fs:
    pictures.add(1, 1, fs)

```


##  add(self, upper_left_row, upper_left_column, file_name) {#int-int-str}
Añade una imagen a la colección.


###  Devoluciones

Índice de objeto [`Picture`](/cells/python-net/es/aspose.cells.drawing/picture).


```python

def add(self, upper_left_row, upper_left_column, file_name):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| upper_left_row | int | Índice de la fila superior izquierda.|
| upper_left_column | int | Índice de la columna superior izquierda.|
| file_name | str | Nombre del archivo de la imagen.|

###  Ejemplo

```python

# add a picture
pictures.add(1, 1, "image.jpg")

```


##  add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream) {#int-int-int-int-io.RawIOBase}
Añade una imagen a la colección.


###  Devoluciones

Índice de objeto [`Picture`](/cells/python-net/es/aspose.cells.drawing/picture).


```python

def add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| upper_left_row | int | Índice de la fila superior izquierda.|
| upper_left_column | int | Índice de la columna superior izquierda.|
| lower_right_row | int | Índice de la fila inferior derecha|
| lower_right_column | int | Índice de la columna inferior derecha|
| stream | io.RawIOBase | Objeto de flujo que contiene los datos de la imagen.|

###  Ejemplo

```python

# add a picture
with open("image.jpg", "rb") as fs:
    pictures.add(1, 1, 5, 5, fs)

```


##  add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name) {#int-int-int-int-str}
Añade una imagen a la colección.


###  Devoluciones

Índice de objeto [`Picture`](/cells/python-net/es/aspose.cells.drawing/picture).


```python

def add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| upper_left_row | int | Índice de la fila superior izquierda.|
| upper_left_column | int | Índice de la columna superior izquierda.|
| lower_right_row | int | Índice de la fila inferior derecha|
| lower_right_column | int | Índice de la columna inferior derecha|
| file_name | str | Nombre del archivo de la imagen.|

###  Ejemplo

```python

# add a picture
pictures.add(1, 1, 5, 5, "image.jpg")

```


##  add(self, upper_left_row, upper_left_column, stream, width_scale, height_scale) {#int-int-io.RawIOBase-int-int}
Añade una imagen a la colección.


###  Devoluciones

Índice de objeto [`Picture`](/cells/python-net/es/aspose.cells.drawing/picture).


```python

def add(self, upper_left_row, upper_left_column, stream, width_scale, height_scale):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| upper_left_row | int | Índice de la fila superior izquierda.|
| upper_left_column | int | Índice de la columna superior izquierda.|
| stream | io.RawIOBase | Objeto de flujo que contiene los datos de la imagen.|
| width_scale | int | Escala del ancho de la imagen, un porcentaje.|
| height_scale | int | Escala de altura de la imagen, un porcentaje.|

###  Ejemplo

```python

# add a picture
with open("image.jpg", "rb") as fs:
    pictures.add(1, 1, fs, 50, 50)

```


##  add(self, upper_left_row, upper_left_column, file_name, width_scale, height_scale) {#int-int-str-int-int}
Añade una imagen a la colección.


###  Devoluciones

Índice de objeto [`Picture`](/cells/python-net/es/aspose.cells.drawing/picture).


```python

def add(self, upper_left_row, upper_left_column, file_name, width_scale, height_scale):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| upper_left_row | int | Índice de la fila superior izquierda.|
| upper_left_column | int | Índice de la columna superior izquierda.|
| file_name | str | Nombre del archivo de la imagen.|
| width_scale | int | Escala del ancho de la imagen, un porcentaje.|
| height_scale | int | Escala de altura de la imagen, un porcentaje.|

###  Ejemplo

```python

# add a picture
pictures.add(1, 1, "image.jpg", 50, 50)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`Picture`](/cells/python-net/es/aspose.cells.drawing/picture)
* clase [`PictureCollection`](/cells/python-net/es/aspose.cells.drawing/picturecollection)
