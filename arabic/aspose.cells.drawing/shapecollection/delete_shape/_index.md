---
title: طريقة delete_shape
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 410
url: /ar/aspose.cells.drawing/shapecollection/delete_shape/
is_root: false
---
##  delete_shape(shape) {#Shape}
حذف شكل. إذا كان الشكل في المجموعة أو كان شكل تعليق ، فلن يتم حذفه.



```python
def delete_shape(self, shape):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| shape | [Shape](/cells/python-net/ar/aspose.cells.drawing/shape) |  |

###  مثال

```python

# add first shape
firstShape = shapes.add_rectangle(2, 0, 2, 0, 50, 50)
# add second shape
secondShape = shapes.add_rectangle(6, 0, 2, 0, 30, 30)
# del
shapes.delete_shape(firstShape)

```



###  أنظر أيضا
* وحدة [aspose.cells.drawing](../../)
* فئة [ShapeCollection](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
