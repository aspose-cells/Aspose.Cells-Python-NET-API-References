﻿---
title: y_ratio_to_chart property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 360
url: /aspose.cells.charts/chartframe/y_ratio_to_chart/
is_root: false
---

## y_ratio_to_chart property


Gets or sets the y coordinate of the upper left corner in units of ratio of the chart area.

### Remarks 


This is a fraction value, its valid range is between 0-1.
How to convert units of ratio to pixels? 
YPixel = YRatioToChart * Chart.ChartObject.Height;
### Definition:
```python
@property
def y_ratio_to_chart(self):
    ...
@y_ratio_to_chart.setter
def y_ratio_to_chart(self, value):
    ...
```

### See Also
* module [`aspose.cells.charts`](../../)
* class [`ChartFrame`](/cells/python-net/aspose.cells.charts/chartframe)
