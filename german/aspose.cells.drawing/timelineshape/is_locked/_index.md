---
title: is_locked Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 620
url: /de/aspose.cells.drawing/timelineshape/is_locked/
is_root: false
---
##  is_locked Eigentum

 „True“ bedeutet, dass das Objekt nicht geändert werden kann, wenn das Blatt geschützt ist.
Beachten Sie, dass dieser Wert nur dann sinnvoll ist, wenn das Arbeitsblatt oder die Objekte im Arbeitsblatt geschützt sind.

###  Beispiel

```python

# Sets the specified shape to unlocked state
if shape.worksheet.is_protected and shape.is_locked:
    shape.is_locked = False
# Sets the specified shape to a locked state
if shape.worksheet.is_protected and notshape.is_locked:
    shape.is_locked = True

```
###  Definition:
```python
@property
def is_locked(self):
    ...
@is_locked.setter
def is_locked(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`TimelineShape`](/cells/python-net/de/aspose.cells.drawing/timelineshape)
