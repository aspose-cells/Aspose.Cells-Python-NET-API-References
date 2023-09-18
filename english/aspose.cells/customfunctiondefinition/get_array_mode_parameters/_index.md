﻿---
title: get_array_mode_parameters method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells/customfunctiondefinition/get_array_mode_parameters/
is_root: false
---

## get_array_mode_parameters {#str}

Gets the indices of given custom function's parameters that need to be calculated in array mode.


### Returns 


Indices of the parameters that need to be calculated in array mode for given custom function.
Default is null, there is no parameter which needs to be calculated in array mode for the custom function.


```python
def get_array_mode_parameters(self, function_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| function_name | str | Name of the custom function. |
### Remarks

For an expression that needs to be calculated, taking A:A+B:B as an example:
Generally in value mode it will be calculated to a single value according to current cell base.
But in array mode, all values of A1+B1,A2+B2,A3+B3,... will be calculated and used for the calculation.


### See Also
* module [`aspose.cells`](../../)
* class [`CustomFunctionDefinition`](/cells/python-net/aspose.cells/customfunctiondefinition)
