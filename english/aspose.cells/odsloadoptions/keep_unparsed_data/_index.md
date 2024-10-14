﻿---
title: keep_unparsed_data property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 150
url: /aspose.cells/odsloadoptions/keep_unparsed_data/
is_root: false
---

## keep_unparsed_data property


Whether keep the unparsed data in memory for the Workbook when it is loaded from template file. Default is true.

### Remarks 


For scenarios that user only needs to read some contents from template file and does not need to save the workbook back,
set this property as false may improve performance, especially when using it together with some kind of LoadFilter,
### Definition:
```python
@property
def keep_unparsed_data(self):
    ...
@keep_unparsed_data.setter
def keep_unparsed_data(self, value):
    ...
```

### See Also
* module [`aspose.cells`](../../)
* class [`OdsLoadOptions`](/cells/python-net/aspose.cells/odsloadoptions)
