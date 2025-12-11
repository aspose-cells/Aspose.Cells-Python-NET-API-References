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


Represents the actual category values that are used in the chart.
corresponding to [`Series.x_values`](/cells/python-net/aspose.cells.charts/series#x_values)
When Series.XValues is a link, you can use this attribute to get specific data.

```python
from aspose.cells import Workbook

workbook = Workbook("YourFilePathName")
worksheet = workbook.worksheets[0]
chart = worksheet.charts[0]
chart.calculate()
#  XValues could be like "[External.xlsx]Sheet1!$B$2:$C$6",
XValues = chart.n_series[0].x_values
#  But when you can't get category values from "[External.xlsx]Sheet1!$B$2:$C$6",
#  For example, "External.xlsx" does not exist, then you can use CategoryValues,
#  It will return the category values actually displayed in the Excel interface in the form of a two-dimensional array.
v1 = chart.n_series[0].category_values

```

### Remarks 


For user's convenience, this property provides the actual values corresponding
to the data defined by [`Series.x_values`](/cells/python-net/aspose.cells.charts/series#x_values).
### Definition:
```python
@property
def category_values(self):
    ...
```

### See Also
* module [`aspose.cells.charts`](../../)
* class [`Series`](/cells/python-net/aspose.cells.charts/series)
