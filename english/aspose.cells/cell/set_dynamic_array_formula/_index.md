---
title: set_dynamic_array_formula method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 340
url: /aspose.cells/cell/set_dynamic_array_formula/
is_root: false
---

## set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-bool}

Sets dynamic array formula and make the formula spill into neighboring cells if possible.


### Returns 


the range that the formula should spill into.


```python
def set_dynamic_array_formula(self, array_formula, options, calculate_value):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| array_formula | str | the formula expression |
| options | [`FormulaParseOptions`](/cells/python-net/aspose.cells/formulaparseoptions) | options to parse formula.<br/>"Parse" option will be ignored and the formula will always be parsed immediately |
| calculate_value | bool | whether calculate this dynamic array formula for those cells in the spilled range. |
### Remarks

the returned range may be not same with the actual one that this dynamic array formula spills into.
If there are non-empty cells in the range, the formula will be set for current cell only and marked as "#SPILL!".
But for such kind of situation we still return the whole range that this formula should spill into.

## set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-list-bool-bool}

Sets dynamic array formula and make the formula spill into neighboring cells if possible.


### Returns 


the range that the formula should spill into.


```python
def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| array_formula | str | the formula expression |
| options | [`FormulaParseOptions`](/cells/python-net/aspose.cells/formulaparseoptions) | options to parse formula.<br/>"Parse" option will be ignored and the formula will always be parsed immediately |
| values | list | values(calculated results) for those cells with given dynamic array formula |
| calculate_range | bool | Whether calculate the spilled range for this dynamic array formula.<br/>If the "values" parameter is not null and this flag is false,<br/>then the spilled range's height will be values.Length and width will be values[0].Length. |
| calculate_value | bool | whether calculate this dynamic array formula for those cells in the spilled range when "values" is null<br/>or corresponding item in "values" for one cell is null. |
### Remarks

the returned range may be not same with the actual one that this dynamic array formula spills into.
If there are non-empty cells in the range, the formula will be set for current cell only and marked as "#SPILL!".
But for such kind of situation we still return the whole range that this formula should spill into.

## set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions}

Sets dynamic array formula and make the formula spill into neighboring cells if possible.


### Returns 


the range that the formula should spill into.


```python
def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| array_formula | str | the formula expression |
| options | [`FormulaParseOptions`](/cells/python-net/aspose.cells/formulaparseoptions) | options to parse formula.<br/>"Parse" option will be ignored and the formula will always be parsed immediately |
| values | list | values(calculated results) for those cells with given dynamic array formula |
| calculate_range | bool | Whether calculate the spilled range for this dynamic array formula.<br/>If the "values" parameter is not null and this flag is false,<br/>then the spilled range's height will be values.Length and width will be values[0].Length. |
| calculate_value | bool | whether calculate this dynamic array formula for those cells in the spilled range when "values" is null<br/>or corresponding item in "values" for one cell is null. |
| copts | [`CalculationOptions`](/cells/python-net/aspose.cells/calculationoptions) | The options for calculating formula.<br/>Commonly, for performance consideration, the [`CalculationOptions.recursive`](/cells/python-net/aspose.cells/calculationoptions#recursive) property should be false. |
### Remarks

the returned range may be not same with the actual one that this dynamic array formula spills into.
If there are non-empty cells in the range, the formula will be set for current cell only and marked as "#SPILL!".
But for such kind of situation we still return the whole range that this formula should spill into.


### See Also
* module [`aspose.cells`](../../)
* class [`Cell`](/cells/python-net/aspose.cells/cell)
