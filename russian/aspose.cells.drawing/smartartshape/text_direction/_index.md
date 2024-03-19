---
title: text_direction недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 940
url: /ru/aspose.cells.drawing/smartartshape/text_direction/
is_root: false
---
##  text_direction недвижимость

Получает/задает направление потока текста для этого объекта.

###  Пример

```python
from aspose.cells import TextDirectionType

if shape.text_direction == TextDirectionType.CONTEXT:
    shape.text_direction = TextDirectionType.LEFT_TO_RIGHT

```
###  Определение:
```python
@property
def text_direction(self):
    ...
@text_direction.setter
def text_direction(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`SmartArtShape`](/cells/python-net/ru/aspose.cells.drawing/smartartshape)
* класс [`TextDirectionType`](/cells/python-net/ru/aspose.cells/textdirectiontype)
