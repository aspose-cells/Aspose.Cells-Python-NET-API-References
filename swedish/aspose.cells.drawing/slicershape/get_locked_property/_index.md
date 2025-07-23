---
title: get_locked_property metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 130
url: /sv/aspose.cells.drawing/slicershape/get_locked_property/
is_root: false
---
##  get_locked_property(self, type) {#aspose.cells.drawing.ShapeLockType}
Hämtar värdet på låst egendom.


###  Returnerar

Returnerar värdet av den låsta egenskapen.


```python

def get_locked_property(self, type):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| type | [`ShapeLockType`](/cells/python-net/sv/aspose.cells.drawing/shapelocktype) | Typen av egenskapen för formlåsning.|

###  Exempel

```python
from aspose.cells.drawing import ShapeLockType

noAdjustHandles = 0
if shape.get_locked_property(ShapeLockType.ADJUST_HANDLES):
    noAdjustHandles = 1

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`SlicerShape`](/cells/python-net/sv/aspose.cells.drawing/slicershape)
