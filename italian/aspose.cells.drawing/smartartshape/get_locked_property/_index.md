---
title: Metodo get_locked_property
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 130
url: /it/aspose.cells.drawing/smartartshape/get_locked_property/
is_root: false
---
##  get_locked_property(self, type) {#aspose.cells.drawing.ShapeLockType}
Ottiene il valore della proprietà bloccata.


###  ritorna

Restituisce il valore della proprietà bloccata.


```python

def get_locked_property(self, type):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| type | [`ShapeLockType`](/cells/python-net/it/aspose.cells.drawing/shapelocktype) | Tipo di proprietà bloccata della forma.|

###  Esempio

```python
from aspose.cells.drawing import ShapeLockType

noAdjustHandles = 0
if shape.get_locked_property(ShapeLockType.ADJUST_HANDLES):
    noAdjustHandles = 1

```



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`SmartArtShape`](/cells/python-net/it/aspose.cells.drawing/smartartshape)
