---
title: placement fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 840
url: /sv/aspose.cells.drawing/dialogbox/placement/
is_root: false
---
##  placement fastighet

Representerar hur ritobjektet är kopplat till cellerna under det.
Egenskapen styr placement för ett objekt i ett kalkylblad.

###  Exempel

```python
from aspose.cells.drawing import PlacementType

if shape.placement == PlacementType.MOVE:
    shape.placement = PlacementType.MOVE_AND_SIZE

```
###  Definition:
```python
@property
def placement(self):
    ...
@placement.setter
def placement(self, value):
    ...
```

###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`DialogBox`](/cells/python-net/sv/aspose.cells.drawing/dialogbox)
* klass [`PlacementType`](/cells/python-net/sv/aspose.cells.drawing/placementtype)
