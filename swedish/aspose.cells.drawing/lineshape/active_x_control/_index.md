---
title: active_x_control fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 270
url: /sv/aspose.cells.drawing/lineshape/active_x_control/
is_root: false
---
##  active_x_control fastighet

Hämtar ActiveX-kontrollen.

###  Exempel

```python
from aspose import pycore
from aspose.cells.drawing.activexcontrols import CheckBoxActiveXControl

if shape.active_x_control != None:
    checkBox1 = pycore.cast(CheckBoxActiveXControl, shape.active_x_control)
    # The font name of CheckBox
    fontName = checkBox1.font.name

```
###  Definition:
```python
@property
def active_x_control(self):
    ...
```

###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`LineShape`](/cells/python-net/sv/aspose.cells.drawing/lineshape)
