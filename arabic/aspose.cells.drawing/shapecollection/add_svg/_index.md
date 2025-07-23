---
title: طريقة add_svg
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 330
url: /ar/aspose.cells.drawing/shapecollection/add_svg/
is_root: false
---
##  add_svg(self, upper_left_row, top, upper_left_column, left, height, width, svg_data, compatible_image_data) {#int-int-int-int-int-int-bytes-bytes}
إضافة صورة svg.


###  عائدات




```python

def add_svg(self, upper_left_row, top, upper_left_column, left, height, width, svg_data, compatible_image_data):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| upper_left_row | int | مؤشر الصف العلوي الأيسر.|
| top | int | يمثل الإزاحة الرأسية للشكل من الصف الأيسر، بوحدة البكسل.|
| upper_left_column | int | فهرس العمود العلوي الأيسر.|
| left | int | الإزاحة الأفقية للشكل من عموده الأيسر، بوحدة البكسل.|
| height | int | ارتفاع الشكل، بوحدة البكسل.|
| width | int | عرض الشكل، بوحدة البكسل.|
| svg_data | bytes | بيانات صورة svg.|
| compatible_image_data | bytes | تم تحويل بيانات الصورة من svg لتكون متوافقة مع Excel 2016 أو الإصدارات الأقدم.|

###  مثال

```python
from aspose import pycore
import bytearray
import int

#  add a svg
with open("image.svg", "rb") as fs:
    len = pycore.cast(int, utils.filesize(fs))
    imageData = bytearray(len)
    fs.readinto(imageData)
    picture = shapes.add_svg(4, 0, 5, 0, -1, -1, imageData, None)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`ShapeCollection`](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
