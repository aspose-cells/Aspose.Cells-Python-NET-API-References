---
title: método set_locked_property
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 210
url: /es/aspose.cells.drawing/arcshape/set_locked_property/
is_root: false
---
##  set_locked_property {#aspose.cells.drawing.ShapeLockType-bool}
Establezca la propiedad bloqueada.



```python
def set_locked_property(self, type, value):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| type | [`ShapeLockType`](/cells/python-net/es/aspose.cells.drawing/shapelocktype) | El tipo bloqueado.|
| value | bool | El valor de la propiedad.|

###  Ejemplo

```python
from aspose.cells.drawing import ShapeLockType

shape.set_locked_property(ShapeLockType.ADJUST_HANDLES, True)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ArcShape`](/cells/python-net/es/aspose.cells.drawing/arcshape)
