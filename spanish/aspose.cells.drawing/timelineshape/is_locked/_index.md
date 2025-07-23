---
title: is_locked propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 620
url: /es/aspose.cells.drawing/timelineshape/is_locked/
is_root: false
---
##  is_locked propiedad

 Verdadero significa que el objeto no se puede modificar cuando la hoja está protegida.
Tenga en cuenta que este valor solo es significativo si la hoja de cálculo o los objetos en la hoja de cálculo están protegidos.

###  Ejemplo

```python

# Sets the specified shape to unlocked state
if shape.worksheet.is_protected and shape.is_locked:
    shape.is_locked = False
# Sets the specified shape to a locked state
if shape.worksheet.is_protected and notshape.is_locked:
    shape.is_locked = True

```
###  Definición:
```python
@property
def is_locked(self):
    ...
@is_locked.setter
def is_locked(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`TimelineShape`](/cells/python-net/es/aspose.cells.drawing/timelineshape)
