---
title: width_in_shape недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 1180
url: /ru/aspose.cells.drawing/button/width_in_shape/
is_root: false
---
##  width_in_shape недвижимость

Представляет ширину фигуры в единицах 1/4000 родительской фигуры.

###  Примечания

Применяется только тогда, когда эта фигура находится в группе или диаграмме.

###  Пример

```python

if shape.is_in_group and shape.width_in_shape == 2000:
    shape.width_in_shape = 4000

```
###  Определение:
```python
@property
def width_in_shape(self):
    ...
@width_in_shape.setter
def width_in_shape(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`Button`](/cells/python-net/ru/aspose.cells.drawing/button)
