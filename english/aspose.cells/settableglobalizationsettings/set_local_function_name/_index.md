---
title: set_local_function_name method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 350
url: /aspose.cells/settableglobalizationsettings/set_local_function_name/
is_root: false
---

## set_local_function_name(self, standard_name, local_name, bidirectional) {#str-str-bool}

Sets the locale dependent function name corresponding to given standard function name.



```python

def set_local_function_name(self, standard_name, local_name, bidirectional):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| standard_name | str | Standard(en-US locale) function name. |
| local_name | str | Locale dependent function name |
| bidirectional | bool | Whether map the local function name to standard function name automatically.<br/>If true, the local name will be mapped to standard name automatically<br/>so user does not need to call [`SettableGlobalizationSettings.set_standard_function_name`](/cells/python-net/aspose.cells/settableglobalizationsettings/set_standard_function_name) again<br/>for the same standard and local names pair |



### See Also
* module [`aspose.cells`](../../)
* class [`SettableGlobalizationSettings`](/cells/python-net/aspose.cells/settableglobalizationsettings)
