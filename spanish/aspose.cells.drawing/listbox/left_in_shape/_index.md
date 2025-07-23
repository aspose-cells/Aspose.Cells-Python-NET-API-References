---
title: left_in_shape propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 730
url: /es/aspose.cells.drawing/listbox/left_in_shape/
is_root: false
---
##  left_in_shape propiedad

 Representa el desplazamiento horizontal de la forma desde el borde izquierdo de la forma principal.
en unidad de 1/4000 del ancho de la forma principal.

###  Observaciones

Solo se aplica cuando esta forma está en el grupo o gráfico.

###  Ejemplo

```python

if shape.is_in_group and shape.left_in_shape == 2000:
    shape.left_in_shape = 4000

```
###  Definición:
```python
@property
def left_in_shape(self):
    ...
@left_in_shape.setter
def left_in_shape(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ListBox`](/cells/python-net/es/aspose.cells.drawing/listbox)
