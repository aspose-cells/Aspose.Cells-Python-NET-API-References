---
title: update_custom_function_definition method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 430
url: /aspose.cells/workbook/update_custom_function_definition/
is_root: false
---

## update_custom_function_definition(self, definition) {#aspose.cells.CustomFunctionDefinition}

Updates definition of custom functions.



```python

def update_custom_function_definition(self, definition):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| definition | aspose.cells.CustomFunctionDefinition | Special definition of custom functions for user's special requirement. |
### Remarks

This method can be used for some special scenarios. For example, if user needs some parameters
of some custom functions be calculated in array mode, then user may provide their own definition with implemented
[`CustomFunctionDefinition.get_array_mode_parameters`](/cells/python-net/aspose.cells/customfunctiondefinition/get_array_mode_parameters) for those functions.
After the data of formulas being updated, those specified parameters will be calculated in array mode automatically
when calculating corresponding custom functions.


### See Also
* module [`aspose.cells`](../../)
* class [`Workbook`](/cells/python-net/aspose.cells/workbook)
