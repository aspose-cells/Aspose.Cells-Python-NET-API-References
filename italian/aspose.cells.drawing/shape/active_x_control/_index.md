---
title: active_x_control proprietà
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 260
url: /it/aspose.cells.drawing/shape/active_x_control/
is_root: false
---
##  active_x_control proprietà

Ottiene il controllo ActiveX.

###  Esempio

```python
from aspose import pycore
from aspose.cells.drawing.activexcontrols import CheckBoxActiveXControl

if shape.active_x_control != None:
    checkBox1 = pycore.cast(CheckBoxActiveXControl, shape.active_x_control)
    # The font name of CheckBox
    fontName = checkBox1.font.name

```
###  Definizione:
```python
@property
def active_x_control(self):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ActiveXControl`](/cells/python-net/it/aspose.cells.drawing.activexcontrols/activexcontrol)
* classe [`Shape`](/cells/python-net/it/aspose.cells.drawing/shape)
