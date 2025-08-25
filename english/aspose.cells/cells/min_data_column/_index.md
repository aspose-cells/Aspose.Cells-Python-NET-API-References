---
title: min_data_column property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 1210
url: /aspose.cells/cells/min_data_column/
is_root: false
---

## min_data_column property


Minimum column index of cell which contains data.

### Remarks 


-1 will be returned if there is no cell which contains data.
This property needs to iterate and check all cells in a worksheet dynamically,
so it is a time-consumed progress and should not be invoked repeatedly,
such as using it directly as condition in a loop.
### Definition:
```python
@property
def min_data_column(self):
    ...
```

### See Also
* module [`aspose.cells`](../../)
* class [`Cells`](/cells/python-net/aspose.cells/cells)
