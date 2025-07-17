﻿---
title: placement property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 900
url: /aspose.cells.drawing/arcshape/placement/
is_root: false
---

## placement property


Represents the way the drawing object is attached to the cells below it.
The property controls the placement of an object on a worksheet.

### Example 


```python
from aspose.cells.drawing import PlacementType

if shape.placement == PlacementType.MOVE:
    shape.placement = PlacementType.MOVE_AND_SIZE

```
### Definition:
```python
@property
def placement(self):
    ...
@placement.setter
def placement(self, value):
    ...
```

### See Also
* module [`aspose.cells.drawing`](../../)
* class [`ArcShape`](/cells/python-net/aspose.cells.drawing/arcshape)
* class [`PlacementType`](/cells/python-net/aspose.cells.drawing/placementtype)
