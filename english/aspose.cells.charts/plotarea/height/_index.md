﻿---
title: height property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 140
url: /aspose.cells.charts/plotarea/height/
is_root: false
---

## height property


Gets or sets the height of plot-area bounding box in units of 1/4000 of the chart area.

### Remarks 


The plot-area bounding box includes the plot area, tick marks(tick labels), and a small border around the tick marks.
If the value is not created by MS Excel, please call Chart.Calculate() method before calling this method. 


The **X** , **Y** , **Width**  and **Height**  of **PlotArea**  represents the plot-area 
bounding box that includes the plot area, tick marks(tick labels), and a small border around the tick marks. 
If you want to get actual size of plot area, you should call **InnerX** , **InnerY** , **InnerWidth**  and 
**InnerHeight**  properties.


For excel 2007 or latter, the default value is zero. you should call get the value after calling Chart.Calculate().
### Definition:
```python
@property
def height(self):
    ...
@height.setter
def height(self, value):
    ...
```

### See Also
* module [`aspose.cells.charts`](../../)
* class [`PlotArea`](/cells/python-net/aspose.cells.charts/plotarea)
