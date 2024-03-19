---
title: set_locked_property yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 210
url: /tr/aspose.cells.drawing/chartshape/set_locked_property/
is_root: false
---
##  set_locked_property {#aspose.cells.drawing.ShapeLockType-bool}
Kilitli özelliğini ayarlayın.



```python
def set_locked_property(self, type, value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| type | [`ShapeLockType`](/cells/python-net/tr/aspose.cells.drawing/shapelocktype) | Kilitli tip.|
| value | bool | Mülkün değeri.|

###  Örnek

```python
from aspose.cells.drawing import ShapeLockType

shape.set_locked_property(ShapeLockType.ADJUST_HANDLES, True)

```



###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`ChartShape`](/cells/python-net/tr/aspose.cells.drawing/chartshape)
