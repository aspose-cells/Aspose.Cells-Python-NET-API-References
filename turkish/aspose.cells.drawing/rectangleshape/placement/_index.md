---
title: placement mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 830
url: /tr/aspose.cells.drawing/rectangleshape/placement/
is_root: false
---
##  placement mülk

Çizim nesnesinin altındaki hücrelere bağlanma şeklini temsil eder.
Özellik, çalışma sayfasındaki bir nesnenin placement'ini kontrol eder.

###  Örnek

```python
from aspose.cells.drawing import PlacementType

if shape.placement == PlacementType.MOVE:
    shape.placement = PlacementType.MOVE_AND_SIZE

```
###  Tanım:
```python
@property
def placement(self):
    ...
@placement.setter
def placement(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`PlacementType`](/cells/python-net/tr/aspose.cells.drawing/placementtype)
* sınıf [`RectangleShape`](/cells/python-net/tr/aspose.cells.drawing/rectangleshape)
