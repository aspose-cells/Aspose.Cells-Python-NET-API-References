---
title: calculate_formula method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 90
url: /aspose.cells/worksheet/calculate_formula/
is_root: false
---

## calculate_formula(self, formula) {#str}

Calculates a formula.


### Returns 


Calculated formula result.


```python

def calculate_formula(self, formula):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| formula | str | Formula to be calculated. |


## calculate_formula(self, formula, opts) {#str-aspose.cells.CalculationOptions}

Calculates a formula expression directly.


### Returns 


Calculated result of given formula.
The returned object may be of possible types of [`Cell.value`](/cells/python-net/aspose.cells/cell#value), or ReferredArea.


```python

def calculate_formula(self, formula, opts):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| formula | str | Formula to be calculated. |
| opts | [`CalculationOptions`](/cells/python-net/aspose.cells/calculationoptions) | Options for calculating formula |
### Remarks

The formula will be calculated just like it has been set to cell A1.
And the formula will be taken as normal formula.
If you need the formula be calculated as an array formula and to get an array for the calculated result,
please use [`Worksheet.calculate_array_formula`](/cells/python-net/aspose.cells/worksheet/calculate_array_formula) instead.

## calculate_formula(self, options, recursive) {#aspose.cells.CalculationOptions-bool}

Calculates all formulas in this worksheet.



```python

def calculate_formula(self, options, recursive):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`CalculationOptions`](/cells/python-net/aspose.cells/calculationoptions) | Options for calculation |
| recursive | bool | True means if the worksheet' cells depend on the cells of other worksheets,<br/>the dependent cells in other worksheets will be calculated too.<br/>False means all the formulas in the worksheet have been calculated and the values are right. |


## calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data) {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-aspose.cells.CalculationData}

Calculates a formula expression directly.


### Returns 


Calculated result of given formula.
The returned object may be of possible types of [`Cell.value`](/cells/python-net/aspose.cells/cell#value), or ReferredArea.


```python

def calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| formula | str | Formula to be calculated. |
| p_opts | [`FormulaParseOptions`](/cells/python-net/aspose.cells/formulaparseoptions) | Options for parsing formula. |
| c_opts | [`CalculationOptions`](/cells/python-net/aspose.cells/calculationoptions) | Options for calculating formula. |
| base_cell_row | int | The row index of the base cell. |
| base_cell_column | int | The column index of the base cell. |
| calculation_data | [`CalculationData`](/cells/python-net/aspose.cells/calculationdata) | The calculation data. It is used for the situation<br/>that user needs to calculate some static formulas when implementing custom calculation engine.<br/>For such kind of situation, user needs to specify it with the calculation data provided<br/>for [`AbstractCalculationEngine.calculate`](/cells/python-net/aspose.cells/abstractcalculationengine/calculate). |
### Remarks

The formula will be calculated just like it has been set to the specified base cell.
And the formula will be taken as normal formula. If you need the formula be calculated as an array formula
and to get an array for the calculated result, please use
[`Worksheet.calculate_array_formula`](/cells/python-net/aspose.cells/worksheet/calculate_array_formula) instead.


### See Also
* module [`aspose.cells`](../../)
* class [`Worksheet`](/cells/python-net/aspose.cells/worksheet)
