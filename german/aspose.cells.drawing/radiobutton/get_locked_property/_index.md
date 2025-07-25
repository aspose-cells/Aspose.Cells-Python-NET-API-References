---
title: get_locked_property Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 130
url: /de/aspose.cells.drawing/radiobutton/get_locked_property/
is_root: false
---
##  get_locked_property(self, type) {#aspose.cells.drawing.ShapeLockType}
Ruft den Wert der gesperrten Eigenschaft ab.


###  Kehrt zurück

Gibt den Wert der gesperrten Eigenschaft zurück.


```python

def get_locked_property(self, type):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| type | [`ShapeLockType`](/cells/python-net/de/aspose.cells.drawing/shapelocktype) | Der Typ der Eigenschaft „Form gesperrt“.|

###  Beispiel

```python
from aspose.cells.drawing import ShapeLockType

noAdjustHandles = 0
if shape.get_locked_property(ShapeLockType.ADJUST_HANDLES):
    noAdjustHandles = 1

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`RadioButton`](/cells/python-net/de/aspose.cells.drawing/radiobutton)
