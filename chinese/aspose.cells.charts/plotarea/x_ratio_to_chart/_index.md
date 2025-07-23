---
title: x_ratio_to_chart属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 410
url: /zh/aspose.cells.charts/plotarea/x_ratio_to_chart/
is_root: false
---
## x_ratio_to_chart属性

获取或获取绘图区域边界框左上角的 x 坐标（以图表区域的比例为单位）。

### 注意事项

绘图区域边界框包括绘图区域、刻度线（刻度标签）和刻度线周围的小边框。
如果该值不是由 MS Excel 创建，请在调用此方法之前调用 Chart.Calculate() 方法。


这**XRatioToChart** , **YRatioToChart** , **宽度与图表之比**和**高度与图表之比**的**绘图区**表示绘图区域
边界框，包括绘图区域、刻度线（刻度标签）和刻度线周围的小边框。
如果你想获得绘图区域的实际大小，你应该调用**InnerXRatioToChart** , **InnerYRatioToChart** , **内部宽度与图表的比率**和
**内部高度与图表之比**属性。


对于 excel 2007 或更高版本，默认值为零。您应该在调用 Chart.Calculate() 后调用获取该值。

 
XPixel = XRatioToChart * 图表.ChartObject.Width。
### 定义：
```python
@property
def x_ratio_to_chart(self):
    ...
@x_ratio_to_chart.setter
def x_ratio_to_chart(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.charts`](../../)
* 类 [`PlotArea`](/cells/python-net/zh/aspose.cells.charts/plotarea)
