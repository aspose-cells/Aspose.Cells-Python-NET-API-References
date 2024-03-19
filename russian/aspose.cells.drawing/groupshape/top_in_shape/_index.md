---
title: top_in_shape недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 1100
url: /ru/aspose.cells.drawing/groupshape/top_in_shape/
is_root: false
---
##  top_in_shape недвижимость

 Представляет вертикальное смещение фигуры от верхней границы родительской фигуры.
в единице 1/4000 высоты родительской фигуры.

###  Примечания

Применяется только тогда, когда эта фигура находится в группе или диаграмме.

###  Пример

```python

if shape.is_in_group and shape.top_in_shape == 8000:
    shape.top_in_shape = 4000

```
###  Определение:
```python
@property
def top_in_shape(self):
    ...
@top_in_shape.setter
def top_in_shape(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`GroupShape`](/cells/python-net/ru/aspose.cells.drawing/groupshape)
