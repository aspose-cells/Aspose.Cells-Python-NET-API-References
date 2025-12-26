---
title: CalculationOptions class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 100
url: /aspose.cells/calculationoptions/
is_root: false
---

## CalculationOptions class

Represents options for calculation.



The CalculationOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/cells/python-net/aspose.cells/calculationoptions/__init__/#) | Constructs a new instance of CalculationOptions |


### Properties
| Property | Description |
| :- | :- |
| [ignore_error](/cells/python-net/aspose.cells/calculationoptions/ignore_error) | Indicates whether errors encountered while calculating formulas should be ignored.<br/>The error may be unsupported function, external links, etc.<br/>The default value is true. |
| [recursive](/cells/python-net/aspose.cells/calculationoptions/recursive) | Indicates whether calculate the dependent cells recursively when calculating one cell and it depends on other cells.<br/>The default value is true. |
| [user_specified_refresh_dynamic_array_formula](/cells/python-net/aspose.cells/calculationoptions/user_specified_refresh_dynamic_array_formula) | Indicates whether user has explicitly specified the behavior of<br/>refreshing dynamic array formulas before calculating specified formulas. |
| [refresh_dynamic_array_formula](/cells/python-net/aspose.cells/calculationoptions/refresh_dynamic_array_formula) | Indicates whether dynamic array formulas should be refreshed<br/>before calculating formulas. |
| [custom_engine](/cells/python-net/aspose.cells/calculationoptions/custom_engine) | The custom formula calculation engine to extend the default calculation engine of Aspose.Cells. |
| [calculation_monitor](/cells/python-net/aspose.cells/calculationoptions/calculation_monitor) | The monitor for user to track the progress of formula calculation. |
| [calc_stack_size](/cells/python-net/aspose.cells/calculationoptions/calc_stack_size) | The stack size for calculating cells recursively. Default value is 200. |
| [precision_strategy](/cells/python-net/aspose.cells/calculationoptions/precision_strategy) | Specifies the strategy for processing precision of calculation. |
| [linked_data_sources](/cells/python-net/aspose.cells/calculationoptions/linked_data_sources) | Specifies the data sources for external links used in formulas. |
| [character_encoding](/cells/python-net/aspose.cells/calculationoptions/character_encoding) | Specifies the encoding used for encoding/decoding characters when calculating formulas.<br/>For functions such as CHAR, CODE, the calculated result depends on the region settings and default charset of the environment.<br/>With this property user can specify the proper encoding used for those function to get the expected result. |



### See Also
* module [`aspose.cells`](..)
