---
title: height_in_shape propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 510
url: /es/aspose.cells.drawing/arcshape/height_in_shape/
is_root: false
---
##  height_in_shape propiedad

Representa el desplazamiento vertical de la forma desde el borde superior de la forma principal, en unidades de 1/4000 de la altura de la forma principal.

###  Observaciones

Solo se aplica cuando esta forma está en el grupo o gráfico.

###  Ejemplo

```python

if shape.is_in_group and shape.height_in_shape == 4000:
    shape.height_in_shape = 2000

```
###  Definición:
```python
@property
def height_in_shape(self):
    ...
@height_in_shape.setter
def height_in_shape(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ArcShape`](/cells/python-net/es/aspose.cells.drawing/arcshape)
