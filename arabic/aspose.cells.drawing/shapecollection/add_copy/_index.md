---
title: طريقة add_copy
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 90
url: /ar/aspose.cells.drawing/shapecollection/add_copy/
is_root: false
---
##  add_copy(self, source_shape, top_row, top, left_column, left) {#aspose.cells.drawing.Shape-int-int-int-int}
إضافة شكل ونسخه إلى ورقة العمل.


###  عائدات

الكائن الجديد [`Shape`](/cells/python-net/ar/aspose.cells.drawing/shape).


```python

def add_copy(self, source_shape, top_row, top, left_column, left):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| source_shape | [`Shape`](/cells/python-net/ar/aspose.cells.drawing/shape) | شكل المصدر.|
| top_row | int |مؤشر الصف العلوي.|
| top | int | يمثل الإزاحة الرأسية من الصف العلوي، بوحدة البكسل.|
| left_column | int | فهرس العمود الأيسر.|
| left | int | يمثل الإزاحة الأفقية من العمود الأيسر، بوحدة البكسل.|

###  مثال

```python

# add a shape
rectangle = shapes.add_rectangle(2, 0, 2, 0, 130, 130)
# Adds and copies a shape.
shapes.add_copy(rectangle, 7, 0, 7, 0)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`Shape`](/cells/python-net/ar/aspose.cells.drawing/shape)
* فئة [`ShapeCollection`](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
