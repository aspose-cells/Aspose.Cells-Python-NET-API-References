---
title: calculate_array_formula method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 80
url: /aspose.cells/worksheet/calculate_array_formula/
is_root: false
---

## calculate_array_formula {#str-aspose.cells.CalculationOptions}

Calculates a formula as array formula.



```python
def calculate_array_formula(self, formula, opts):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| formula | str | Formula to be calculated. |
| opts | [`CalculationOptions`](/cells/python-net/aspose.cells/calculationoptions) | Options for calculating formula |


## calculate_array_formula {#str-aspose.cells.CalculationOptions-int-int}

Calculates a formula as array formula.


### Returns 


Calculated formula result.


```python
def calculate_array_formula(self, formula, opts, max_row_count, max_column_count):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| formula | str | Formula to be calculated. |
| opts | [`CalculationOptions`](/cells/python-net/aspose.cells/calculationoptions) | Options for calculating formula |
| max_row_count | int | the maximum row count of resultant data.<br/>-1 means it will be determined by the formula itself. |
| max_column_count | int | the maximum column count of resultant data.<br/>-1 means it is determined by the formula itself. |
### Remarks

The formula will be taken as dynamic array formula to calculate the dimension and result.
User specified maximum dimension is used for cases that the calculated result is large data set
(for example, the calculated result may correspond to a whole row or column data)
but user does not need so large an array according to business requirement or for performance consideration.


### See Also
* module [`aspose.cells`](../../)
* class [`Worksheet`](/cells/python-net/aspose.cells/worksheet)
