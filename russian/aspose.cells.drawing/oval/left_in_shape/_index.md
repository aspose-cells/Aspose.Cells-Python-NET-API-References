---
title: left_in_shape недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 690
url: /ru/aspose.cells.drawing/oval/left_in_shape/
is_root: false
---
##  left_in_shape недвижимость

 Представляет горизонтальное смещение фигуры от левой границы родительской фигуры.
в единице 1/4000 ширины родительской фигуры.

###  Примечания

Применяется только тогда, когда эта фигура находится в группе или диаграмме.

###  Пример

```python

if shape.is_in_group and shape.left_in_shape == 2000:
    shape.left_in_shape = 4000

```
###  Определение:
```python
@property
def left_in_shape(self):
    ...
@left_in_shape.setter
def left_in_shape(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`Oval`](/cells/python-net/ru/aspose.cells.drawing/oval)
