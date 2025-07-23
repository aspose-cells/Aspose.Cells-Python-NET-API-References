---
title: left_in_shape fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 700
url: /sv/aspose.cells.drawing/customxmlshape/left_in_shape/
is_root: false
---
##  left_in_shape fastighet

 Representerar den horisontella förskjutningen av formen från den vänstra kanten av den överordnade formen,
i enheten 1/4000 av den överordnade formens bredd.

###  Anmärkningar

Gäller endast när den här formen finns i gruppen eller diagrammet.

###  Exempel

```python

if shape.is_in_group and shape.left_in_shape == 2000:
    shape.left_in_shape = 4000

```
###  Definition:
```python
@property
def left_in_shape(self):
    ...
@left_in_shape.setter
def left_in_shape(self, value):
    ...
```

###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`CustomXmlShape`](/cells/python-net/sv/aspose.cells.drawing/customxmlshape)
