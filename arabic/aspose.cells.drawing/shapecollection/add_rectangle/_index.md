---
title: طريقة add_rectangle
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 260
url: /ar/aspose.cells.drawing/shapecollection/add_rectangle/
is_root: false
---
##  add_rectangle(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
إضافة شكل مستطيل إلى ورقة العمل.


###  عائدات

كائن على شكل مستطيل.


```python

def add_rectangle(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| upper_left_row | int | مؤشر الصف العلوي الأيسر.|
| top | int | يمثل الإزاحة الرأسية لشكل المستطيل من الصف الأيسر، بوحدة البكسل.|
| upper_left_column | int | فهرس العمود العلوي الأيسر.|
| left | int | يمثل الإزاحة الأفقية لشكل المستطيل من العمود الأيسر، بوحدة البكسل.|
| height | int | يمثل ارتفاع الشكل المستطيلي، بوحدة البكسل.|
| width | int | يمثل عرض RectangleShape، بوحدة البكسل.|

###  مثال

```python

#  add a rectangle
rectangleShape = shapes.add_rectangle(2, 0, 2, 0, 130, 130)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`ShapeCollection`](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
