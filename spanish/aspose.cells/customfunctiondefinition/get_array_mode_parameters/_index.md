---
title: método get_array_mode_parameters
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 20
url: /es/aspose.cells/customfunctiondefinition/get_array_mode_parameters/
is_root: false
---
##  get_array_mode_parameters(self, function_name) {#str}
Obtiene los índices de los parámetros de una función personalizada dada que deben calcularse en modo de matriz.


###  Devoluciones

Índices de los parámetros que deben calcularse en modo matriz para una función personalizada determinada.
El valor predeterminado es nulo, no hay ningún parámetro que deba calcularse en modo de matriz para la función personalizada.


```python

def get_array_mode_parameters(self, function_name):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| function_name | str | Nombre de la función personalizada.|
###  Observaciones

Para una expresión que necesita ser calculada, tomando A:A+B:B como ejemplo:
Generalmente, en el modo de valor, se calculará un valor único según la base de celda actual.
Pero en el modo de matriz, se calcularán todos los valores de A1+B1,A2+B2,A3+B3,... y se utilizarán para el cálculo.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`CustomFunctionDefinition`](/cells/python-net/es/aspose.cells/customfunctiondefinition)
