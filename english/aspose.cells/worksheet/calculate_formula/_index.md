---
title: calculate_formula method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 90
url: /aspose.cells/worksheet/calculate_formula/
is_root: false
---

## calculate_formula {#str}

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


## calculate_formula {#str-aspose.cells.CalculationOptions}

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

## calculate_formula {#aspose.cells.CalculationOptions-bool}

Calculates all formulas in this worksheet.



```python
def calculate_formula(self, options, recursive):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`CalculationOptions`](/cells/python-net/aspose.cells/calculationoptions) | Options for calculation |
| recursive | bool | True means if the worksheet' cells depend on the cells of other worksheets,<br/>the dependent cells in other worksheets will be calculated too.<br/>False means all the formulas in the worksheet have been calculated and the values are right. |


## calculate_formula {#bool-bool-aspose.cells.ICustomFunction}

Calculates all formulas in this worksheet.



```python
def calculate_formula(self, recursive, ignore_error, custom_function):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| recursive | bool | True means if the worksheet' cells depend on the cells of other worksheets,<br/>the dependent cells in other worksheets will be calculated too.<br/>False means all the formulas in the worksheet have been calculated and the values are right. |
| ignore_error | bool | Indicates if hide the error in calculating formulas.<br/>The error may be unsupported function, external links, etc. |
| custom_function | [`ICustomFunction`](/cells/python-net/aspose.cells/icustomfunction) | The custom formula calculation functions to extend the calculation engine. |
### Remarks

NOTE: This member is now obsolete. Instead, 
please use CalculateFormula(CalculationOptions, bool) method.
This method will be removed 12 months later since August 2020. 
Aspose apologizes for any inconvenience you may have experienced.


### See Also
* module [`aspose.cells`](../../)
* class [`Worksheet`](/cells/python-net/aspose.cells/worksheet)
