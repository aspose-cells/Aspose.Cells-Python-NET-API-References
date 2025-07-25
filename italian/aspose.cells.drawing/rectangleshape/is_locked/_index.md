---
title: is_locked proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 620
url: /it/aspose.cells.drawing/rectangleshape/is_locked/
is_root: false
---
##  is_locked proprietà

 Vero significa che l'oggetto non può essere modificato quando il foglio è protetto.
Si noti che questo valore è significativo solo se il foglio di lavoro o gli oggetti nel foglio di lavoro sono protetti.

###  Esempio

```python

# Sets the specified shape to unlocked state
if shape.worksheet.is_protected and shape.is_locked:
    shape.is_locked = False
# Sets the specified shape to a locked state
if shape.worksheet.is_protected and notshape.is_locked:
    shape.is_locked = True

```
###  Definizione:
```python
@property
def is_locked(self):
    ...
@is_locked.setter
def is_locked(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`RectangleShape`](/cells/python-net/it/aspose.cells.drawing/rectangleshape)
