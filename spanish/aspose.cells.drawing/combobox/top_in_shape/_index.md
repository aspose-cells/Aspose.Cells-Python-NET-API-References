---
title: top_in_shape propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 1140
url: /es/aspose.cells.drawing/combobox/top_in_shape/
is_root: false
---
##  top_in_shape propiedad

 Representa el desplazamiento vertical de la forma desde el borde superior de la forma principal.
en unidad de 1/4000 de la altura de la forma principal.

###  Observaciones

Solo se aplica cuando esta forma está en el grupo o gráfico.

###  Ejemplo

```python

if shape.is_in_group and shape.top_in_shape == 8000:
    shape.top_in_shape = 4000

```
###  Definición:
```python
@property
def top_in_shape(self):
    ...
@top_in_shape.setter
def top_in_shape(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ComboBox`](/cells/python-net/es/aspose.cells.drawing/combobox)
