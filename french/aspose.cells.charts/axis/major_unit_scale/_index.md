---
title: major_unit_scale propriété
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 320
url: /fr/aspose.cells.charts/axis/major_unit_scale/
is_root: false
---
##  major_unit_scale propriété

Représente l'échelle de l'unité principale pour l'axe des catégories.

###  Exemple

```python
from aspose.cells.charts import CategoryType, TimeUnit

chart.category_axis.category_type = CategoryType.TIME_SCALE
chart.category_axis.major_unit_scale = TimeUnit.MONTHS
chart.category_axis.major_unit = 2.0

```
###  Définition:
```python
@property
def major_unit_scale(self):
    ...
@major_unit_scale.setter
def major_unit_scale(self, value):
    ...
```

###  Voir également
* module [`aspose.cells.charts`](../../)
* classe [`Axis`](/cells/python-net/fr/aspose.cells.charts/axis)
* classe [`TimeUnit`](/cells/python-net/fr/aspose.cells.charts/timeunit)
