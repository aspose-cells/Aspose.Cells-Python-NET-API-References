---
title: inner_x属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 250
url: /zh/aspose.cells.charts/plotarea/inner_x/
is_root: false
---
## inner_x属性

获取或获取图表区域上角的 x 坐标，以 1/4000 为单位。

### 注意事项

绘图区域边界框包括绘图区域、刻度线（刻度标签）和刻度线周围的小边框。
如果该值不是由 MS Excel 创建，请在调用此方法之前调用 Chart.Calculate() 方法。


这**X**, **Y** , **宽度**和**高度**的**绘图区**表示绘图区域
边界框，包括绘图区域、刻度线（刻度标签）和刻度线周围的小边框。
如果你想获得绘图区域的实际大小，你应该调用**InnerXRatioToChart** , **InnerYRatioToChart** , **内部宽度与图表的比率**和
**内部高度与图表之比**属性。


对于 excel 2007 或更高版本，默认值为零。您应该在调用 Chart.Calculate() 后调用获取该值。
### 定义：
```python
@property
def inner_x(self):
    ...
@inner_x.setter
def inner_x(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.charts`](../../)
* 类 [`PlotArea`](/cells/python-net/zh/aspose.cells.charts/plotarea)
