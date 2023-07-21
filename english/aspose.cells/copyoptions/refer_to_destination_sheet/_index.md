﻿---
title: refer_to_destination_sheet property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 80
url: /aspose.cells/copyoptions/refer_to_destination_sheet/
is_root: false
---

## refer_to_destination_sheet property


When copying the range in the same file and the chart refers to the source sheet,
False means the copied chart's data source will not be changed.
True means the copied chart's data source refers to the destination sheet.

### Remarks 


The default value is false, it works as MS Excel.
### Definition:
```python
@property
def refer_to_destination_sheet(self):
    ...
@refer_to_destination_sheet.setter
def refer_to_destination_sheet(self, value):
    ...
```

### See Also
* module [`aspose.cells`](../../)
* class [`CopyOptions`](/cells/python-net/aspose.cells/copyoptions)
