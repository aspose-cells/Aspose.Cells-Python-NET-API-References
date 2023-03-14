---
title: active_x_control fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 240
url: /sv/aspose.cells.drawing/commentshape/active_x_control/
is_root: false
---
##  active_x_control fastighet

Hämtar ActiveX-kontrollen.

###  Exempel

```python
from aspose import pycore
from aspose.cells.drawing.activexcontrols import CheckBoxActiveXControl

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
* modul [aspose.cells.drawing](../../)
* klass [ActiveXControl](/cells/python-net/sv/aspose.cells.drawing.activexcontrols/activexcontrol)
* klass [CommentShape](/cells/python-net/sv/aspose.cells.drawing/commentshape)
