---
title: top_in_shape fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1090
url: /sv/aspose.cells.drawing/oval/top_in_shape/
is_root: false
---
##  top_in_shape fastighet

 Representerar formens vertikala förskjutning från den överordnade formens övre kant,
i enheten 1/4000 av höjden på den överordnade formen.

###  Anmärkningar

Gäller endast när den här formen finns i gruppen eller diagrammet.

###  Exempel

```python

if shape.is_in_group and shape.top_in_shape == 8000:
    shape.top_in_shape = 4000

```
###  Definition:
```python
@property
def top_in_shape(self):
    ...
@top_in_shape.setter
def top_in_shape(self, value):
    ...
```

###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`Oval`](/cells/python-net/sv/aspose.cells.drawing/oval)
