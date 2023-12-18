﻿---
title: width_in_shape property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 1240
url: /aspose.cells.drawing/arcshape/width_in_shape/
is_root: false
---

## width_in_shape property


Represents the width of the shape, in unit of 1/4000 of the parent shape.

### Remarks 


Only Applies when this shape in the group or chart.

### Example 


```python

if shape.is_in_group and shape.width_in_shape == 2000:
    shape.width_in_shape = 4000

```
### Definition:
```python
@property
def width_in_shape(self):
    ...
@width_in_shape.setter
def width_in_shape(self, value):
    ...
```

### See Also
* module [`aspose.cells.drawing`](../../)
* class [`ArcShape`](/cells/python-net/aspose.cells.drawing/arcshape)
