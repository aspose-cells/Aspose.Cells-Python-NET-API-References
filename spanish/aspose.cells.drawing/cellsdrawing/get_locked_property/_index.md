---
title: método get_locked_property
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 130
url: /es/aspose.cells.drawing/cellsdrawing/get_locked_property/
is_root: false
---
##  get_locked_property(self, type) {#aspose.cells.drawing.ShapeLockType}
Obtiene el valor de la propiedad bloqueada.


###  Devoluciones

Devuelve el valor de la propiedad bloqueada.


```python

def get_locked_property(self, type):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| type | [`ShapeLockType`](/cells/python-net/es/aspose.cells.drawing/shapelocktype) | El tipo de propiedad bloqueada de forma.|

###  Ejemplo

```python
from aspose.cells.drawing import ShapeLockType

noAdjustHandles = 0
if shape.get_locked_property(ShapeLockType.ADJUST_HANDLES):
    noAdjustHandles = 1

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`CellsDrawing`](/cells/python-net/es/aspose.cells.drawing/cellsdrawing)
