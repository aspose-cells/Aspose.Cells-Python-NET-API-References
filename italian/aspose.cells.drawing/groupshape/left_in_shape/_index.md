---
title: left_in_shape proprietà
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 710
url: /it/aspose.cells.drawing/groupshape/left_in_shape/
is_root: false
---
##  left_in_shape proprietà

 Rappresenta l'offset orizzontale della forma dal bordo sinistro della forma genitore,
in unità di 1/4000 della larghezza della forma principale.

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
* classe [`GroupShape`](/cells/python-net/it/aspose.cells.drawing/groupshape)
