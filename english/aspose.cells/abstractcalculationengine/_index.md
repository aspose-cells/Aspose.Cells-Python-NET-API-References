---
title: AbstractCalculationEngine class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells/abstractcalculationengine/
is_root: false
---

## AbstractCalculationEngine class

Represents user's custom calculation engine to extend the default calculation engine of Aspose.Cells.



The AbstractCalculationEngine type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [is_param_literal_required](/cells/python-net/aspose.cells/abstractcalculationengine/is_param_literal_required) | Indicates whether this engine needs the literal text of parameter while doing calculation. Default value is false. |
| [is_param_array_mode_required](/cells/python-net/aspose.cells/abstractcalculationengine/is_param_array_mode_required) | Indicates whether this engine needs the parameter to be calculated in array mode. Default value is false.<br/>If [`CalculationData.get_param_value_in_array_mode`](/cells/python-net/aspose.cells/calculationdata/get_param_value_in_array_mode) is required when calculating custom<br/>functions and user has not updated the definition for them<br/>(by [`Workbook.update_custom_function_definition`](/cells/python-net/aspose.cells/workbook/update_custom_function_definition)),<br/>this property needs to be set as true. |
| [process_built_in_functions](/cells/python-net/aspose.cells/abstractcalculationengine/process_built_in_functions) | Whether built-in functions that have been supported by the built-in engine<br/>should be checked and processed by this implementation.<br/>Default is false. |


### Methods
| Method | Description |
| :- | :- |
| [calculate](/cells/python-net/aspose.cells/abstractcalculationengine/calculate/#aspose.cells.CalculationData) | Calculates one function with given data. |
| [force_recalculate](/cells/python-net/aspose.cells/abstractcalculationengine/force_recalculate/#str) | Whether force given function to be recalculated always when calculating shared formulas. |



### Remarks 


User should not modify any part of the Workbook directly in this implementation(except
the calculated result of the custom function, which can be set by CalculationData.CalculatedValue property).
Otherwise unexpected result or Exception may be caused.
If user needs to change other data than calculated result in the implementation for some custom functions,
for example, change cell's formula, style, ...etc., user should gather those data in this implementation
and change them out of the scope of formula calculation.

### See Also
* module [`aspose.cells`](..)
