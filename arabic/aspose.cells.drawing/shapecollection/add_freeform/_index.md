---
title: طريقة add_freeform
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 120
url: /ar/aspose.cells.drawing/shapecollection/add_freeform/
is_root: false
---
##  add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths) {#int-int-int-int-int-int-list}
يضيف شكلًا حرًا إلى ورقة العمل.


###  عائدات

شكل حر.


```python

def add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| upper_left_row | int | مؤشر الصف العلوي الأيسر.|
| top | int | يمثل الإزاحة الرأسية للشكل الحر من الصف الأيسر، بوحدة البكسل.|
| upper_left_column | int | فهرس العمود العلوي الأيسر.|
| left | int | يمثل الإزاحة الأفقية للشكل الحر من العمود الأيسر، بوحدة البكسل.|
| height | int | يمثل ارتفاع الشكل الحر، بوحدة البكسل.|
| width | int | يمثل عرض الشكل الحر، بوحدة البكسل.|
| paths | list | يمثل مسارًا محددًا من قبل المستخدم|
###  ملاحظات

ملاحظة: يمكن أن يكون العرض والارتفاع في المعلمات أي قيم عددية صحيحة موجبة، وليس إجمالي عرض وارتفاع مصفوفة ShapePath المحددة بواسطة "paths". العلاقة بينهما هي علاقة تغيير الحجم والتعبئة، أي أن كل كائن ShapePath سيتم تغيير حجمه وفقًا للعرض والارتفاع. لذلك، عند وجود عدة كائنات في "paths"، يجب تصميم كل كائن ShapePath بشكل معقول لتلبية التوقعات. عند وجود كائن ShapePath واحد فقط وعدم وجود متطلبات أخرى، يُعد تمرير عرض الكائن وارتفاعه كقيم للمعلمات حلاً جيدًا.
###  مثال


```python
from aspose.cells.drawing import ShapePath

# Custom figure
shapePath = ShapePath()
shapePath.move_to(60, 45)
shapePath.arc_to(25, 25, 0, 270)
shapePath.close()
shapePath.move_to(60, 20)
shapePath.line_to(110, 70)
shapePath.line_to(125, 155.5)
shapePath.arc_to(35.5, 35.5, 0, 270)
shapePath.close()
shapePath.move_to(150, 45)
shapePath.arc_to(25, 25, 0, 270)
shapePathW = shapePath.width_pixel
shapePathH = shapePath.height_pixel
shapePath1 = ShapePath()
shapePath1.move_to(0, 0)
shapePath1.cubic_bezier_to(48.24997, 0.6844,                                 96.5, -7.148871,                                 130, 11.517795)
shapePath1.cubic_bezier_to(163.5, 30.18446,                                 182.24997, 75.351,                                 201, 120.517795)
shapePath1.move_to(150, 80)
shapePath1.arc_to(25, 25, 0, 270)
if shapePath1.width_pixel > shapePathW:
    shapePathW = shapePath1.width_pixel
if shapePath1.height_pixel > shapePathH:
    shapePathH = shapePath1.height_pixel
# Notice: shapePathH and shapePathH can be any positive integer values, here we just simply set them.
# Insert custom figure into worksheet
shapes.add_freeform(1, 0, 1, 0, shapePathH, shapePathW, [shapePath, shapePath1])

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`ShapeCollection`](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
