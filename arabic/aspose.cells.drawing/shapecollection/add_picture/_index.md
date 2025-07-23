---
title: طريقة add_picture
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 230
url: /ar/aspose.cells.drawing/shapecollection/add_picture/
is_root: false
---
##  add_picture(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream) {#int-int-int-int-io.RawIOBase}
إضافة صورة إلى المجموعة.


###  عائدات

[`Picture`](/cells/python-net/ar/aspose.cells.drawing/picture) صورة الكائن.


```python

def add_picture(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| upper_left_row | int | مؤشر الصف العلوي الأيسر.|
| upper_left_column | int | فهرس العمود العلوي الأيسر.|
| lower_right_row | int | مؤشر الصف السفلي الأيمن|
| lower_right_column | int | فهرس العمود السفلي الأيمن|
| stream | io.RawIOBase | كائن التدفق الذي يحتوي على بيانات الصورة.|

###  مثال

```python

# add a picture
with open("image.jpg", "rb") as fs:
    picture = shapes.add_picture(1, 0, 1, 0, fs)

```


##  add_picture(self, upper_left_row, upper_left_column, stream, width_scale, height_scale) {#int-int-io.RawIOBase-int-int}
إضافة صورة إلى المجموعة.


###  عائدات

[`Picture`](/cells/python-net/ar/aspose.cells.drawing/picture) صورة الكائن.


```python

def add_picture(self, upper_left_row, upper_left_column, stream, width_scale, height_scale):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| upper_left_row | int | مؤشر الصف العلوي الأيسر.|
| upper_left_column | int | فهرس العمود العلوي الأيسر.|
| stream | io.RawIOBase | كائن التدفق الذي يحتوي على بيانات الصورة.|
| width_scale | int | مقياس عرض الصورة، نسبة مئوية.|
| height_scale | int | مقياس ارتفاع الصورة، نسبة مئوية.|

###  مثال

```python

# add a picture
with open("image.jpg", "rb") as fs:
    picture = shapes.add_picture(1, 1, fs, 50, 60)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`Picture`](/cells/python-net/ar/aspose.cells.drawing/picture)
* فئة [`ShapeCollection`](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
