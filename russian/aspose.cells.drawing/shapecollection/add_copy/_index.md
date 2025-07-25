---
title: add_copy метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 90
url: /ru/aspose.cells.drawing/shapecollection/add_copy/
is_root: false
---
##  add_copy(self, source_shape, top_row, top, left_column, left) {#aspose.cells.drawing.Shape-int-int-int-int}
Добавляет и копирует фигуру на рабочий лист.


###  Возврат

Новый объект [`Shape`](/cells/python-net/ru/aspose.cells.drawing/shape).


```python

def add_copy(self, source_shape, top_row, top, left_column, left):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| source_shape | [`Shape`](/cells/python-net/ru/aspose.cells.drawing/shape) | Исходная форма.|
| top_row | int |Индекс верхней строки.|
| top | int | Представляет собой вертикальное смещение от верхней строки в пикселях.|
| left_column | int | Индекс левой колонки.|
| left | int | Представляет собой горизонтальное смещение от левого столбца в пикселях.|

###  Пример

```python

# add a shape
rectangle = shapes.add_rectangle(2, 0, 2, 0, 130, 130)
# Adds and copies a shape.
shapes.add_copy(rectangle, 7, 0, 7, 0)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`Shape`](/cells/python-net/ru/aspose.cells.drawing/shape)
* класс [`ShapeCollection`](/cells/python-net/ru/aspose.cells.drawing/shapecollection)
