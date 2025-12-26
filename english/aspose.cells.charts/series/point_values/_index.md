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


Represents the actual values that are used to plot every point in the chart.
corresponding to [`Series.values`](/cells/python-net/aspose.cells.charts/series#values)
When Series.Values is a link, you can use this attribute to get specific data.

```python
from aspose.cells import Workbook

workbook = Workbook("YourFilePathName")
worksheet = workbook.worksheets[0]
chart = worksheet.charts[0]
chart.calculate()
#  Values could be like "[External.xlsx]Sheet1!$A$1:$A$6",
Values = chart.n_series[0].values
#  But when you can't get point values from "[External.xlsx]Sheet1!$A$1:$A$6",
#  For example, "External.xlsx" does not exist, then you can use PointValues,
#  It will return the values actually displayed in the Excel interface in the form of an array.
v1 = chart.n_series[0].point_values

```

### Remarks 


For user's convenience, this property provides the actual values corresponding
to the data defined by [`Series.values`](/cells/python-net/aspose.cells.charts/series#values).
### Definition:
```python
@property
def point_values(self):
    ...
```

### See Also
* module [`aspose.cells.charts`](../../)
* class [`Series`](/cells/python-net/aspose.cells.charts/series)
