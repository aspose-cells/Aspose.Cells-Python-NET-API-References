---
title: طريقة add_auto_shape
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 40
url: /ar/aspose.cells.drawing/shapecollection/add_auto_shape/
is_root: false
---
##  add_auto_shape(self, type, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.AutoShapeType-int-int-int-int-int-int}
إضافة شكل تلقائي إلى ورقة العمل.


###  عائدات

كائن شكل.


```python

def add_auto_shape(self, type, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| type | [`AutoShapeType`](/cells/python-net/ar/aspose.cells.drawing/autoshapetype) | نوع الشكل التلقائي.|
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
from aspose.cells.drawing import AutoShapeType

# Adds a AutoShape to the worksheet.
autoShape = shapes.add_auto_shape(AutoShapeType.CUBE, 1, 0, 1, 0, 100, 50)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`ShapeCollection`](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
