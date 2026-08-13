---
title: is_outline property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 80
url: /aspose.cells/bordercollection/is_outline/
is_root: false
---

## is_outline property


Indicates if left, right, top, and bottom borders should be applied only to outside borders of a cell range.
Default value is true.

### Remarks 


Only works when applying to a range for conditional formattings, pivot tables.
If false,left, right, top, and bottom will apply to each cell, otherwise only to outside borders of a cell range.
If true, please set horizontal and vertical border of inner borders of range for conditional formattings, pivot tables.
### Definition:
```python
@property
def is_outline(self):
    ...
@is_outline.setter
def is_outline(self, value):
    ...
```

### See Also
* module [`aspose.cells`](../../)
* class [`BorderCollection`](/cells/python-net/aspose.cells/bordercollection)
