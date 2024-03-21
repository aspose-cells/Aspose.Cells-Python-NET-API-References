---
title: add_icons yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 130
url: /tr/aspose.cells.drawing/shapecollection/add_icons/
is_root: false
---
##  add_icons {#int-int-int-int-int-int-bytes-bytes}
Svg resmi ekler.


###  İadeler




```python
def add_icons(self, upper_left_row, top, upper_left_column, left, height, width, image_byte_data, compatible_image_data):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| upper_left_row | int | Sol üst satır dizini.|
| top | int | Piksel birimi cinsinden şeklin sol satırından dikey uzaklığını temsil eder.|
| upper_left_column | int | Sol üst sütun dizini.|
| left | int | Piksel birimi cinsinden şeklin sol sütunundan yatay uzaklığı.|
| height | int | Piksel birimi cinsinden şeklin yüksekliği.|
| width | int | Piksel birimi cinsinden şeklin genişliği.|
| image_byte_data | bytes | Görüntü bayt verileri.|
| compatible_image_data | bytes | Excel 2016 veya daha düşük sürümlerle uyumlu olması için svg'den görüntü verileri dönüştürüldü.|

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
