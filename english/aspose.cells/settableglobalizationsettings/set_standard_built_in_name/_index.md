---
title: set_standard_built_in_name method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 370
url: /aspose.cells/settableglobalizationsettings/set_standard_built_in_name/
is_root: false
---

## set_standard_built_in_name(self, local_name, standard_name, bidirectional) {#System.String-System.String-bool}

Sets the locale dependent function name according to given standard function name.



```python

def set_standard_built_in_name(self, local_name, standard_name, bidirectional):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| local_name | System.String | Locale dependent function name |
| standard_name | System.String | Standard(en-US locale) function name. |
| bidirectional | bool | Whether map the standard name text to local name text automatically.<br/>If true, the standar name text will be mapped to local name text automatically<br/>so user does not need to call [`SettableGlobalizationSettings.set_local_built_in_name`](/cells/python-net/aspose.cells/settableglobalizationsettings/set_local_built_in_name) again<br/>for the same standard and local names pair |



### See Also
* module [`aspose.cells`](../../)
* class [`SettableGlobalizationSettings`](/cells/python-net/aspose.cells/settableglobalizationsettings)
