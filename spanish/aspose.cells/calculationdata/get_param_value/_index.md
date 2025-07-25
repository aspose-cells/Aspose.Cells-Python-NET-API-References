---
title: método get_param_value
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 30
url: /es/aspose.cells/calculationdata/get_param_value/
is_root: false
---
##  get_param_value(self, index) {#int}
Obtiene el objeto de valor representado del parámetro en el índice dado.


###  Devoluciones

El valor calculado del parámetro.


```python

def get_param_value(self, index):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| index | int | El índice del parámetro (basado en 0)|
###  Observaciones

Para un parámetro:

Si es un valor simple, entonces devuelve el valor simple en sí;


Si es una referencia, entonces devuelve el objeto ReferredArea;


Si hace referencia a conjuntos de datos con múltiples valores, entonces devuelve una matriz de objetos;



Si se trata de algún tipo de expresión que necesita calcularse, se calculará en modo de valor.
Generalmente, se devolverá un único valor según la base de celdas actual. Por ejemplo,
Si un parámetro de la fórmula de D2 es A:A+B:B, entonces se calculará y devolverá A2+B2.
Sin embargo, si este parámetro se ha especificado como modo de matriz
(por [`Workbook.update_custom_function_definition`](/cells/python-net/es/aspose.cells/workbook/update_custom_function_definition)
o [`FormulaParseOptions.custom_function_definition`](/cells/python-net/es/aspose.cells/formulaparseoptions#custom_function_definition)),
entonces se devolverá una matriz(object[][]) cuyos elementos son A1+B1,A2+B2,....


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`CalculationData`](/cells/python-net/es/aspose.cells/calculationdata)
