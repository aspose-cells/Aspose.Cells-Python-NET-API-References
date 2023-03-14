---
title: width 属性
second_title: Aspose.Cells for Python via .NET API 参考资料
description:
type: docs
weight: 260
url: /zh/aspose.cells.charts/plotarea/width/
is_root: false
---
## width 属性

获取或设置绘图区域边界框的 width，以图表区域的 1/4000 为单位。

### 评论

绘图区域边界框包括绘图区域、刻度线（刻度标签）和刻度线周围的小边框。
如果该值不是由 MS Excel 创建的，请在调用此方法之前调用 Chart.Calculate() 方法。


这**X** , **Y** , **宽度**和**高度**的**绘图区**代表地块面积
边界框，包括绘图区域、刻度线（刻度标签）和刻度线周围的小边框。
如果你想获得绘图区域的实际大小，你应该调用**内X** , **内Y** , **内宽**和
**内部高度**特性。


对于 excel 2007 或更高版本，默认值为零。您应该在调用 Chart.Calculate() 之后调用获取值。
### 定义：
```python
@property
def width(self):
    ...
@width.setter
def width(self, value):
    ...
```

### 也可以看看
* 模块 [aspose.cells.charts](../../)
* 类 [PlotArea](/cells/python-net/zh/aspose.cells.charts/plotarea)
