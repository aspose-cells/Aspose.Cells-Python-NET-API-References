---
title: width_in_shape proprietà
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 1360
url: /it/aspose.cells.drawing/oleobject/width_in_shape/
is_root: false
---
##  width_in_shape proprietà

Rappresenta la larghezza della forma, in unità di 1/4000 della forma padre.

###  Osservazioni

Si applica solo quando questa forma è nel gruppo o nel grafico.

###  Esempio

```python

if shape.is_in_group and shape.width_in_shape == 2000:
    shape.width_in_shape = 4000

```
###  Definizione:
```python
@property
def width_in_shape(self):
    ...
@width_in_shape.setter
def width_in_shape(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`OleObject`](/cells/python-net/it/aspose.cells.drawing/oleobject)
