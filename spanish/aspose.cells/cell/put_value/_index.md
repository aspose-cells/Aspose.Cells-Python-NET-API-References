---
title: método put_value
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 290
url: /es/aspose.cells/cell/put_value/
is_root: false
---
##  put_value(self, bool_value) {#bool}
Coloca un valor booleano en la celda.



```python

def put_value(self, bool_value):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| bool_value | bool |  |


##  put_value(self, int_value) {#int}
Coloca un valor entero en la celda.



```python

def put_value(self, int_value):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| int_value | int | Valor de entrada|


##  put_value(self, double_value) {#float}
Coloca un valor doble en la celda.



```python

def put_value(self, double_value):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| double_value | float | Valor de entrada|


##  put_value(self, string_value) {#str}
Coloca un valor de cadena en la celda.



```python

def put_value(self, string_value):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| string_value | str | Valor de entrada|


##  put_value(self, date_time) {#DateTime}
Coloca un valor de fecha y hora en la celda.



```python

def put_value(self, date_time):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| date_time | DateTime | Valor de entrada|
###  Observaciones

Establecer un valor de fecha y hora para una celda no significa que la celda se formateará como fecha y hora automáticamente.
El valor de fecha y hora se mantuvo como valor numérico en el modelo de datos de MS Excel y Aspose.Cells.
Si el valor numérico se tomará como el valor numérico en sí o como fecha y hora
Depende del formato de número aplicado a esta celda. Si esta celda no tiene formato de fecha y hora,
Se mostrará como un valor numérico aunque lo que ingrese sea fecha y hora.
###  Ejemplo

Este ejemplo muestra cómo establecer el valor de fecha y hora en una celda y hacer que se muestre como fecha y hora.

```python
from aspose.cells import Workbook
from datetime import datetime

excel = Workbook()
cells = excel.worksheets[0].cells
# Put date time into a cell
cell = cells.get(0, 0)
cell.put_value(datetime(2023, 5, 15))
style = cell.get_style(False)
style.number = 14
cell.set_style(style)

```


##  put_value(self, object_value) {#any}
Coloca un valor de objeto en la celda.



```python

def put_value(self, object_value):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| object_value | any | valor de entrada|


##  put_value(self, string_value, is_converted) {#str-bool}
Coloca un valor de cadena en la celda y convierte el valor a otro tipo de datos si corresponde.



```python

def put_value(self, string_value, is_converted):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| string_value | str | Valor de entrada|
| is_converted | bool | Verdadero: se convierte a otro tipo de datos si corresponde.|


##  put_value(self, string_value, is_converted, set_style) {#str-bool-bool}
Coloca un valor en la celda, si corresponde, el valor se convertirá a otro tipo de datos y se restablecerá el formato de número de la celda.



```python

def put_value(self, string_value, is_converted, set_style):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| string_value | str | Valor de entrada|
| is_converted | bool | Verdadero: se convierte a otro tipo de datos si corresponde.|
| set_style | bool | Verdadero: establece el formato del número al estilo de la celda al convertir a otro tipo de datos|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cell`](/cells/python-net/es/aspose.cells/cell)
