---
title: active_x_control недвижимость
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 240
url: /ru/aspose.cells.drawing/groupbox/active_x_control/
is_root: false
---
##  active_x_control недвижимость

Получает элемент управления ActiveX.

###  Пример

```python
from aspose import pycore
from aspose.cells.drawing.activexcontrols import CheckBoxActiveXControl

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
* модуль [aspose.cells.drawing](../../)
* класс [ActiveXControl](/cells/python-net/ru/aspose.cells.drawing.activexcontrols/activexcontrol)
* класс [GroupBox](/cells/python-net/ru/aspose.cells.drawing/groupbox)
