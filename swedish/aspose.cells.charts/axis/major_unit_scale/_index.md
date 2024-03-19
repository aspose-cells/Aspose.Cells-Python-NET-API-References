---
title: major_unit_scale fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 310
url: /sv/aspose.cells.charts/axis/major_unit_scale/
is_root: false
---
##  major_unit_scale fastighet

Representerar huvudenhetsskalan för kategoriaxeln.

###  Exempel

```python
from aspose.cells.charts import CategoryType, TimeUnit

chart.category_axis.category_type = CategoryType.TIME_SCALE
chart.category_axis.major_unit_scale = TimeUnit.MONTHS
chart.category_axis.major_unit = 2.0

```
###  Definition:
```python
@property
def major_unit_scale(self):
    ...
@major_unit_scale.setter
def major_unit_scale(self, value):
    ...
```

###  Se även
* modul [`aspose.cells.charts`](../../)
* klass [`Axis`](/cells/python-net/sv/aspose.cells.charts/axis)
* klass [`TimeUnit`](/cells/python-net/sv/aspose.cells.charts/timeunit)
