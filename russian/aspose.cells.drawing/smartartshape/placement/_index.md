---
title: placement недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 830
url: /ru/aspose.cells.drawing/smartartshape/placement/
is_root: false
---
##  placement недвижимость

Представляет способ прикрепления объекта рисования к ячейкам под ним.
Свойство управляет номером placement объекта на листе.

###  Пример

```python
from aspose.cells.drawing import PlacementType

if shape.placement == PlacementType.MOVE:
    shape.placement = PlacementType.MOVE_AND_SIZE

```
###  Определение:
```python
@property
def placement(self):
    ...
@placement.setter
def placement(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`PlacementType`](/cells/python-net/ru/aspose.cells.drawing/placementtype)
* класс [`SmartArtShape`](/cells/python-net/ru/aspose.cells.drawing/smartartshape)
