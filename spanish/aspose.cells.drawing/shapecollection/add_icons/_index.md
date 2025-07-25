---
title: método add_icons
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 140
url: /es/aspose.cells.drawing/shapecollection/add_icons/
is_root: false
---
##  add_icons(self, upper_left_row, top, upper_left_column, left, height, width, image_byte_data, compatible_image_data) {#int-int-int-int-int-int-bytes-bytes}
Agrega imagen SVG.


###  Devoluciones




```python

def add_icons(self, upper_left_row, top, upper_left_column, left, height, width, image_byte_data, compatible_image_data):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| upper_left_row | int | Índice de la fila superior izquierda.|
| top | int | Representa el desplazamiento vertical de la forma desde su fila izquierda, en unidades de píxeles.|
| upper_left_column | int | Índice de la columna superior izquierda.|
| left | int | El desplazamiento horizontal de la forma desde su columna izquierda, en unidades de píxeles.|
| height | int | La altura de la forma, en unidades de píxeles.|
| width | int | El ancho de la forma, en unidades de píxeles.|
| image_byte_data | bytes | Los datos en bytes de la imagen.|
| compatible_image_data | bytes | Se convirtieron los datos de imagen de SVG para que sean compatibles con Excel 2016 o versiones anteriores.|

###  Ejemplo

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



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ShapeCollection`](/cells/python-net/es/aspose.cells.drawing/shapecollection)
