---
title: preserve_padding_spaces property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 130
url: /aspose.cells/formulasettings/preserve_padding_spaces/
is_root: false
---

## preserve_padding_spaces property


Indicates whether to preserve those spaces and line breaks that are padded between formula tokens while getting and setting formulas.
Default value is false.

### Remarks 


Generally those spaces and line breaks are jsut for visual purpose,
Preserving them or not does not affect the calculated result.
For performance consideration, if there is no special requirement,
it is better not to preserve them while processing formulas.
### Definition:
```python
@property
def preserve_padding_spaces(self):
    ...
@preserve_padding_spaces.setter
def preserve_padding_spaces(self, value):
    ...
```

### See Also
* module [`aspose.cells`](../../)
* class [`FormulaSettings`](/cells/python-net/aspose.cells/formulasettings)
