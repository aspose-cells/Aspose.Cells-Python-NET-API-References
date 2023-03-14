---
title: add_ole_object метод
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 180
url: /ru/aspose.cells.drawing/shapecollection/add_ole_object/
is_root: false
---
##  add_ole_object(upper_left_row, top, upper_left_column, left, height, width, image_data) {#int-int-int-int-int-int-bytes}
Добавляет OleObject.


###  Возвращает




```python
def add_ole_object(self, upper_left_row, top, upper_left_column, left, height, width, image_data):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_row | int |  |
| top | int |  |
| upper_left_column | int |  |
| left | int |  |
| height | int |  |
| width | int |  |
| image_data | bytes |  |

###  Пример

```python
from aspose import pycore

with open("image.jpg", "rb") as fs:
    len = pycore.cast(int, utils.filesize(fs))
    imageData = bytearray(len)
    fs.readinto(imageData)
    oleObject = shapes.add_ole_object(4, 0, 5, 0, 300, 500, imageData)

```



###  Смотрите также
* модуль [aspose.cells.drawing](../../)
* класс [ShapeCollection](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
