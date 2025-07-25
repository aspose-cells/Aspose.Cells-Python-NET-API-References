---
title: major_unit_scale proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 320
url: /it/aspose.cells.charts/axis/major_unit_scale/
is_root: false
---
##  major_unit_scale proprietà

Rappresenta la scala dell'unità principale per l'asse delle categorie.

###  Esempio

```python
from aspose.cells.charts import CategoryType, TimeUnit

chart.category_axis.category_type = CategoryType.TIME_SCALE
chart.category_axis.major_unit_scale = TimeUnit.MONTHS
chart.category_axis.major_unit = 2.0

```
###  Definizione:
```python
@property
def major_unit_scale(self):
    ...
@major_unit_scale.setter
def major_unit_scale(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.charts`](../../)
* classe [`Axis`](/cells/python-net/it/aspose.cells.charts/axis)
* classe [`TimeUnit`](/cells/python-net/it/aspose.cells.charts/timeunit)
