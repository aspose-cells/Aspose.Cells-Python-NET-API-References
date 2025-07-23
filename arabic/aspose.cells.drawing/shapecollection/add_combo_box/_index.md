---
title: طريقة add_combo_box
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 80
url: /ar/aspose.cells.drawing/shapecollection/add_combo_box/
is_root: false
---
##  add_combo_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
إضافة مربع تحرير وسرد إلى ورقة العمل.


###  عائدات

كائن ComboBox.


```python

def add_combo_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| upper_left_row | int | مؤشر الصف العلوي الأيسر.|
| top | int | يمثل الإزاحة الرأسية لـ ComboBox من الصف الأيسر، بوحدة البكسل.|
| upper_left_column | int | فهرس العمود العلوي الأيسر.|
| left | int | يمثل الإزاحة الأفقية لـ ComboBox من العمود الأيسر، بوحدة البكسل.|
| height | int | يمثل ارتفاع ComboBox، بوحدة البكسل.|
| width | int | يمثل عرض ComboBox، بوحدة البكسل.|

###  مثال

```python

# add a combo box
comboBox = shapes.add_combo_box(1, 0, 1, 0, 100, 50)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`ShapeCollection`](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
