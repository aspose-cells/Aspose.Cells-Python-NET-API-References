---
title: طريقة get_locked_property
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 110
url: /ar/aspose.cells.drawing/rectangleshape/get_locked_property/
is_root: false
---
##  get_locked_property(type) {#ShapeLockType}
يحصل على قيمة الممتلكات المقفلة.


###  عائدات

ترجع قيمة الممتلكات المقفلة.


```python
def get_locked_property(self, type):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| type | [ShapeLockType](/cells/python-net/ar/aspose.cells.drawing/shapelocktype) | نوع خاصية تأمين الشكل.|

###  مثال

```python
from aspose.cells.drawing import ShapeLockType

noAdjustHandles = 0
if shape.get_locked_property(ShapeLockType.ADJUST_HANDLES):
    noAdjustHandles = 1

```



###  أنظر أيضا
* وحدة [aspose.cells.drawing](../../)
* فئة [RectangleShape](/cells/python-net/ar/aspose.cells.drawing/rectangleshape)
