---
title: método calculate_array_formula
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 80
url: /es/aspose.cells/worksheet/calculate_array_formula/
is_root: false
---
##  calculate_array_formula(self, formula, opts) {#str-aspose.cells.CalculationOptions}
Calcula una fórmula como fórmula de matriz.



```python

def calculate_array_formula(self, formula, opts):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| formula | str | Fórmula a calcular.|
| opts | [`CalculationOptions`](/cells/python-net/es/aspose.cells/calculationoptions) | Opciones para calcular la fórmula|


##  calculate_array_formula(self, formula, opts, max_row_count, max_column_count) {#str-aspose.cells.CalculationOptions-int-int}
Calcula una fórmula como fórmula de matriz.


###  Devoluciones

Resultado de la fórmula calculada.


```python

def calculate_array_formula(self, formula, opts, max_row_count, max_column_count):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| formula | str | Fórmula a calcular.|
| opts | [`CalculationOptions`](/cells/python-net/es/aspose.cells/calculationoptions) | Opciones para calcular la fórmula|
| max_row_count | int | el número máximo de filas de datos resultantes.<br/> Si no es positivo o es mayor que el recuento de filas real, se utilizará el recuento de filas real.|
| max_column_count | int | el número máximo de columnas de datos resultantes.<br/> Si no es positivo o es mayor que el recuento de filas real, se utilizará el recuento de columnas real.|
###  Observaciones

La fórmula se tomará como una fórmula de matriz dinámica para calcular la dimensión y el resultado.
La dimensión máxima especificada por el usuario se utiliza para los casos en que el resultado calculado es un conjunto de datos grande
(por ejemplo, el resultado calculado puede corresponder a datos de una fila o columna completa)
pero el usuario no necesita una matriz tan grande según los requisitos comerciales o por consideraciones de rendimiento.

##  calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data) {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-int-int-aspose.cells.CalculationData}
Calcula una fórmula como fórmula de matriz.


###  Devoluciones

Resultado de la fórmula calculada.


```python

def calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| formula | str | Fórmula a calcular.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/es/aspose.cells/formulaparseoptions) |Opciones para analizar fórmulas|
| c_opts | [`CalculationOptions`](/cells/python-net/es/aspose.cells/calculationoptions) | Opciones para calcular la fórmula|
| base_cell_row | int | El índice de fila de la celda base.|
| base_cell_column | int | El índice de la columna de la celda base.|
| max_row_count | int | El recuento máximo de filas de datos resultantes.<br/> Si no es positivo o es mayor que el recuento de filas real, se utilizará el recuento de filas real.|
| max_column_count | int | El número máximo de columnas de datos resultantes.<br/> Si no es positivo o es mayor que el recuento de filas real, se utilizará el recuento de columnas real.|
| calculation_data | [`CalculationData`](/cells/python-net/es/aspose.cells/calculationdata) | Los datos de cálculo. Se utilizan para la situación.<br/>Ese usuario necesita calcular algunas fórmulas estáticas al implementar un motor de cálculo personalizado.<br/>Para este tipo de situación, el usuario debe especificarlo con los datos de cálculo proporcionados.<br/> para Aspose.Cells.AbstractCalculationEngine.Calcular.|
###  Observaciones

La fórmula se tomará como una fórmula de matriz dinámica para calcular la dimensión y el resultado.
La dimensión máxima especificada por el usuario se utiliza para los casos en que el resultado calculado es un conjunto de datos grande
(por ejemplo, el resultado calculado puede corresponder a datos de una fila o columna completa)
pero el usuario no necesita una matriz tan grande según los requisitos comerciales o por consideraciones de rendimiento.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Worksheet`](/cells/python-net/es/aspose.cells/worksheet)
