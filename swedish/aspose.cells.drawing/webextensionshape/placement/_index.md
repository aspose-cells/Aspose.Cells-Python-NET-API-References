---
title: placement fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 820
url: /sv/aspose.cells.drawing/webextensionshape/placement/
is_root: false
---
##  placement fastighet

Representerar hur ritobjektet är fäst vid cellerna under det.
Egenskapen styr placement för ett objekt på ett kalkylblad.

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
* modul [aspose.cells.drawing](../../)
* klass [PlacementType](/cells/python-net/sv/aspose.cells.drawing/placementtype)
* klass [WebExtensionShape](/cells/python-net/sv/aspose.cells.drawing/webextensionshape)
