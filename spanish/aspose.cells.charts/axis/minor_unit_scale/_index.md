---
title: minor_unit_scale propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 380
url: /es/aspose.cells.charts/axis/minor_unit_scale/
is_root: false
---
##  minor_unit_scale propiedad

Representa la escala de unidad principal para el eje de categorías.

###  Ejemplo

```python
from aspose.cells.charts import CategoryType, TimeUnit

chart.category_axis.category_type = CategoryType.TIME_SCALE
chart.category_axis.minor_unit_scale = TimeUnit.MONTHS
chart.category_axis.minor_unit = 2.0

```
###  Definición:
```python
@property
def minor_unit_scale(self):
    ...
@minor_unit_scale.setter
def minor_unit_scale(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells.charts`](../../)
* clase [`Axis`](/cells/python-net/es/aspose.cells.charts/axis)
* clase [`TimeUnit`](/cells/python-net/es/aspose.cells.charts/timeunit)
