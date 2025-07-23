---
title: add_free_floating_shape yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 110
url: /tr/aspose.cells.drawing/shapecollection/add_free_floating_shape/
is_root: false
---
##  add_free_floating_shape(self, type, top, left, height, width, image_data, is_original_size) {#aspose.cells.drawing.MsoDrawingType-int-int-int-int-bytes-bool}
Çalışma sayfasına serbest yüzen bir şekil ekler. Sadece çizgi/görüntü şekli için geçerlidir.


###  İadeler




```python

def add_free_floating_shape(self, type, top, left, height, width, image_data, is_original_size):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| type | [`MsoDrawingType`](/cells/python-net/tr/aspose.cells.drawing/msodrawingtype) | Şekil türü.|
| top | int | Şeklin çalışma sayfasının en üst satırından dikey uzaklığını piksel cinsinden temsil eder.|
| left | int | Şeklin çalışma sayfasının sol sütunundan yatay uzaklığını piksel cinsinden temsil eder.|
| height | int | LineShape'in yüksekliğini piksel cinsinden temsil eder.|
| width | int |LineShape'in genişliğini piksel cinsinden temsil eder.|
| image_data | bytes | Resim verileri yalnızca resim için geçerlidir.|
| is_original_size | bool | Şekil resim ise şeklin orijinal boyutunu kullanıp kullanmayacağı.|

###  Örnek

```python
from aspose import pycore
from aspose.cells.drawing import MsoDrawingType
import bytearray
import int

# add a line
floatingShape_Line = shapes.add_free_floating_shape(MsoDrawingType.LINE, 100, 100, 100, 50, None, False)
# add a picture
imageData = None
with open("image.jpg", "rb") as fs:
    len = pycore.cast(int, utils.filesize(fs))
    imageData = bytearray(len)
    fs.readinto(imageData)
floatingShape_Picture = shapes.add_free_floating_shape(MsoDrawingType.PICTURE, 200, 100, 100, 50, imageData, False)

```



###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`ShapeCollection`](/cells/python-net/tr/aspose.cells.drawing/shapecollection)
