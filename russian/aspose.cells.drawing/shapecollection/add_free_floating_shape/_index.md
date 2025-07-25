---
title: add_free_floating_shape метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 110
url: /ru/aspose.cells.drawing/shapecollection/add_free_floating_shape/
is_root: false
---
##  add_free_floating_shape(self, type, top, left, height, width, image_data, is_original_size) {#aspose.cells.drawing.MsoDrawingType-int-int-int-int-bytes-bool}
Добавляет на рабочий лист свободно перемещаемую фигуру. Применяется только к фигурам линии/изображения.


###  Возврат




```python

def add_free_floating_shape(self, type, top, left, height, width, image_data, is_original_size):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| type | [`MsoDrawingType`](/cells/python-net/ru/aspose.cells.drawing/msodrawingtype) | Тип фигуры.|
| top | int | Представляет собой вертикальное смещение фигуры от верхней строки листа в пикселях.|
| left | int | Представляет горизонтальное смещение фигуры относительно левого столбца рабочего листа в пикселях.|
| height | int | Представляет высоту LineShape в пикселях.|
| width | int |Представляет ширину LineShape в пикселях.|
| image_data | bytes | Данные изображения применимы только к картинке.|
| is_original_size | bool | Использовать ли оригинальный размер формы, если форма является изображением.|

###  Пример

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



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
