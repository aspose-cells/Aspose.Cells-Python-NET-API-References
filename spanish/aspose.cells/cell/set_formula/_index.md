---
title: método set_formula
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 340
url: /es/aspose.cells/cell/set_formula/
is_root: false
---
##  set_formula {#str-any}
Establezca la fórmula y el valor (resultado calculado) de la fórmula.



```python
def set_formula(self, formula, value):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| formula | str | La formula.|
| value | any |El valor (resultado calculado) de la fórmula.|


##  set_formula {#str-aspose.cells.FormulaParseOptions-any}
Establezca la fórmula y el valor (resultado calculado) de la fórmula.



```python
def set_formula(self, formula, options, value):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| formula | str | La formula.|
| options | [`FormulaParseOptions`](/cells/python-net/es/aspose.cells/formulaparseoptions) | Opciones para analizar la fórmula.|
| value | any |El valor (resultado calculado) de la fórmula.|


##  set_formula {#str-bool-bool-any}
Establezca la fórmula y el valor de la fórmula.



```python
def set_formula(self, formula, is_r1c1, is_local, value):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| formula | str | La formula.|
| is_r1c1 | bool | Si la fórmula es la fórmula R1C1.|
| is_local | bool | Si la fórmula tiene formato local.|
| value | any | El valor de la fórmula.|
###  Observaciones

NOTA: Esta clase ahora está obsoleta. En cambio,
utilice Cell.SetFormula (cadena, FormulaParseOptions, objeto).
Esta propiedad será eliminada 12 meses después desde diciembre de 2019.
Aspose se disculpa por cualquier inconveniente que pueda haber experimentado.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cell`](/cells/python-net/es/aspose.cells/cell)
