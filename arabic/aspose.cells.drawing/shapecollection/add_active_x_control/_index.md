---
title: طريقة add_active_x_control
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells.drawing/shapecollection/add_active_x_control/
is_root: false
---
##  add_active_x_control(self, type, top_row, top, left_column, left, width, height) {#aspose.cells.drawing.activexcontrols.ControlType-int-int-int-int-int-int}
إنشاء عنصر تحكم Activex.


###  عائدات




```python

def add_active_x_control(self, type, top_row, top, left_column, left, width, height):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| type | aspose.cells.drawing.activexcontrols.ControlType | نوع التحكم.|
| top_row | int | مؤشر الصف العلوي الأيسر.|
| top | int | يمثل الإزاحة الرأسية للشكل من صفه الأيسر، بوحدة البكسل.|
| left_column | int | فهرس العمود العلوي الأيسر.|
| left | int | يمثل الإزاحة الأفقية للشكل من العمود الأيسر، بوحدة البكسل.|
| width | int | يمثل عرض الشكل بوحدة البكسل.|
| height | int | يمثل ارتفاع الشكل بوحدة البكسل.|

###  مثال

```python
from aspose.cells.drawing.activexcontrols import ControlType

# add an ActiveX control
activeXControl = shapes.add_active_x_control(ControlType.CHECK_BOX, 1, 0, 1, 0, 100, 50)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`ShapeCollection`](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
