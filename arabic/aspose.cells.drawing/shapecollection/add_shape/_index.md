---
title: طريقة add_shape
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 280
url: /ar/aspose.cells.drawing/shapecollection/add_shape/
is_root: false
---
##  add_shape(self, type, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.MsoDrawingType-int-int-int-int-int-int}
إضافة شكل إلى ورقة العمل.


###  عائدات

كائن شكل.


```python

def add_shape(self, type, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| type | [`MsoDrawingType`](/cells/python-net/ar/aspose.cells.drawing/msodrawingtype) | نوع الرسم Mso.|
| upper_left_row | int | مؤشر الصف العلوي الأيسر.|
| top | int | يمثل الإزاحة الرأسية للشكل من صفه الأيسر، بوحدة البكسل.|
| upper_left_column | int | فهرس العمود العلوي الأيسر.|
| left | int | يمثل الإزاحة الأفقية للشكل من العمود الأيسر، بوحدة البكسل.|
| height | int | يمثل ارتفاع الشكل بوحدة البكسل.|
| width | int | يمثل عرض الشكل بوحدة البكسل.|
###  ملاحظات

لا يمكن أن يكون النوع Chart/Comment/Picture/OleObject/Polygon/DialogBox
###  مثال


```python
from aspose.cells.drawing import MsoDrawingType

# Add a shape of the specified type
shapeByType = shapes.add_shape(MsoDrawingType.CELLS_DRAWING, 1, 0, 1, 0, 100, 50)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`ShapeCollection`](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
