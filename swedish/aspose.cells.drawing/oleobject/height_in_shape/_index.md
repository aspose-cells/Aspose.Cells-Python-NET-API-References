---
title: height_in_shape fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 530
url: /sv/aspose.cells.drawing/oleobject/height_in_shape/
is_root: false
---
##  height_in_shape fastighet

Representerar den vertikala förskjutningen av formen från den övre kanten av den överordnade formen, i enhet av 1/4000 av höjden på den överordnade formen.

###  Anmärkningar

Gäller endast när denna form i gruppen eller diagrammet.

###  Exempel

```python

if shape.is_in_group and shape.height_in_shape == 4000:
    shape.height_in_shape = 2000

```
###  Definition:
```python
@property
def height_in_shape(self):
    ...
@height_in_shape.setter
def height_in_shape(self, value):
    ...
```

###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`OleObject`](/cells/python-net/sv/aspose.cells.drawing/oleobject)
