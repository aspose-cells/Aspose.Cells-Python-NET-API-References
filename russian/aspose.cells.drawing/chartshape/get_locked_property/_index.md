---
title: get_locked_property метод
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 110
url: /ru/aspose.cells.drawing/chartshape/get_locked_property/
is_root: false
---
##  get_locked_property(type) {#ShapeLockType}
Получает значение заблокированного свойства.


###  Возвращает

Возвращает значение заблокированного свойства.


```python
def get_locked_property(self, type):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| type | [ShapeLockType](/cells/python-net/ru/aspose.cells.drawing/shapelocktype) | Тип заблокированного свойства фигуры.|

###  Пример

```python
from aspose.cells.drawing import ShapeLockType

noAdjustHandles = 0
if shape.get_locked_property(ShapeLockType.ADJUST_HANDLES):
    noAdjustHandles = 1

```



###  Смотрите также
* модуль [aspose.cells.drawing](../../)
* класс [ChartShape](/cells/python-net/ru/aspose.cells.drawing/chartshape)
