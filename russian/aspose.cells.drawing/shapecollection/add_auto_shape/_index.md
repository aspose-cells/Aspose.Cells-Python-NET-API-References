---
title: add_auto_shape метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 40
url: /ru/aspose.cells.drawing/shapecollection/add_auto_shape/
is_root: false
---
##  add_auto_shape(self, type, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.AutoShapeType-int-int-int-int-int-int}
Добавляет автофигуру на рабочий лист.


###  Возврат

Объект Shape.


```python

def add_auto_shape(self, type, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| type | [`AutoShapeType`](/cells/python-net/ru/aspose.cells.drawing/autoshapetype) | Тип автофигуры.|
| upper_left_row | int | Указатель верхнего левого ряда.|
| top | int | Представляет вертикальное смещение фигуры от ее левой строки в пикселях.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| left | int | Представляет горизонтальное смещение фигуры от ее левого столбца в пикселях.|
| height | int | Представляет высоту фигуры в пикселях.|
| width | int | Представляет ширину фигуры в пикселях.|
###  Примечания

Тип не может быть Chart/Comment/Picture/OleObject/Polygon/DialogBox
###  Пример


```python
from aspose.cells.drawing import AutoShapeType

# Adds a AutoShape to the worksheet.
autoShape = shapes.add_auto_shape(AutoShapeType.CUBE, 1, 0, 1, 0, 100, 50)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
