---
title: método get_list_value
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 70
url: /es/aspose.cells/validation/get_list_value/
is_root: false
---
##  get_list_value(self, row, column) {#int-int}
Obtenga el valor de la lista de validaciones para la celda especificada.


###  Devoluciones

El valor para producir la lista de esta validación para la celda especificada.
Si la lista hace referencia a un rango, entonces el valor devuelto será un objeto [`ReferredArea`](/cells/python-net/es/aspose.cells/referredarea);
De lo contrario, el valor devuelto puede ser nulo, objeto[] o objeto simple.


```python

def get_list_value(self, row, column):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| row | int | El índice de fila.|
| column | int | El índice de la columna.|
###  Observaciones

Sólo para la validación cuyo tipo es Lista y se ha aplicado a la celda dada,
De lo contrario se devolverá nulo.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`ReferredArea`](/cells/python-net/es/aspose.cells/referredarea)
* clase [`Validation`](/cells/python-net/es/aspose.cells/validation)
