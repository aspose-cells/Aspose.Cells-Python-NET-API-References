---
title: height_in_shape proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 460
url: /it/aspose.cells.drawing/listbox/height_in_shape/
is_root: false
---
##  height_in_shape proprietà

Rappresenta lo scostamento verticale della forma dal bordo superiore della forma padre, in unità di 1/4000 dell'altezza della forma padre.

###  Osservazioni

Si applica solo quando questa forma è nel gruppo o nel grafico.

###  Esempio

```python

if shape.is_in_group and shape.height_in_shape == 4000:
    shape.height_in_shape = 2000

```
###  Definizione:
```python
@property
def height_in_shape(self):
    ...
@height_in_shape.setter
def height_in_shape(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ListBox`](/cells/python-net/it/aspose.cells.drawing/listbox)
