﻿---
title: trim_leading_blank_row_and_column property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 230
url: /aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column/
is_root: false
---

## trim_leading_blank_row_and_column property


Indicates whether leading blank rows and columns should be trimmed like what ms excel does.
Default is true.

### Remarks 


Same with the rule in ms excel, a row/column will not be taken as blank if it has custom style,
even if it contains no cell data.
When saving with LightCells mode, this option takes no effect.
User should control the output range by the implementation of [`TxtSaveOptions.LightCellsDataProvider`](/cells/python-net/aspose.cells/txtsaveoptions)
or by speicifing [`TxtSaveOptions.export_area`](/cells/python-net/aspose.cells/txtsaveoptions#export_area)
### Definition:
```python
@property
def trim_leading_blank_row_and_column(self):
    ...
@trim_leading_blank_row_and_column.setter
def trim_leading_blank_row_and_column(self, value):
    ...
```

### See Also
* module [`aspose.cells`](../../)
* class [`TxtSaveOptions`](/cells/python-net/aspose.cells/txtsaveoptions)
