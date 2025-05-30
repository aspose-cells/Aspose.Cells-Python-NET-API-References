﻿---
title: width property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 360
url: /aspose.cells.charts/plotarea/width/
is_root: false
---

## width property


Gets or sets the width of plot-area bounding box in units of 1/4000 of the chart area.

### Remarks 


The plot-area bounding box includes the plot area, tick marks(tick labels), and a small border around the tick marks.
If the value is not created by MS Excel, please call Chart.Calculate() method before calling this method. 


The **X** , **Y** , **Width**  and **Height**  of **PlotArea**  represents the plot-area 
bounding box that includes the plot area, tick marks(tick labels), and a small border around the tick marks. 
If you want to get actual size of plot area, you should call **InnerXRatioToChart** , **InnerYRatioToChart** , **InnerWidthRatioToChart**  and 
**InnerHeightRatioToChart**  properties.


For excel 2007 or latter, the default value is zero. you should call get the value after calling Chart.Calculate().
### Definition:
```python
@property
def width(self):
    ...
@width.setter
def width(self, value):
    ...
```

### See Also
* module [`aspose.cells.charts`](../../)
* class [`PlotArea`](/cells/python-net/aspose.cells.charts/plotarea)
