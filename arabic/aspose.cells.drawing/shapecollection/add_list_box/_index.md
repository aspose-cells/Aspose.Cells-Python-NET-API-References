---
title: طريقة add_list_box
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 190
url: /ar/aspose.cells.drawing/shapecollection/add_list_box/
is_root: false
---
##  add_list_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
إضافة ListBox إلى ورقة العمل.


###  عائدات

كائن ListBox.


```python

def add_list_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| upper_left_row | int | مؤشر الصف العلوي الأيسر.|
| top | int | يمثل الإزاحة الرأسية لـ ListBox من الصف الأيسر، بوحدة البكسل.|
| upper_left_column | int | فهرس العمود العلوي الأيسر.|
| left | int | يمثل الإزاحة الأفقية لـ ListBox من العمود الأيسر، بوحدة البكسل.|
| height | int | يمثل ارتفاع ListBox، بوحدة البكسل.|
| width | int | يمثل عرض ListBox بوحدة البكسل.|

###  مثال

```python

# add a list box
listBox = shapes.add_list_box(1, 0, 1, 0, 100, 50)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`ShapeCollection`](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
