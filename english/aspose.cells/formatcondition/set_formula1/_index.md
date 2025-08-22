﻿---
title: set_formula1 method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 40
url: /aspose.cells/formatcondition/set_formula1/
is_root: false
---

## set_formula1(self, formula, is_r1c1, is_local) {#System.String-bool-bool}

Sets the value or expression associated with this format condition.



```python

def set_formula1(self, formula, is_r1c1, is_local):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| formula | System.String | The value or expression associated with this format condition.<br/>If the input value starts with '=', then it will be taken as formula. Otherwise it will be taken as plain value(text, number, bool).<br/>For text value that starts with '=', user may input it as formula in format: "=\"=...\"". |
| is_r1c1 | bool | Whether the formula is R1C1 formula. |
| is_local | bool | Whether the formula is locale formatted. |



### See Also
* module [`aspose.cells`](../../)
* class [`FormatCondition`](/cells/python-net/aspose.cells/formatcondition)
