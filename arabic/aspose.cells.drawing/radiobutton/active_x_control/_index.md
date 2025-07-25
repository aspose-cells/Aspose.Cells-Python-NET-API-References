---
title: active_x_control عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 280
url: /ar/aspose.cells.drawing/radiobutton/active_x_control/
is_root: false
---
##  active_x_control عقار

يحصل على عنصر التحكم ActiveX.

###  مثال

```python
from aspose import pycore
from aspose.cells.drawing.activexcontrols import CheckBoxActiveXControl

if shape.active_x_control != None:
    checkBox1 = pycore.cast(CheckBoxActiveXControl, shape.active_x_control)
    # The font name of CheckBox
    fontName = checkBox1.font.name

```
###  تعريف:
```python
@property
def active_x_control(self):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`RadioButton`](/cells/python-net/ar/aspose.cells.drawing/radiobutton)
