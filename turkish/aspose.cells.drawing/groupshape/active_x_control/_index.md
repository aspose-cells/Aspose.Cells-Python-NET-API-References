---
title: active_x_control mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 290
url: /tr/aspose.cells.drawing/groupshape/active_x_control/
is_root: false
---
##  active_x_control mülk

ActiveX denetimini alır.

###  Örnek

```python
from aspose import pycore
from aspose.cells.drawing.activexcontrols import CheckBoxActiveXControl

if shape.active_x_control != None:
    checkBox1 = pycore.cast(CheckBoxActiveXControl, shape.active_x_control)
    # The font name of CheckBox
    fontName = checkBox1.font.name

```
###  Tanım:
```python
@property
def active_x_control(self):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`GroupShape`](/cells/python-net/tr/aspose.cells.drawing/groupshape)
