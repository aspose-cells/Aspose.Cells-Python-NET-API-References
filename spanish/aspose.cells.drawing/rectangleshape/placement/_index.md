---
title: placement propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 840
url: /es/aspose.cells.drawing/rectangleshape/placement/
is_root: false
---
##  placement propiedad

Representa la forma en que el objeto de dibujo se adjunta a las celdas debajo de él.
La propiedad controla el placement de un objeto en una hoja de cálculo.

###  Ejemplo

```python
from aspose.cells.drawing import PlacementType

if shape.placement == PlacementType.MOVE:
    shape.placement = PlacementType.MOVE_AND_SIZE

```
###  Definición:
```python
@property
def placement(self):
    ...
@placement.setter
def placement(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`PlacementType`](/cells/python-net/es/aspose.cells.drawing/placementtype)
* clase [`RectangleShape`](/cells/python-net/es/aspose.cells.drawing/rectangleshape)
