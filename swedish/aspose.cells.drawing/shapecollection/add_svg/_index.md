---
title: add_svg metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 330
url: /sv/aspose.cells.drawing/shapecollection/add_svg/
is_root: false
---
##  add_svg(self, upper_left_row, top, upper_left_column, left, height, width, svg_data, compatible_image_data) {#int-int-int-int-int-int-bytes-bytes}
Lägger till svg-bild.


###  Returnerar




```python

def add_svg(self, upper_left_row, top, upper_left_column, left, height, width, svg_data, compatible_image_data):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| upper_left_row | int | Index för övre vänstra raden.|
| top | int | Representerar formens vertikala förskjutning från dess vänstra rad, i pixelenhet.|
| upper_left_column | int | Index i övre vänstra kolumnen.|
| left | int | Formens horisontella förskjutning från dess vänstra kolumn, i pixelenhet.|
| height | int | Formens höjd, i pixelenhet.|
| width | int | Formens bredd, i pixlar.|
| svg_data | bytes | SVG-bilddata.|
| compatible_image_data | bytes | Konverterade bilddata från svg för att vara kompatibel med Excel 2016 eller lägre versioner.|

###  Exempel

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



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection)
