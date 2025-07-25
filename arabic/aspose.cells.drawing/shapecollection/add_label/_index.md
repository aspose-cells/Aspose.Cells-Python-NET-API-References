---
title: طريقة add_label
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 150
url: /ar/aspose.cells.drawing/shapecollection/add_label/
is_root: false
---
##  add_label(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
إضافة تسمية إلى ورقة العمل.


###  عائدات

كائن تسمية.


```python

def add_label(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| upper_left_row | int | مؤشر الصف العلوي الأيسر.|
| top | int |يمثل الإزاحة الرأسية للتسمية من صفها الأيسر، بوحدة البكسل.|
| upper_left_column | int | فهرس العمود العلوي الأيسر.|
| left | int | يمثل الإزاحة الأفقية للتسمية من العمود الأيسر، بوحدة البكسل.|
| height | int | يمثل ارتفاع الملصق بوحدة البكسل.|
| width | int | يمثل عرض الملصق بوحدة البكسل.|

###  مثال

```python

# add a label
label = shapes.add_label(1, 0, 1, 0, 100, 50)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`ShapeCollection`](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
