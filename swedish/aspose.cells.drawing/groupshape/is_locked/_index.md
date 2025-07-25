---
title: is_locked fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 640
url: /sv/aspose.cells.drawing/groupshape/is_locked/
is_root: false
---
##  is_locked fastighet

 True betyder att objektet inte kan ändras när arket är skyddat.
Observera att det här värdet endast är meningsfullt om kalkylbladet eller objekten i kalkylbladet är skyddade.

###  Exempel

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

###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`GroupShape`](/cells/python-net/sv/aspose.cells.drawing/groupshape)
