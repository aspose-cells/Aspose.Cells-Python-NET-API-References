---
title: CalculationData class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 90
url: /aspose.cells/calculationdata/
is_root: false
---

## CalculationData class

Represents the required data when calculating one function, such as function name, parameters, ...etc.



The CalculationData type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [calculated_value](/cells/python-net/aspose.cells/calculationdata/calculated_value) | Gets or sets the calculated value for this function. |
| [workbook](/cells/python-net/aspose.cells/calculationdata/workbook) | Gets the Workbook object where the function is. |
| [worksheet](/cells/python-net/aspose.cells/calculationdata/worksheet) | Gets the Worksheet object where the function is. |
| [cell_row](/cells/python-net/aspose.cells/calculationdata/cell_row) | Gets the row index of the cell where the function is. |
| [cell_column](/cells/python-net/aspose.cells/calculationdata/cell_column) | Gets the column index of the cell where the function is. |
| [cell](/cells/python-net/aspose.cells/calculationdata/cell) | Gets the Cell object where the function is. |
| [function_name](/cells/python-net/aspose.cells/calculationdata/function_name) | Gets the function name to be calculated. |
| [param_count](/cells/python-net/aspose.cells/calculationdata/param_count) | Gets the count of parameters |


### Methods
| Method | Description |
| :- | :- |
| [`get_param_value(self, index)`](/cells/python-net/aspose.cells/calculationdata/get_param_value/#int) | Gets the represented value object of the parameter at a given index. |
| [`get_param_value_in_array_mode(self, index, max_row_count, max_column_count)`](/cells/python-net/aspose.cells/calculationdata/get_param_value_in_array_mode/#int-int-int) | Gets the value(s) of the parameter at a given index.<br/>If the parameter is some kind of expression that needs to be calculated, then it will be calculated in array mode. |
| [`get_param_text(self, index)`](/cells/python-net/aspose.cells/calculationdata/get_param_text/#int) | Gets the literal text of the parameter at the given index. |



### Remarks 


All objects provided by this class are for "read" purpose only.
User should not change any data in the Workbook during the formula calculation process,
Otherwise unexpected result or Exception may be caused.

### See Also
* module [`aspose.cells`](..)
