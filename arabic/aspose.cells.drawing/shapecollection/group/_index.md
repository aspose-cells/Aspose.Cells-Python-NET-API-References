---
title: طريقة group
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 420
url: /ar/aspose.cells.drawing/shapecollection/group/
is_root: false
---
##  group(group_items) {#list}
اجمع الأشكال.


###  عائدات

أعد الشكل group.


```python
def group(self, group_items):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| group_items | list | عناصر المجموعة.|
###  ملاحظات

لا يجب تجميع الشكل الموجود في groupItems.
يجب أن يكون الشكل في مجموعة الأشكال هذه.
###  مثال

```python

# add first shape
shapes.add_rectangle(2, 0, 2, 0, 50, 50)
# add second shape
shapes.add_rectangle(6, 0, 2, 0, 30, 30)
shapesArr = [shapes[0], shapes[1]]
groupShape = shapes.group(shapesArr)

```



###  أنظر أيضا
* وحدة [aspose.cells.drawing](../../)
* فئة [ShapeCollection](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
