---
title: طريقة add_group_box
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 130
url: /ar/aspose.cells.drawing/shapecollection/add_group_box/
is_root: false
---
##  add_group_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
إضافة GroupBox إلى ورقة العمل.


###  عائدات

كائن GroupBox.


```python

def add_group_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| upper_left_row | int | مؤشر الصف العلوي الأيسر.|
| top | int | يمثل الإزاحة الرأسية لـ GroupBox من الصف الأيسر، بوحدة البكسل.|
| upper_left_column | int | فهرس العمود العلوي الأيسر.|
| left | int | يمثل الإزاحة الأفقية لـ GroupBox من العمود الأيسر، بوحدة البكسل.|
| height | int | يمثل ارتفاع GroupBox، بوحدة البكسل.|
| width | int | يمثل عرض GroupBox بوحدة البكسل.|

###  مثال

```python

# add a group box
groupBox = shapes.add_group_box(1, 0, 1, 0, 100, 50)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`ShapeCollection`](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
