---
title: placement mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1000
url: /tr/aspose.cells.drawing/oleobject/placement/
is_root: false
---
##  placement mülk

Çizim nesnesinin altındaki hücrelere bağlanma şeklini gösterir.
Özellik, bir çalışma sayfasındaki nesnenin placement değerini kontrol eder.

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
* sınıf [`OleObject`](/cells/python-net/tr/aspose.cells.drawing/oleobject)
* sınıf [`PlacementType`](/cells/python-net/tr/aspose.cells.drawing/placementtype)
