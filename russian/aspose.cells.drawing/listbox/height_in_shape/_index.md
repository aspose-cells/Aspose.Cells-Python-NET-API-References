---
title: height_in_shape недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 470
url: /ru/aspose.cells.drawing/listbox/height_in_shape/
is_root: false
---
##  height_in_shape недвижимость

Представляет вертикальное смещение фигуры от верхней границы родительской фигуры в единицах 1/4000 высоты родительской фигуры.

###  Примечания

Применяется только тогда, когда эта фигура находится в группе или диаграмме.

###  Пример

```python

if shape.is_in_group and shape.height_in_shape == 4000:
    shape.height_in_shape = 2000

```
###  Определение:
```python
@property
def height_in_shape(self):
    ...
@height_in_shape.setter
def height_in_shape(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ListBox`](/cells/python-net/ru/aspose.cells.drawing/listbox)
