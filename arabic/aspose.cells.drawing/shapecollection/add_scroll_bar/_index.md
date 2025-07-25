---
title: طريقة add_scroll_bar
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 270
url: /ar/aspose.cells.drawing/shapecollection/add_scroll_bar/
is_root: false
---
##  add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
إضافة شريط التمرير إلى ورقة العمل.


###  عائدات

كائن ScrollBar.


```python

def add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| upper_left_row | int | مؤشر الصف العلوي الأيسر.|
| top | int |يمثل الإزاحة الرأسية لشريط التمرير من الصف الأيسر، بوحدة البكسل.|
| upper_left_column | int | فهرس العمود العلوي الأيسر.|
| left | int | يمثل الإزاحة الأفقية لشريط التمرير من العمود الأيسر، بوحدة البكسل.|
| height | int | يمثل ارتفاع شريط التمرير، بوحدة البكسل.|
| width | int | يمثل عرض شريط التمرير، بوحدة البكسل.|

###  مثال

```python

# add a scroll bar
scrollBar = shapes.add_scroll_bar(1, 0, 1, 0, 100, 20)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`ShapeCollection`](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
