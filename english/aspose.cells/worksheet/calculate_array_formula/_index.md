---
title: calculate_array_formula method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 80
url: /aspose.cells/worksheet/calculate_array_formula/
is_root: false
---

## calculate_array_formula(self, formula, opts) {#System.String-aspose.cells.CalculationOptions}

Calculates a formula as array formula.



```python

def calculate_array_formula(self, formula, opts):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| formula | System.String | Formula to be calculated. |
| opts | aspose.cells.CalculationOptions | Options for calculating formula |


## calculate_array_formula(self, formula, opts, max_row_count, max_column_count) {#System.String-aspose.cells.CalculationOptions-int-int}

Calculates a formula as array formula.


### Returns 


Calculated formula result.


```python

def calculate_array_formula(self, formula, opts, max_row_count, max_column_count):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| formula | System.String | Formula to be calculated. |
| opts | aspose.cells.CalculationOptions | Options for calculating formula |
| max_row_count | int | the maximum row count of resultant data.<br/>If it is non-positive or greater than the actual row count, then actual row count will be used. |
| max_column_count | int | the maximum column count of resultant data.<br/>If it is non-positive or greater than the actual row count, then actual column count will be used. |
### Remarks

The formula will be taken as dynamic array formula to calculate the dimension and result.
User specified maximum dimension is used for cases that the calculated result is large data set
(for example, the calculated result may correspond to a whole row or column data)
but user does not need so large an array according to business requirement or for performance consideration.

## calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data) {#System.String-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-int-int-aspose.cells.CalculationData}

Calculates a formula as array formula.


### Returns 


Calculated formula result.


```python

def calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| formula | System.String | Formula to be calculated. |
| p_opts | aspose.cells.FormulaParseOptions | Options for parsing formula |
| c_opts | aspose.cells.CalculationOptions | Options for calculating formula |
| base_cell_row | int | The row index of the base cell. |
| base_cell_column | int | The column index of the base cell. |
| max_row_count | int | The maximum row count of resultant data.<br/>If it is non-positive or greater than the actual row count, then actual row count will be used. |
| max_column_count | int | The maximum column count of resultant data.<br/>If it is non-positive or greater than the actual row count, then actual column count will be used. |
| calculation_data | aspose.cells.CalculationData | The calculation data. It is used for the situation<br/>that user needs to calculate some static formulas when implementing custom calculation engine.<br/>For such kind of situation, user needs to specify it with the calculation data provided<br/>for Aspose.Cells.AbstractCalculationEngine.Calculate. |
### Remarks

The formula will be taken as dynamic array formula to calculate the dimension and result.
User specified maximum dimension is used for cases that the calculated result is large data set
(for example, the calculated result may correspond to a whole row or column data)
but user does not need so large an array according to business requirement or for performance consideration.


### See Also
* module [`aspose.cells`](../../)
* class [`Worksheet`](/cells/python-net/aspose.cells/worksheet)
