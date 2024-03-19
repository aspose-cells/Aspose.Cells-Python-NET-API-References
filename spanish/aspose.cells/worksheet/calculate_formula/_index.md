---
title: método calculate_formula
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 90
url: /es/aspose.cells/worksheet/calculate_formula/
is_root: false
---
##  calculate_formula {#str}
Calcula una fórmula.


###  Devoluciones

Resultado de la fórmula calculada.


```python
def calculate_formula(self, formula):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| formula | str | Fórmula a calcular.|


##  calculate_formula {#str-aspose.cells.CalculationOptions}
Calcula una expresión de fórmula directamente.


###  Devoluciones

Resultado calculado de la fórmula dada.
El objeto devuelto puede ser de posibles tipos de [`Cell.value`](/cells/python-net/es/aspose.cells/cell#value) o ReferedArea.


```python
def calculate_formula(self, formula, opts):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| formula | str | Fórmula a calcular.|
| opts | [`CalculationOptions`](/cells/python-net/es/aspose.cells/calculationoptions) | Opciones para calcular la fórmula.|
###  Observaciones

La fórmula se calculará tal como se configuró en la celda A1.
Y la fórmula se tomará como fórmula normal.
Si necesita que la fórmula se calcule como una fórmula matricial y obtenga una matriz para el resultado calculado,
utilice [`Worksheet.calculate_array_formula`](/cells/python-net/es/aspose.cells/worksheet/calculate_array_formula) en su lugar.

##  calculate_formula {#aspose.cells.CalculationOptions-bool}
Calcula todas las fórmulas en esta hoja de trabajo.



```python
def calculate_formula(self, options, recursive):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| options | [`CalculationOptions`](/cells/python-net/es/aspose.cells/calculationoptions) | Opciones de cálculo|
| recursive | bool | Verdadero significa que si las celdas de la hoja de trabajo dependen de las celdas de otras hojas de trabajo,<br/>Las celdas dependientes en otras hojas de trabajo también se calcularán.<br/> Falso significa que todas las fórmulas de la hoja de cálculo se han calculado y los valores son correctos.|


##  calculate_formula {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-aspose.cells.CalculationData}
Calcula una expresión de fórmula directamente.


###  Devoluciones

Resultado calculado de la fórmula dada.
El objeto devuelto puede ser de posibles tipos de [`Cell.value`](/cells/python-net/es/aspose.cells/cell#value) o ReferedArea.


```python
def calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| formula | str | Fórmula a calcular.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/es/aspose.cells/formulaparseoptions) | Opciones para analizar la fórmula.|
| c_opts | [`CalculationOptions`](/cells/python-net/es/aspose.cells/calculationoptions) | Opciones para calcular la fórmula.|
| base_cell_row | int | El índice de fila de la celda base.|
| base_cell_column | int | El índice de columna de la celda base.|
| calculation_data | [`CalculationData`](/cells/python-net/es/aspose.cells/calculationdata) | Los datos del cálculo. Se utiliza para la situación.<br/>ese usuario necesita calcular algunas fórmulas estáticas al implementar un motor de cálculo personalizado.<br/>Para tal tipo de situación, el usuario debe especificarlo con los datos de cálculo proporcionados.<br/> para [`AbstractCalculationEngine.calculate`](/cells/python-net/es/aspose.cells/abstractcalculationengine/calculate).|
###  Observaciones

La fórmula se calculará tal como se configuró en la celda base especificada.
la fórmula se tomará como fórmula normal. Si necesita que la fórmula se calcule como una fórmula matricial
y para obtener una matriz para el resultado calculado, utilice
[`Worksheet.calculate_array_formula`](/cells/python-net/es/aspose.cells/worksheet/calculate_array_formula) en su lugar.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Worksheet`](/cells/python-net/es/aspose.cells/worksheet)
