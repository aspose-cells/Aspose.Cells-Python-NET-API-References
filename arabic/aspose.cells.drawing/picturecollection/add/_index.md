---
title: طريقة add
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells.drawing/picturecollection/add/
is_root: false
---
##  add(self, upper_left_row, upper_left_column, stream) {#int-int-io.RawIOBase}
إضافة صورة إلى المجموعة.


###  عائدات

[`Picture`](/cells/python-net/ar/aspose.cells.drawing/picture) فهرس الكائن.


```python

def add(self, upper_left_row, upper_left_column, stream):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| upper_left_row | int | مؤشر الصف العلوي الأيسر.|
| upper_left_column | int | فهرس العمود العلوي الأيسر.|
| stream | io.RawIOBase | كائن التدفق الذي يحتوي على بيانات الصورة.|

###  مثال

```python

# add a picture
with open("image.jpg", "rb") as fs:
    pictures.add(1, 1, fs)

```


##  add(self, upper_left_row, upper_left_column, file_name) {#int-int-str}
إضافة صورة إلى المجموعة.


###  عائدات

[`Picture`](/cells/python-net/ar/aspose.cells.drawing/picture) فهرس الكائن.


```python

def add(self, upper_left_row, upper_left_column, file_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| upper_left_row | int | مؤشر الصف العلوي الأيسر.|
| upper_left_column | int | فهرس العمود العلوي الأيسر.|
| file_name | str | اسم ملف الصورة.|

###  مثال

```python

# add a picture
pictures.add(1, 1, "image.jpg")

```


##  add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream) {#int-int-int-int-io.RawIOBase}
إضافة صورة إلى المجموعة.


###  عائدات

[`Picture`](/cells/python-net/ar/aspose.cells.drawing/picture) فهرس الكائن.


```python

def add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream):
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
    pictures.add(1, 1, 5, 5, fs)

```


##  add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name) {#int-int-int-int-str}
إضافة صورة إلى المجموعة.


###  عائدات

[`Picture`](/cells/python-net/ar/aspose.cells.drawing/picture) فهرس الكائن.


```python

def add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| upper_left_row | int | مؤشر الصف العلوي الأيسر.|
| upper_left_column | int | فهرس العمود العلوي الأيسر.|
| lower_right_row | int | مؤشر الصف السفلي الأيمن|
| lower_right_column | int | فهرس العمود السفلي الأيمن|
| file_name | str | اسم ملف الصورة.|

###  مثال

```python

# add a picture
pictures.add(1, 1, 5, 5, "image.jpg")

```


##  add(self, upper_left_row, upper_left_column, stream, width_scale, height_scale) {#int-int-io.RawIOBase-int-int}
إضافة صورة إلى المجموعة.


###  عائدات

[`Picture`](/cells/python-net/ar/aspose.cells.drawing/picture) فهرس الكائن.


```python

def add(self, upper_left_row, upper_left_column, stream, width_scale, height_scale):
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
    pictures.add(1, 1, fs, 50, 50)

```


##  add(self, upper_left_row, upper_left_column, file_name, width_scale, height_scale) {#int-int-str-int-int}
إضافة صورة إلى المجموعة.


###  عائدات

[`Picture`](/cells/python-net/ar/aspose.cells.drawing/picture) فهرس الكائن.


```python

def add(self, upper_left_row, upper_left_column, file_name, width_scale, height_scale):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| upper_left_row | int | مؤشر الصف العلوي الأيسر.|
| upper_left_column | int | فهرس العمود العلوي الأيسر.|
| file_name | str | اسم ملف الصورة.|
| width_scale | int | مقياس عرض الصورة، نسبة مئوية.|
| height_scale | int | مقياس ارتفاع الصورة، نسبة مئوية.|

###  مثال

```python

# add a picture
pictures.add(1, 1, "image.jpg", 50, 50)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`Picture`](/cells/python-net/ar/aspose.cells.drawing/picture)
* فئة [`PictureCollection`](/cells/python-net/ar/aspose.cells.drawing/picturecollection)
