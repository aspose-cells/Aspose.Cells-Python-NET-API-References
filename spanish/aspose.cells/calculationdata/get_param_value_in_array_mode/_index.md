---
title: método get_param_value_in_array_mode
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 40
url: /es/aspose.cells/calculationdata/get_param_value_in_array_mode/
is_root: false
---
##  get_param_value_in_array_mode(self, index, max_row_count, max_column_count) {#int-int-int}
Obtiene los valores del parámetro en el índice dado.
Si el parámetro es algún tipo de expresión que necesita calcularse,
Luego se calculará en modo matriz.


###  Devoluciones

Una matriz que contiene todos los elementos representados por el parámetro especificado.


```python

def get_param_value_in_array_mode(self, index, max_row_count, max_column_count):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| index | int | El índice del parámetro (basado en 0)|
| max_row_count | int | El límite de recuento de filas para la matriz devuelta.<br/> Si no es positivo o es mayor que el recuento de filas real, se utilizará el recuento de filas real.|
| max_column_count | int | El límite de recuento de columnas para la matriz devuelta.<br/> Si no es positivo o es mayor que el recuento de filas real, se utilizará el recuento de columnas real.|
###  Observaciones

Para una expresión que necesita ser calculada, tomando A:A+B:B como ejemplo:
En el modo de valor, se calculará un valor único según la base de celda actual.
Pero en el modo de matriz, se calcularán todos los valores de A1+B1,A2+B2,A3+B3,... y se usarán para construir la matriz devuelta.
Y para este tipo de situaciones, es mejor especificar el límite para el recuento de filas/columnas.
(como según [`Cells.max_data_row`](/cells/python-net/es/aspose.cells/cells#max_data_row) y [`Cells.max_data_column`](/cells/python-net/es/aspose.cells/cells#max_data_column)),
De lo contrario, la gran matriz devuelta puede aumentar el costo de memoria con una gran cantidad de datos inútiles.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`CalculationData`](/cells/python-net/es/aspose.cells/calculationdata)
