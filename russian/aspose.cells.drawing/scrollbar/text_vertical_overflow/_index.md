---
title: text_vertical_overflow недвижимость
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 1090
url: /ru/aspose.cells.drawing/scrollbar/text_vertical_overflow/
is_root: false
---
##  text_vertical_overflow недвижимость

Получает и задает тип вертикального переполнения текста для фигуры, содержащей текст.

###  Пример

```python
from aspose.cells.drawing import TextOverflowType

if shape.text_vertical_overflow == TextOverflowType.CLIP:
    shape.text_vertical_overflow = TextOverflowType.OVERFLOW

```
###  Определение:
```python
@property
def text_vertical_overflow(self):
    ...
@text_vertical_overflow.setter
def text_vertical_overflow(self, value):
    ...
```

###  Смотрите также
* модуль [aspose.cells.drawing](../../)
* класс [ScrollBar](/cells/python-net/ru/aspose.cells.drawing/scrollbar)
* класс [TextOverflowType](/cells/python-net/ru/aspose.cells.drawing/textoverflowtype)
