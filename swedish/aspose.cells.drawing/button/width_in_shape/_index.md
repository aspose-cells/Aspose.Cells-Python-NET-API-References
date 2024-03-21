---
title: width_in_shape fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1180
url: /sv/aspose.cells.drawing/button/width_in_shape/
is_root: false
---
##  width_in_shape fastighet

Representerar formens bredd, i enheten 1/4000 av den överordnade formen.

###  Anmärkningar

Gäller endast när denna form i gruppen eller diagrammet.

###  Exempel

```python

if shape.is_in_group and shape.width_in_shape == 2000:
    shape.width_in_shape = 4000

```
###  Definition:
```python
@property
def width_in_shape(self):
    ...
@width_in_shape.setter
def width_in_shape(self, value):
    ...
```

###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`Button`](/cells/python-net/sv/aspose.cells.drawing/button)
