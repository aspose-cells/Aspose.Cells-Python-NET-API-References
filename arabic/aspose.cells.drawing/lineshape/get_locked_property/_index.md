---
title: طريقة get_locked_property
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 130
url: /ar/aspose.cells.drawing/lineshape/get_locked_property/
is_root: false
---
##  get_locked_property(self, type) {#aspose.cells.drawing.ShapeLockType}
يحصل على قيمة الممتلكات المقفولة.


###  عائدات

إرجاع قيمة الخاصية المقفلة.


```python

def get_locked_property(self, type):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| type | [`ShapeLockType`](/cells/python-net/ar/aspose.cells.drawing/shapelocktype) | نوع الخاصية المقفولة بالشكل.|

###  مثال

```python
from aspose.cells.drawing import ShapeLockType

noAdjustHandles = 0
if shape.get_locked_property(ShapeLockType.ADJUST_HANDLES):
    noAdjustHandles = 1

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`LineShape`](/cells/python-net/ar/aspose.cells.drawing/lineshape)
