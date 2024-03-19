---
title: text_horizontal_overflow недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 980
url: /ru/aspose.cells.drawing/dialogbox/text_horizontal_overflow/
is_root: false
---
##  text_horizontal_overflow недвижимость

Получает и задает тип горизонтального переполнения текста для фигуры, содержащей текст.

###  Пример

```python
from aspose.cells.drawing import TextOverflowType

if shape.text_horizontal_overflow == TextOverflowType.CLIP:
    shape.text_horizontal_overflow = TextOverflowType.OVERFLOW

```
###  Определение:
```python
@property
def text_horizontal_overflow(self):
    ...
@text_horizontal_overflow.setter
def text_horizontal_overflow(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`DialogBox`](/cells/python-net/ru/aspose.cells.drawing/dialogbox)
* класс [`TextOverflowType`](/cells/python-net/ru/aspose.cells.drawing/textoverflowtype)
