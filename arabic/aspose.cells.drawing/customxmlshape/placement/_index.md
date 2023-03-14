---
title: placement الملكية
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 820
url: /ar/aspose.cells.drawing/customxmlshape/placement/
is_root: false
---
##  placement الملكية

يمثل الطريقة التي يتم بها إرفاق الكائن الرسومي بالخلايا الموجودة أسفله.
تتحكم الخاصية في placement لكائن موجود بورقة عمل.

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
* وحدة [aspose.cells.drawing](../../)
* فئة [CustomXmlShape](/cells/python-net/ar/aspose.cells.drawing/customxmlshape)
* فئة [PlacementType](/cells/python-net/ar/aspose.cells.drawing/placementtype)
