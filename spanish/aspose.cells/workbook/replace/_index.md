---
title: método replace
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 350
url: /es/aspose.cells/workbook/replace/
is_root: false
---
##  replace(self, place_holder, new_value) {#str-str}
Reemplaza el valor de una celda con una nueva cadena.



```python

def replace(self, place_holder, new_value):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| place_holder | str | Cell marcador de posición|
| new_value | str | Valor de cadena a reemplazar|

###  Ejemplo

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
workbook.replace("AnOldValue", "NewValue")

```


##  replace(self, place_holder, new_value) {#str-int}
Reemplaza el valor de una celda con un nuevo entero.



```python

def replace(self, place_holder, new_value):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| place_holder | str | Cell marcador de posición|
| new_value | int | Valor entero a reemplazar|

###  Ejemplo

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValue = 100
workbook.replace("AnOldValue", newValue)

```


##  replace(self, place_holder, new_value) {#str-float}
Reemplaza el valor de una celda con un nuevo doble.



```python

def replace(self, place_holder, new_value):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| place_holder | str | Cell marcador de posición|
| new_value | float | Doble valor a reemplazar|

###  Ejemplo

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValue = 100.0
workbook.replace("AnOldValue", newValue)

```


##  replace(self, bool_value, new_value) {#bool-any}
Reemplaza los valores de las celdas con datos nuevos.



```python

def replace(self, bool_value, new_value):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| bool_value | bool | El valor booleano que se reemplazará.|
| new_value | any | Nuevo valor. Puede ser una cadena, un entero, un valor doble o un valor de fecha y hora.|


##  replace(self, int_value, new_value) {#int-any}
Reemplaza los valores de las celdas con datos nuevos.



```python

def replace(self, int_value, new_value):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| int_value | int | El valor entero que se va a reemplazar.|
| new_value | any | Nuevo valor. Puede ser una cadena, un entero, un valor doble o un valor de fecha y hora.|


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
Reemplaza el valor de una celda con una nueva matriz de cadenas.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| place_holder | str | Cell marcador de posición|
| new_values | list | Matriz de cadenas para reemplazar|
| is_vertical | bool | Verdadero - Vertical, Falso - Horizontal|

###  Ejemplo

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = ["Tom", "Alice", "Jerry"]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
Reemplaza los valores de las celdas con una matriz de números enteros.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| place_holder | str | Cell marcador de posición|
| new_values | list | Matriz de enteros a reemplazar|
| is_vertical | bool | Verdadero - Vertical, Falso - Horizontal|

###  Ejemplo

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = [1, 2, 3]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
Reemplaza los valores de las celdas con una matriz doble.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| place_holder | str | Cell marcador de posición|
| new_values | list | Matriz doble para reemplazar|
| is_vertical | bool | Verdadero - Vertical, Falso - Horizontal|

###  Ejemplo

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = [1.23, 2.56, 3.14159]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_value, options) {#str-str-aspose.cells.ReplaceOptions}
Reemplaza el valor de una celda con una nueva cadena.



```python

def replace(self, place_holder, new_value, options):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| place_holder | str | Cell marcador de posición|
| new_value | str | Valor de cadena a reemplazar|
| options | [`ReplaceOptions`](/cells/python-net/es/aspose.cells/replaceoptions) | Las opciones de reemplazo|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Workbook`](/cells/python-net/es/aspose.cells/workbook)
