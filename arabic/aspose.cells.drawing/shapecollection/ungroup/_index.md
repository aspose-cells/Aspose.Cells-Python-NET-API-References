---
title: طريقة ungroup
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 500
url: /ar/aspose.cells.drawing/shapecollection/ungroup/
is_root: false
---
##  ungroup(self, group) {#aspose.cells.drawing.GroupShape}
إلغاء تجميع عناصر الشكل.



```python

def ungroup(self, group):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| group | [`GroupShape`](/cells/python-net/ar/aspose.cells.drawing/groupshape) | شكل المجموعة.|
###  ملاحظات

إذا تم تجميع شكل المجموعة بواسطة شكل مجموعة آخر، فلن يتم فعل أي شيء.
###  مثال


```python

# add first shape
shapes.add_rectangle(2, 0, 2, 0, 50, 50)
# add second shape
shapes.add_rectangle(6, 0, 2, 0, 30, 30)
# group
shapesArr = [shapes[0], shapes[1]]
groupShape = shapes.group(shapesArr)
# ungroup
shapes.ungroup(groupShape)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`ShapeCollection`](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
