---
title: active_x_control недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 280
url: /ru/aspose.cells.drawing/listbox/active_x_control/
is_root: false
---
##  active_x_control недвижимость

Получает элемент управления ActiveX.

###  Пример

```python
from aspose import pycore
from aspose.cells.drawing.activexcontrols import CheckBoxActiveXControl

if shape.active_x_control != None:
    checkBox1 = pycore.cast(CheckBoxActiveXControl, shape.active_x_control)
    # The font name of CheckBox
    fontName = checkBox1.font.name

```
###  Определение:
```python
@property
def active_x_control(self):
    ...
```

###  Смотрите также
* модуль [`aspose.cells.drawing`](../../)
* класс [`ActiveXControl`](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/activexcontrol)
* класс [`ListBox`](/cells/python-net/ru/aspose.cells.drawing/listbox)
