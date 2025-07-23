---
title: طريقة add_button
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 60
url: /ar/aspose.cells.drawing/shapecollection/add_button/
is_root: false
---
##  add_button(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
إضافة زر إلى ورقة العمل.


###  عائدات

كائن زر.


```python

def add_button(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| upper_left_row | int | مؤشر الصف العلوي الأيسر.|
| top | int | يمثل الإزاحة الرأسية للزر من صفه الأيسر، بوحدة البكسل.|
| upper_left_column | int | فهرس العمود العلوي الأيسر.|
| left | int |يمثل الإزاحة الأفقية للزر من عموده الأيسر، بوحدة البكسل.|
| height | int | يمثل ارتفاع الزر، بوحدة البكسل.|
| width | int | يمثل عرض الزر بوحدة البكسل.|

###  مثال

```python

# add a button
button = shapes.add_button(1, 0, 1, 0, 100, 50)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`ShapeCollection`](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
