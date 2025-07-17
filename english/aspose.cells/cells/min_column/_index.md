---
title: min_column property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 1180
url: /aspose.cells/cells/min_column/
is_root: false
---

## min_column property


Minimum column index of those cells that have been instantiated in the collection(does not include the column
where style is defined for the whole column but no cell has been instantiated in it).

### Remarks 


This property needs to iterate and check cells and rows dynamically,
so it is a time-consumed progress and should not be invoked repeatedly,
such as using it directly as condition in a loop.
### Definition:
```python
@property
def min_column(self):
    ...
```

### See Also
* module [`aspose.cells`](../../)
* class [`Cells`](/cells/python-net/aspose.cells/cells)
