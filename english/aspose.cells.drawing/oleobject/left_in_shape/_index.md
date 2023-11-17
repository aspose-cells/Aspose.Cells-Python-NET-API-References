﻿---
title: left_in_shape property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 820
url: /aspose.cells.drawing/oleobject/left_in_shape/
is_root: false
---

## left_in_shape property


Represents the horizontal offset of shape from the left border of the parent shape, 
in unit of 1/4000 of width of the parent shape.

### Remarks 


Only Applies when this shape in the group or chart.

### Example 


```python

if shape.is_in_group and shape.left_in_shape == 2000:
    shape.left_in_shape = 4000

```
### Definition:
```python
@property
def left_in_shape(self):
    ...
@left_in_shape.setter
def left_in_shape(self, value):
    ...
```

### See Also
* module [`aspose.cells.drawing`](../../)
* class [`OleObject`](/cells/python-net/aspose.cells.drawing/oleobject)
