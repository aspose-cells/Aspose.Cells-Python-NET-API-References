---
title: metodo add_ole_object
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 180
url: /it/aspose.cells.drawing/shapecollection/add_ole_object/
is_root: false
---
##  add_ole_object(upper_left_row, top, upper_left_column, left, height, width, image_data) {#int-int-int-int-int-int-bytes}
Aggiunge un OleObject.


###  ritorna




```python
def add_ole_object(self, upper_left_row, top, upper_left_column, left, height, width, image_data):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| upper_left_row | int |  |
| top | int |  |
| upper_left_column | int |  |
| left | int |  |
| height | int |  |
| width | int |  |
| image_data | bytes |  |

###  Esempio

```python
from aspose import pycore

with open("image.jpg", "rb") as fs:
    len = pycore.cast(int, utils.filesize(fs))
    imageData = bytearray(len)
    fs.readinto(imageData)
    oleObject = shapes.add_ole_object(4, 0, 5, 0, 300, 500, imageData)

```



###  Guarda anche
* modulo [aspose.cells.drawing](../../)
* classe [ShapeCollection](/cells/python-net/it/aspose.cells.drawing/shapecollection)
