---
title: add_icons yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 140
url: /tr/aspose.cells.drawing/shapecollection/add_icons/
is_root: false
---
##  add_icons(self, upper_left_row, top, upper_left_column, left, height, width, image_byte_data, compatible_image_data) {#int-int-int-int-int-int-bytes-bytes}
SVG görseli ekler.


###  İadeler




```python

def add_icons(self, upper_left_row, top, upper_left_column, left, height, width, image_byte_data, compatible_image_data):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| upper_left_row | int | Sol üst sıra dizini.|
| top | int | Şeklin sol satırından dikey uzaklığını piksel cinsinden temsil eder.|
| upper_left_column | int | Sol üst sütun dizini.|
| left | int | Şeklin sol sütunundan yatay uzaklığı, piksel biriminde.|
| height | int | Şeklin piksel cinsinden yüksekliği.|
| width | int | Şeklin genişliği, piksel biriminde.|
| image_byte_data | bytes | Görüntü bayt verisi.|
| compatible_image_data | bytes | Excel 2016 ve daha düşük sürümlerle uyumlu olması için svg formatındaki görüntü verileri dönüştürüldü.|

###  Örnek

```python
from aspose import pycore
import bytearray
import int

# add icon
with open("icon.svg", "rb") as fs:
    len = pycore.cast(int, utils.filesize(fs))
    imageData = bytearray(len)
    fs.readinto(imageData)
    picture = shapes.add_icons(4, 0, 5, 0, -1, -1, imageData, None)

```



###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`ShapeCollection`](/cells/python-net/tr/aspose.cells.drawing/shapecollection)
