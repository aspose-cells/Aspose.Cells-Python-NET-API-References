---
title: método add_ole_object
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 200
url: /es/aspose.cells.drawing/shapecollection/add_ole_object/
is_root: false
---
##  add_ole_object(self, upper_left_row, top, upper_left_column, left, height, width, image_data) {#int-int-int-int-int-int-bytes}
Agrega un OleObject.


###  Devoluciones




```python

def add_ole_object(self, upper_left_row, top, upper_left_column, left, height, width, image_data):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| upper_left_row | int |  |
| top | int |  |
| upper_left_column | int |  |
| left | int |  |
| height | int |  |
| width | int |  |
| image_data | bytes |  |

###  Ejemplo

```python
from aspose import pycore
import bytearray
import int

with open("image.jpg", "rb") as fs:
    len = pycore.cast(int, utils.filesize(fs))
    imageData = bytearray(len)
    fs.readinto(imageData)
    oleObject = shapes.add_ole_object(4, 0, 5, 0, 300, 500, imageData)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ShapeCollection`](/cells/python-net/es/aspose.cells.drawing/shapecollection)
