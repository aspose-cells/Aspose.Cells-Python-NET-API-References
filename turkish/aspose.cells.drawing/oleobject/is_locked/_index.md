---
title: is_locked mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 750
url: /tr/aspose.cells.drawing/oleobject/is_locked/
is_root: false
---
##  is_locked mülk

 True, sayfa korunduğunda nesnenin değiştirilemeyeceği anlamına gelir.
Bu değerin yalnızca çalışma sayfası veya çalışma sayfasındaki nesneler korunuyorsa anlamlı olduğunu unutmayın.

###  Örnek

```python

# Sets the specified shape to unlocked state
if shape.worksheet.is_protected and shape.is_locked:
    shape.is_locked = False
# Sets the specified shape to a locked state
if shape.worksheet.is_protected and notshape.is_locked:
    shape.is_locked = True

```
###  Tanım:
```python
@property
def is_locked(self):
    ...
@is_locked.setter
def is_locked(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`OleObject`](/cells/python-net/tr/aspose.cells.drawing/oleobject)
