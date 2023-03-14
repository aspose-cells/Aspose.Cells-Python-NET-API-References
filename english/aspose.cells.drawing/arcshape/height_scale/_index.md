﻿---
title: height_scale property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 530
url: /aspose.cells.drawing/arcshape/height_scale/
is_root: false
---

## height_scale property


Gets and sets the height scale,in unit of percent of the original picture height.
If the shape is not picture ,the HeightScale property only returns 100;

### Example 


```python

if shape.height_scale == 3:
    shape.height_scale = 1

```
### Definition:
```python
@property
def height_scale(self):
    ...
@height_scale.setter
def height_scale(self, value):
    ...
```

### See Also
* module [aspose.cells.drawing](../../)
* class [ArcShape](/cells/python-net/aspose.cells.drawing/arcshape)
