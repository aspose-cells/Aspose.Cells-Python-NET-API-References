---
title: x_ratio_to_chart property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 470
url: /aspose.cells.charts/charttextframe/x_ratio_to_chart/
is_root: false
---

## x_ratio_to_chart property


Gets or sets the x coordinate of the upper left corner in units of ratio of the chart area.

### Remarks 


This is a fraction value, its valid range is between 0-1.
How to convert units of ratio to pixels? 
XPixel = XRatioToChart * Chart.ChartObject.Width;
### Definition:
```python
@property
def x_ratio_to_chart(self):
    ...
@x_ratio_to_chart.setter
def x_ratio_to_chart(self, value):
    ...
```

### See Also
* module [`aspose.cells.charts`](../../)
* class [`ChartTextFrame`](/cells/python-net/aspose.cells.charts/charttextframe)
