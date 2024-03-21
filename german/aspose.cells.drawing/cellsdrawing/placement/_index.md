---
title: placement Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 830
url: /de/aspose.cells.drawing/cellsdrawing/placement/
is_root: false
---
##  placement Eigentum

Stellt die Art und Weise dar, wie das Zeichenobjekt an die darunter liegenden Zellen angehängt wird.
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
* Klasse [`CellsDrawing`](/cells/python-net/de/aspose.cells.drawing/cellsdrawing)
* Klasse [`PlacementType`](/cells/python-net/de/aspose.cells.drawing/placementtype)
