---
title: add_icons метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 130
url: /ru/aspose.cells.drawing/shapecollection/add_icons/
is_root: false
---
##  add_icons {#int-int-int-int-int-int-bytes-bytes}
Добавляет изображение в формате SVG.


###  Возврат




```python
def add_icons(self, upper_left_row, top, upper_left_column, left, height, width, image_byte_data, compatible_image_data):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_row | int | Индекс верхней левой строки.|
| top | int | Представляет вертикальное смещение фигуры от ее левого ряда в пикселях.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| left | int | Горизонтальное смещение фигуры от ее левого столбца в пикселях.|
| height | int | Высота фигуры в пикселях.|
| width | int | Ширина фигуры в пикселях.|
| image_byte_data | bytes | Байтовые данные изображения.|
| compatible_image_data | bytes | Данные изображения преобразованы из svg для совместимости с Excel 2016 или более ранними версиями.|

###  Пример

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



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
