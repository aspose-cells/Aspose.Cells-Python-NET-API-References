﻿---
title: active_x_control property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 270
url: /aspose.cells.drawing/scrollbar/active_x_control/
is_root: false
---

## active_x_control property


Gets the ActiveX control.

### Example 


```python
from aspose import pycore
from aspose.cells.drawing.activexcontrols import CheckBoxActiveXControl

if shape.active_x_control != None:
    checkBox1 = pycore.cast(CheckBoxActiveXControl, shape.active_x_control)
    # The font name of CheckBox
    fontName = checkBox1.font.name

```
### Definition:
```python
@property
def active_x_control(self):
    ...
```

### See Also
* module [`aspose.cells.drawing`](../../)
* class [`ActiveXControl`](/cells/python-net/aspose.cells.drawing.activexcontrols/activexcontrol)
* class [`ScrollBar`](/cells/python-net/aspose.cells.drawing/scrollbar)
