---
title: get_locked_property yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 140
url: /tr/aspose.cells.drawing/groupshape/get_locked_property/
is_root: false
---
##  get_locked_property(self, type) {#aspose.cells.drawing.ShapeLockType}
Kilitli mülkün değerini alır.


###  İadeler

Kilitli özelliğin değerini döndürür.


```python

def get_locked_property(self, type):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| type | [`ShapeLockType`](/cells/python-net/tr/aspose.cells.drawing/shapelocktype) | Şekil kilitli özelliğinin türü.|

###  Örnek

```python
from aspose.cells.drawing import ShapeLockType

noAdjustHandles = 0
if shape.get_locked_property(ShapeLockType.ADJUST_HANDLES):
    noAdjustHandles = 1

```



###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`GroupShape`](/cells/python-net/tr/aspose.cells.drawing/groupshape)
