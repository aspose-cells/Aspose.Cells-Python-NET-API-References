---
title: active_x_control Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 280
url: /de/aspose.cells.drawing/textbox/active_x_control/
is_root: false
---
##  active_x_control Eigentum

Ruft das ActiveX-Steuerelement ab.

###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`TextBox`](/cells/python-net/de/aspose.cells.drawing/textbox)
