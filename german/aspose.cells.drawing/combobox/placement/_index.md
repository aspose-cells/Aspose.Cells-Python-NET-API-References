---
title: placement Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 850
url: /de/aspose.cells.drawing/combobox/placement/
is_root: false
---
##  placement Eigentum

Stellt die Art und Weise dar, wie das Zeichenobjekt mit den darunterliegenden Zellen verbunden ist.
Die Eigenschaft steuert die placement eines Objekts auf einem Arbeitsblatt.

###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`ComboBox`](/cells/python-net/de/aspose.cells.drawing/combobox)
* Klasse [`PlacementType`](/cells/python-net/de/aspose.cells.drawing/placementtype)
