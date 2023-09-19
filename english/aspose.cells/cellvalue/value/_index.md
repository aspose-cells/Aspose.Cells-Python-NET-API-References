﻿---
title: value property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 40
url: /aspose.cells/cellvalue/value/
is_root: false
---

## value property


Represents the cell value.

### Remarks 


The value must be of the correct type of object corresponding to the [`CellValue.type`](/cells/python-net/aspose.cells/cellvalue#type):
| Type | Value |
| :- | :- |
| null, any other object will be ignored |
| double |
| DateTime |
| string |
| bool |
| error string such as "#VALUE!", "#NAME?", ... |
### Definition:
```python
@property
def value(self):
    ...
@value.setter
def value(self, value):
    ...
```

### See Also
* module [`aspose.cells`](../../)
* class [`CellValue`](/cells/python-net/aspose.cells/cellvalue)
