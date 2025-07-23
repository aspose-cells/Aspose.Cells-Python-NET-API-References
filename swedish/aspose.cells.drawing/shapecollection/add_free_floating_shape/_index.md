---
title: add_free_floating_shape metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 110
url: /sv/aspose.cells.drawing/shapecollection/add_free_floating_shape/
is_root: false
---
##  add_free_floating_shape(self, type, top, left, height, width, image_data, is_original_size) {#aspose.cells.drawing.MsoDrawingType-int-int-int-int-bytes-bool}
Lägger till en fritt flytande form i kalkylbladet. Gäller endast för linje-/bildformer.


###  Returnerar




```python

def add_free_floating_shape(self, type, top, left, height, width, image_data, is_original_size):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| type | [`MsoDrawingType`](/cells/python-net/sv/aspose.cells.drawing/msodrawingtype) | Formtypen.|
| top | int | Representerar formens vertikala förskjutning från kalkylbladets översta rad, i pixlar.|
| left | int | Representerar den horisontella förskjutningen av formen från kalkylbladets vänstra kolumn, i pixlar.|
| height | int | Representerar höjden på linjeformen, i pixelenhet.|
| width | int |Representerar bredden på linjeformen, i pixelenhet.|
| image_data | bytes | Bilddatan gäller endast för bilden.|
| is_original_size | bool | Om formen använder originalstorlek om formen är en bild.|

###  Exempel

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



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection)
