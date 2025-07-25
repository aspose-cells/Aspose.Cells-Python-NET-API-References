---
title: height_in_shape fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 450
url: /sv/aspose.cells.drawing/commentshape/height_in_shape/
is_root: false
---
##  height_in_shape fastighet

Representerar formens vertikala förskjutning från den överordnade formens övre kant, i enheten 1/4000 av den överordnade formens höjd.

###  Anmärkningar

Gäller endast när den här formen finns i gruppen eller diagrammet.

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
* klass [`CommentShape`](/cells/python-net/sv/aspose.cells.drawing/commentshape)
