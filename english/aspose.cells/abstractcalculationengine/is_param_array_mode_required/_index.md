---
title: is_param_array_mode_required property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 40
url: /aspose.cells/abstractcalculationengine/is_param_array_mode_required/
is_root: false
---

## is_param_array_mode_required property


Indicates whether this engine needs the parameter to be calculated in array mode. Default value is false.
If [`CalculationData.get_param_value_in_array_mode`](/cells/python-net/aspose.cells/calculationdata/get_param_value_in_array_mode) is required when calculating custom
functions and user has not updated the definition for them
(by [`Workbook.update_custom_function_definition`](/cells/python-net/aspose.cells/workbook/update_custom_function_definition)),
this property needs to be set as true.

### Remarks 


If this custom calculation engine needs the parameter to be calculated in array mode,
more stacks will be required to cache the tree for parameters
and Calculate() method may be called recursively to calculate the parameter's value.
For performance consideration, please keep this property as the default value(false)
if there is no special requirement.
### Definition:
```python
@property
def is_param_array_mode_required(self):
    ...
```

### See Also
* module [`aspose.cells`](../../)
* class [`AbstractCalculationEngine`](/cells/python-net/aspose.cells/abstractcalculationengine)
