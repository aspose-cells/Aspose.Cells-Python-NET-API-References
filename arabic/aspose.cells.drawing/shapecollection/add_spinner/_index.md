---
title: طريقة add_spinner
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 320
url: /ar/aspose.cells.drawing/shapecollection/add_spinner/
is_root: false
---
##  add_spinner(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
إضافة Spinner إلى ورقة العمل.


###  عائدات

كائن دوار.


```python

def add_spinner(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| upper_left_row | int | مؤشر الصف العلوي الأيسر.|
| top | int |يمثل الإزاحة الرأسية لـ Spinner من الصف الأيسر، بوحدة البكسل.|
| upper_left_column | int | فهرس العمود العلوي الأيسر.|
| left | int | يمثل الإزاحة الأفقية لـ Spinner من العمود الأيسر، بوحدة البكسل.|
| height | int | يمثل ارتفاع Spinner، بوحدة البكسل.|
| width | int | يمثل عرض Spinner، بوحدة البكسل.|

###  مثال

```python

# add a spinner
spinner = shapes.add_spinner(1, 0, 1, 0, 100, 50)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`ShapeCollection`](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
