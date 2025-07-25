---
title: método calculate_formula
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 90
url: /es/aspose.cells/worksheet/calculate_formula/
is_root: false
---
##  calculate_formula(self, formula) {#str}
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


##  calculate_formula(self, formula, opts) {#str-aspose.cells.CalculationOptions}
Calcula una expresión de fórmula directamente.


###  Devoluciones

Resultado calculado de la fórmula dada.
El objeto devuelto puede ser de los tipos posibles [`Cell.value`](/cells/python-net/es/aspose.cells/cell#value) o ReferredArea.


```python

def calculate_formula(self, formula, opts):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| formula | str | Fórmula a calcular.|
| opts | [`CalculationOptions`](/cells/python-net/es/aspose.cells/calculationoptions) | Opciones para calcular la fórmula|
###  Observaciones

La fórmula se calculará tal como se ha establecido en la celda A1.
Y la fórmula se tomará como fórmula normal.
Si necesita que la fórmula se calcule como una fórmula matricial y obtener una matriz para el resultado calculado,
Por favor utilice [`Worksheet.calculate_array_formula`](/cells/python-net/es/aspose.cells/worksheet/calculate_array_formula) en su lugar.

##  calculate_formula(self, options, recursive) {#aspose.cells.CalculationOptions-bool}
Calcula todas las fórmulas en esta hoja de trabajo.



```python

def calculate_formula(self, options, recursive):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| options | [`CalculationOptions`](/cells/python-net/es/aspose.cells/calculationoptions) | Opciones de cálculo|
| recursive | bool | Verdadero significa si las celdas de la hoja de cálculo dependen de las celdas de otras hojas de cálculo,<br/>También se calcularán las celdas dependientes en otras hojas de cálculo.<br/> Falso significa que se han calculado todas las fórmulas de la hoja de cálculo y los valores son correctos.|


##  calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data) {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-aspose.cells.CalculationData}
Calcula una expresión de fórmula directamente.


###  Devoluciones

Resultado calculado de la fórmula dada.
El objeto devuelto puede ser de los tipos posibles [`Cell.value`](/cells/python-net/es/aspose.cells/cell#value) o ReferredArea.


```python

def calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| formula | str | Fórmula a calcular.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/es/aspose.cells/formulaparseoptions) | Opciones para analizar fórmulas.|
| c_opts | [`CalculationOptions`](/cells/python-net/es/aspose.cells/calculationoptions) | Opciones para calcular la fórmula.|
| base_cell_row | int | El índice de fila de la celda base.|
| base_cell_column | int | El índice de la columna de la celda base.|
| calculation_data | [`CalculationData`](/cells/python-net/es/aspose.cells/calculationdata) | Los datos de cálculo. Se utilizan para la situación.<br/>Ese usuario necesita calcular algunas fórmulas estáticas al implementar un motor de cálculo personalizado.<br/>Para este tipo de situación, el usuario debe especificarlo con los datos de cálculo proporcionados.<br/> para Aspose.Cells.AbstractCalculationEngine.Calcular.|
###  Observaciones

La fórmula se calculará tal como se ha establecido en la celda base especificada.
La fórmula se tomará como una fórmula normal. Si necesita calcularla como una fórmula matricial,
y para obtener una matriz para el resultado calculado, utilice
[`Worksheet.calculate_array_formula`](/cells/python-net/es/aspose.cells/worksheet/calculate_array_formula) en su lugar.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Worksheet`](/cells/python-net/es/aspose.cells/worksheet)
