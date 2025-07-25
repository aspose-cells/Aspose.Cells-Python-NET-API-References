---
title: add_svg метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 330
url: /ru/aspose.cells.drawing/shapecollection/add_svg/
is_root: false
---
##  add_svg(self, upper_left_row, top, upper_left_column, left, height, width, svg_data, compatible_image_data) {#int-int-int-int-int-int-bytes-bytes}
Добавляет изображение SVG.


###  Возврат




```python

def add_svg(self, upper_left_row, top, upper_left_column, left, height, width, svg_data, compatible_image_data):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_row | int | Указатель верхнего левого ряда.|
| top | int | Представляет собой вертикальное смещение фигуры относительно ее левой строки в пикселях.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| left | int | Горизонтальное смещение фигуры относительно ее левого столбца, в пикселях.|
| height | int | Высота фигуры в пикселях.|
| width | int | Ширина фигуры в пикселях.|
| svg_data | bytes | Данные изображения SVG.|
| compatible_image_data | bytes | Конвертированные данные изображения из svg для совместимости с Excel 2016 или более ранними версиями.|

###  Пример

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



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
