---
title: left_in_shape proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 700
url: /it/aspose.cells.drawing/cellsdrawing/left_in_shape/
is_root: false
---
##  left_in_shape proprietà

 Rappresenta lo spostamento orizzontale della forma dal bordo sinistro della forma padre,
in unità di 1/4000 della larghezza della forma madre.

###  Osservazioni

Si applica solo quando questa forma è nel gruppo o nel grafico.

###  Esempio

```python

if shape.is_in_group and shape.left_in_shape == 2000:
    shape.left_in_shape = 4000

```
###  Definizione:
```python
@property
def left_in_shape(self):
    ...
@left_in_shape.setter
def left_in_shape(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`CellsDrawing`](/cells/python-net/it/aspose.cells.drawing/cellsdrawing)
