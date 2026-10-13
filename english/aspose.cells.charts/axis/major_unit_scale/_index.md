---
title: major_unit_scale property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 320
url: /aspose.cells.charts/axis/major_unit_scale/
is_root: false
---

## major_unit_scale property


Represents the major unit scale for the category axis.

### Example 


```python
from aspose.cells.charts import CategoryType

chart.category_axis.category_type = CategoryType.TIME_SCALE
timeUnit = chart.category_axis.major_unit_scale
chart.category_axis.major_unit_scale = timeUnit
chart.category_axis.major_unit = 2.0

```
### Definition:
```python
@property
def major_unit_scale(self):
    ...
@major_unit_scale.setter
def major_unit_scale(self, value):
    ...
```

### See Also
* module [`aspose.cells.charts`](../../)
* class [`Axis`](/cells/python-net/aspose.cells.charts/axis)
* class [`TimeUnit`](/cells/python-net/aspose.cells.charts/timeunit)
