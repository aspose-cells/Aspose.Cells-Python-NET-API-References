---
title: placement property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 220
url: /aspose.cells.slicers/slicer/placement/
is_root: false
---

## placement property


Represents the way the drawing object is attached to the cells below it.
The property controls the placement of an object on a worksheet.

### Remarks 


NOTE: This member is now obsolete. Instead, 
please use [`Shape.placement`](/cells/python-net/aspose.cells.drawing/shape#placement) property. 
This property will be removed 12 months later since January 2026. 
Aspose apologizes for any inconvenience you may have experienced.

### Example 


```python
from aspose.cells.drawing import PlacementType

slicer.placement = PlacementType.FREE_FLOATING

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
* module [`aspose.cells.slicers`](../../)
* class [`PlacementType`](/cells/python-net/aspose.cells.drawing/placementtype)
* class [`Slicer`](/cells/python-net/aspose.cells.slicers/slicer)
