---
title: placement proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 840
url: /it/aspose.cells.drawing/groupbox/placement/
is_root: false
---
##  placement proprietà

Rappresenta il modo in cui l'oggetto del disegno è collegato alle celle sottostanti.
La proprietà controlla il valore placement di un oggetto in un foglio di lavoro.

###  Esempio

```python
from aspose.cells.drawing import PlacementType

if shape.placement == PlacementType.MOVE:
    shape.placement = PlacementType.MOVE_AND_SIZE

```
###  Definizione:
```python
@property
def placement(self):
    ...
@placement.setter
def placement(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`GroupBox`](/cells/python-net/it/aspose.cells.drawing/groupbox)
* classe [`PlacementType`](/cells/python-net/it/aspose.cells.drawing/placementtype)
