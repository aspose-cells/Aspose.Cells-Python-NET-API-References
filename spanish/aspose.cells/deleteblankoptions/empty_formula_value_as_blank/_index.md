---
title: empty_formula_value_as_blank propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 40
url: /es/aspose.cells/deleteblankoptions/empty_formula_value_as_blank/
is_root: false
---
##  empty_formula_value_as_blank propiedad

Si una celda se tomará como en blanco cuando es una fórmula y el resultado calculado es nulo o una cadena vacía.
El valor predeterminado es falso.

###  Observaciones

Generalmente, el usuario debe asegurarse de que se hayan calculado las fórmulas antes de eliminar una operación con esta propiedad como verdadera.
De lo contrario, todas las fórmulas recién creadas por API normales, como [`Cell.formula`](/cells/python-net/es/aspose.cells/cell#formula), se tomarán en blanco y podrán eliminarse.
porque antes del cálculo sus resultados calculados son todos nulos.
###  Definición:
```python
@property
def empty_formula_value_as_blank(self):
    ...
@empty_formula_value_as_blank.setter
def empty_formula_value_as_blank(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`DeleteBlankOptions`](/cells/python-net/es/aspose.cells/deleteblankoptions)
