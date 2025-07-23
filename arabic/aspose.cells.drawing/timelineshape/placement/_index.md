---
title: placement عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 840
url: /ar/aspose.cells.drawing/timelineshape/placement/
is_root: false
---
##  placement عقار

يمثل الطريقة التي يتم بها ربط كائن الرسم بالخلايا الموجودة أسفله.
تتحكم الخاصية في placement لكائن موجود في ورقة العمل.

###  مثال

```python
from aspose.cells.drawing import PlacementType

if shape.placement == PlacementType.MOVE:
    shape.placement = PlacementType.MOVE_AND_SIZE

```
###  تعريف:
```python
@property
def placement(self):
    ...
@placement.setter
def placement(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`PlacementType`](/cells/python-net/ar/aspose.cells.drawing/placementtype)
* فئة [`TimelineShape`](/cells/python-net/ar/aspose.cells.drawing/timelineshape)
