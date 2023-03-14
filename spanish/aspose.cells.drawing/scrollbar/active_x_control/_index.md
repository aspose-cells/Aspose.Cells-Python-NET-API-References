---
title: active_x_control propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 240
url: /es/aspose.cells.drawing/scrollbar/active_x_control/
is_root: false
---
##  active_x_control propiedad

Obtiene el control ActiveX.

###  Ejemplo

```python
from aspose import pycore
from aspose.cells.drawing.activexcontrols import CheckBoxActiveXControl

checkBox1 = pycore.cast(CheckBoxActiveXControl, shape.active_x_control)
# The font name of CheckBox
fontName = checkBox1.font.name

```
###  Definición:
```python
@property
def active_x_control(self):
    ...
```

###  Ver también
* módulo [aspose.cells.drawing](../../)
* clase [ActiveXControl](/cells/python-net/es/aspose.cells.drawing.activexcontrols/activexcontrol)
* clase [ScrollBar](/cells/python-net/es/aspose.cells.drawing/scrollbar)
