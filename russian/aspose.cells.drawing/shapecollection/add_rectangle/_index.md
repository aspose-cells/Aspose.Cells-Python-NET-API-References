---
title: add_rectangle метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 260
url: /ru/aspose.cells.drawing/shapecollection/add_rectangle/
is_root: false
---
##  add_rectangle(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Добавляет RectangleShape на рабочий лист.


###  Возврат

Объект RectangleShape.


```python

def add_rectangle(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| upper_left_row | int | Указатель верхнего левого ряда.|
| top | int | Представляет вертикальное смещение RectangleShape от его левой строки в пикселях.|
| upper_left_column | int | Индекс верхнего левого столбца.|
| left | int | Представляет горизонтальное смещение RectangleShape от его левого столбца в пикселях.|
| height | int | Представляет высоту RectangleShape в пикселях.|
| width | int | Представляет ширину RectangleShape в пикселях.|

###  Пример

```python

#  add a rectangle
rectangleShape = shapes.add_rectangle(2, 0, 2, 0, 130, 130)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
