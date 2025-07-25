---
title: active_x_control propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 290
url: /fr/aspose.cells.drawing/groupshape/active_x_control/
is_root: false
---
##  active_x_control propriété

Obtient le contrôle ActiveX.

###  Exemple

```python
from aspose import pycore
from aspose.cells.drawing.activexcontrols import CheckBoxActiveXControl

if shape.active_x_control != None:
    checkBox1 = pycore.cast(CheckBoxActiveXControl, shape.active_x_control)
    # The font name of CheckBox
    fontName = checkBox1.font.name

```
###  Définition:
```python
@property
def active_x_control(self):
    ...
```

###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`GroupShape`](/cells/python-net/fr/aspose.cells.drawing/groupshape)
