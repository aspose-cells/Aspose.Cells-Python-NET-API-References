---
title: point_values property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 400
url: /aspose.cells.charts/series/point_values/
is_root: false
---

## point_values property


Gets the actual values that are used to plot every point
of this series in the chart.

### Remarks 


This property provides one convenient way to get the actual values corresponding
to the data defined by [`Series.values`](/cells/python-net/aspose.cells.charts/series#values),
especially when the specified data source is external link, formula, ...etc.

### Example 


```python
from aspose.cells import Workbook

workbook = Workbook("ExternalSourceChart.xlsx")
worksheet = workbook.worksheets[0]
chart = worksheet.charts[0]
chart.calculate()
Values = chart.n_series[0].values
#  Values could be like "[External.xlsx]Sheet1!$A$1:$A$6" which is complicated
#  for user to get the actual values(the values may be linked to another workbook,
#  or cached in current workbook). Here you can use PointValues property
#  to get the values actually displayed in the Excel interface
#  in the form of an array.
v1 = chart.n_series[0].point_values

```
### Definition:
```python
@property
def point_values(self):
    ...
```

### See Also
* module [`aspose.cells.charts`](../../)
* class [`Series`](/cells/python-net/aspose.cells.charts/series)
