---
title: top_in_shape proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1090
url: /it/aspose.cells.drawing/rectangleshape/top_in_shape/
is_root: false
---
##  top_in_shape proprietà

 Rappresenta lo scostamento verticale della forma dal bordo superiore della forma padre,
in unità di 1/4000 dell'altezza della forma madre.

###  Osservazioni

Si applica solo quando questa forma è nel gruppo o nel grafico.

###  Esempio

```python

if shape.is_in_group and shape.top_in_shape == 8000:
    shape.top_in_shape = 4000

```
###  Definizione:
```python
@property
def top_in_shape(self):
    ...
@top_in_shape.setter
def top_in_shape(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`RectangleShape`](/cells/python-net/it/aspose.cells.drawing/rectangleshape)
