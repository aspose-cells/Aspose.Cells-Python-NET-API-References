---
title: set_local_built_in_name method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 330
url: /aspose.cells/settableglobalizationsettings/set_local_built_in_name/
is_root: false
---

## set_local_built_in_name {#str-str-bool}

Sets the locale dependent text for the built-in name with given standard name text.



```python
def set_local_built_in_name(self, standard_name, local_name, bidirectional):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| standard_name | str | Standard(en-US locale) name text of built-in name. |
| local_name | str | Locale dependent name text |
| bidirectional | bool | Whether map the local name text to standard name text automatically.<br/>If true, the local name text will be mapped to standard name text automatically<br/>so user does not need to call [`SettableGlobalizationSettings.set_standard_built_in_name`](/cells/python-net/aspose.cells/settableglobalizationsettings/set_standard_built_in_name) again<br/>for the same standard and local names pair |



### See Also
* module [`aspose.cells`](../../)
* class [`SettableGlobalizationSettings`](/cells/python-net/aspose.cells/settableglobalizationsettings)
