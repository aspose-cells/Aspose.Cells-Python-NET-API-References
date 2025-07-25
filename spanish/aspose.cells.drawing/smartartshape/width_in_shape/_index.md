---
title: width_in_shape propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1190
url: /es/aspose.cells.drawing/smartartshape/width_in_shape/
is_root: false
---
##  width_in_shape propiedad

Representa el ancho de la forma, en unidades de 1/4000 de la forma principal.

###  Observaciones

Solo se aplica cuando esta forma está en el grupo o gráfico.

###  Ejemplo

```python

if shape.is_in_group and shape.width_in_shape == 2000:
    shape.width_in_shape = 4000

```
###  Definición:
```python
@property
def width_in_shape(self):
    ...
@width_in_shape.setter
def width_in_shape(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`SmartArtShape`](/cells/python-net/es/aspose.cells.drawing/smartartshape)
