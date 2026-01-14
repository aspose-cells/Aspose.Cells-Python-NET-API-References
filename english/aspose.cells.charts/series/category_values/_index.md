---
title: category_values property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 110
url: /aspose.cells.charts/series/category_values/
is_root: false
---

## category_values property


Gets the actual category values that are used to plot every point
of this series in the chart.

### Remarks 


This property provides one convenient way to get the actual values corresponding
to the data defined by [`Series.x_values`](/cells/python-net/aspose.cells.charts/series#x_values),
especially when the specified data source is external link, formula, ...etc.

### Example 


```python
from aspose.cells import Workbook

# Standalone example
workbook = Workbook("ExternalSourceChart.xlsx")
worksheet = workbook.worksheets[0]
chart = worksheet.charts[0]
chart.calculate()
XValues = chart.n_series[0].x_values
#  XValues may be like "[External.xlsx]Sheet1!$B$2:$C$6" which is complicated
#  for user to get the actual values(the values may be linked to another workbook,
#  or cached in current workbook). Here you can use CategoryValues property
#  to get the category values actually displayed in the Excel interface
#  in the form of a two-dimensional array.
v1 = chart.n_series[0].category_values

```
### Definition:
```python
@property
def category_values(self):
    ...
```

### See Also
* module [`aspose.cells.charts`](../../)
* class [`Series`](/cells/python-net/aspose.cells.charts/series)
