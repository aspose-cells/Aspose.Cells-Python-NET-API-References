---
title: set_locked_property метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 220
url: /ru/aspose.cells.drawing/groupshape/set_locked_property/
is_root: false
---
##  set_locked_property {#aspose.cells.drawing.ShapeLockType-bool}
Установите заблокированное свойство.



```python
def set_locked_property(self, type, value):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| type | [`ShapeLockType`](/cells/python-net/ru/aspose.cells.drawing/shapelocktype) | Закрытый тип.|
| value | bool | Стоимость недвижимости.|

###  Пример

```python
from aspose.cells.drawing import ShapeLockType

shape.set_locked_property(ShapeLockType.ADJUST_HANDLES, True)

```



###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`GroupShape`](/cells/python-net/ru/aspose.cells.drawing/groupshape)
