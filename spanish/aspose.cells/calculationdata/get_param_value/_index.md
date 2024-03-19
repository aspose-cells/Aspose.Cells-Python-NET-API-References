---
title: método get_param_value
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 30
url: /es/aspose.cells/calculationdata/get_param_value/
is_root: false
---
##  get_param_value {#int}
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

Si es un valor simple, devuelve el valor simple en sí;


Si es una referencia, devuelve el objeto ReferedArea;


Si hace referencia a conjuntos de datos con múltiples valores, devuelve una matriz de objetos;



Si es algún tipo de expresión que necesita calcularse, entonces se calculará en modo valor.
y generalmente se devolverá un valor único según la base de celdas actual. Por ejemplo,
Si un parámetro de la fórmula de D2 es A:A+B:B, entonces se calculará y devolverá A2+B2.
Sin embargo, si este parámetro se ha especificado como modo de matriz
(por [`Workbook.update_custom_function_definition`](/cells/python-net/es/aspose.cells/workbook/update_custom_function_definition)
o [`FormulaParseOptions.custom_function_definition`](/cells/python-net/es/aspose.cells/formulaparseoptions#custom_function_definition)),
luego se devolverá una matriz (objeto [][]) cuyos elementos son A1+B1,A2+B2,....


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`CalculationData`](/cells/python-net/es/aspose.cells/calculationdata)
