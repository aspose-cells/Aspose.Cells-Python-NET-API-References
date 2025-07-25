---
title: calc_stack_size propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 30
url: /es/aspose.cells/calculationoptions/calc_stack_size/
is_root: false
---
##  calc_stack_size propiedad

Tamaño de la pila para calcular celdas recursivamente. El valor predeterminado es 200.

###  Observaciones

Cuando hay una gran cantidad de celdas que necesitan calcularse recursivamente en el árbol de dependencia,
Es posible que se produzca una excepción StackOverflowException en el proceso de cálculo.
Si es así, el usuario debe especificar un valor más pequeño para esta propiedad.
Para tal situación, el usuario debe determinar el valor adecuado para esta propiedad de acuerdo con las fórmulas y datos reales.
Sin embargo, un valor demasiado pequeño puede provocar una degradación del rendimiento para el cálculo de la fórmula y un valor inferior a 2
Hará imposible calcular una fórmula que dependa de otra. Por lo tanto, si el valor especificado es menor que 2,
Se restablecerá a 2.
###  Definición:
```python
@property
def calc_stack_size(self):
    ...
@calc_stack_size.setter
def calc_stack_size(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`CalculationOptions`](/cells/python-net/es/aspose.cells/calculationoptions)
