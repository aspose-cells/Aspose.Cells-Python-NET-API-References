---
title: طريقة add_text_box
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 340
url: /ar/aspose.cells.drawing/shapecollection/add_text_box/
is_root: false
---
##  add_text_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
إضافة مربع نص إلى ورقة العمل.


###  عائدات

كائن [`TextBox`](/cells/python-net/ar/aspose.cells.drawing/textbox).


```python

def add_text_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| upper_left_row | int | مؤشر الصف العلوي الأيسر.|
| top | int | يمثل الإزاحة الرأسية لمربع النص من الصف العلوي، بوحدة البكسل.|
| upper_left_column | int | فهرس العمود العلوي الأيسر.|
| left | int | يمثل الإزاحة الأفقية لمربع النص من العمود الأيسر، بوحدة البكسل.|
| height | int | يمثل ارتفاع مربع النص، بوحدة البكسل.|
| width | int | يمثل عرض مربع النص بوحدة البكسل.|

###  مثال

```python

# add a TextBox
textBox = shapes.add_text_box(1, 0, 1, 0, 100, 50)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`ShapeCollection`](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
* فئة [`TextBox`](/cells/python-net/ar/aspose.cells.drawing/textbox)
