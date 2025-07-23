---
title: get_locked_property метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 130
url: /ru/aspose.cells.drawing/oval/get_locked_property/
is_root: false
---
##  get_locked_property(self, type) {#aspose.cells.drawing.ShapeLockType}
Получает значение заблокированного свойства.


###  Возврат

Возвращает значение заблокированного свойства.


```python

def get_locked_property(self, type):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| type | [`ShapeLockType`](/cells/python-net/ru/aspose.cells.drawing/shapelocktype) | Тип заблокированного свойства формы.|

###  Пример

```python
from aspose.cells.drawing import ShapeLockType

noAdjustHandles = 0
if shape.get_locked_property(ShapeLockType.ADJUST_HANDLES):
    noAdjustHandles = 1

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`Oval`](/cells/python-net/ru/aspose.cells.drawing/oval)
