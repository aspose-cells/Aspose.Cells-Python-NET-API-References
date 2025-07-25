---
title: add_freeform метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 120
url: /ru/aspose.cells.drawing/shapecollection/add_freeform/
is_root: false
---
##  add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths) {#int-int-int-int-int-int-list}
Добавляет на рабочий лист фигуру произвольной формы.


###  Возврат

Свободная форма.


```python

def add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_row | int | Указатель верхнего левого ряда.|
| top | int | Представляет собой вертикальное смещение произвольной фигуры от ее левой строки в пикселях.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| left | int | Представляет горизонтальное смещение произвольной фигуры от ее левого столбца в пикселях.|
| height | int | Представляет высоту произвольной фигуры в пикселях.|
| width | int | Представляет ширину произвольной фигуры в пикселях.|
| paths | list | Представляет собой определенный пользователем путь|
###  Примечания

Обратите внимание: ширина и высота в параметрах могут быть любыми положительными целыми числами, а не общей шириной и высотой массива ShapePath, заданного параметром «paths». Связь между ними — это отношение масштабирования и заполнения, то есть каждый объект ShapePath будет масштабироваться в соответствии с шириной и высотой. Поэтому, если в «paths» несколько объектов, каждый объект ShapePath должен быть спроектирован разумно, чтобы соответствовать ожиданиям. Если имеется только один объект ShapePath и нет других требований, передача ширины и высоты объекта в качестве значений параметров является хорошим решением.
###  Пример


```python
from aspose.cells.drawing import ShapePath

# Custom figure
shapePath = ShapePath()
shapePath.move_to(60, 45)
shapePath.arc_to(25, 25, 0, 270)
shapePath.close()
shapePath.move_to(60, 20)
shapePath.line_to(110, 70)
shapePath.line_to(125, 155.5)
shapePath.arc_to(35.5, 35.5, 0, 270)
shapePath.close()
shapePath.move_to(150, 45)
shapePath.arc_to(25, 25, 0, 270)
shapePathW = shapePath.width_pixel
shapePathH = shapePath.height_pixel
shapePath1 = ShapePath()
shapePath1.move_to(0, 0)
shapePath1.cubic_bezier_to(48.24997, 0.6844,                                 96.5, -7.148871,                                 130, 11.517795)
shapePath1.cubic_bezier_to(163.5, 30.18446,                                 182.24997, 75.351,                                 201, 120.517795)
shapePath1.move_to(150, 80)
shapePath1.arc_to(25, 25, 0, 270)
if shapePath1.width_pixel > shapePathW:
    shapePathW = shapePath1.width_pixel
if shapePath1.height_pixel > shapePathH:
    shapePathH = shapePath1.height_pixel
# Notice: shapePathH and shapePathH can be any positive integer values, here we just simply set them.
# Insert custom figure into worksheet
shapes.add_freeform(1, 0, 1, 0, shapePathH, shapePathW, [shapePath, shapePath1])

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
