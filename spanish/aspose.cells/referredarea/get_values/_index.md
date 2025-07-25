---
title: método get_values
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 30
url: /es/aspose.cells/referredarea/get_values/
is_root: false
---
##  get_values(self) {#}
Obtiene valores de celda en esta área.


###  Devoluciones

Si esta área no es válida, "#REF!" Será devuelto;
Si esta área es una sola celda, devuelva el objeto de valor de celda;
De lo contrario, devuelve una matriz 2D para todos los valores en esta área.


```python

def get_values(self):
    ...
```




##  get_values(self, calculate_formulas) {#bool}
Obtiene valores de celda en esta área.


###  Devoluciones

Si esta área no es válida, "#REF!" Será devuelto;
Si esta área es una sola celda, devuelva el objeto de valor de celda;
De lo contrario, devuelve una matriz 2D para todos los valores en esta área.


```python

def get_values(self, calculate_formulas):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| calculate_formulas | bool | En este rango, si hay algunas fórmulas que no se han calculado,<br/> Esta bandera indica si esas fórmulas deben calcularse recursivamente|



###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`ReferredArea`](/cells/python-net/es/aspose.cells/referredarea)
