---
title: y_ratio_to_chart属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 500
url: /zh/aspose.cells.charts/charttextframe/y_ratio_to_chart/
is_root: false
---
## y_ratio_to_chart属性

获取或设置图表区域左上角的 y 坐标（以比例为单位）。

### 注意事项

这是一个分数值，其有效范围在0-1之间。
如何将比例单位转换为像素？
YPixel = YRatioToChart * Chart.ChartObject.Height;
### 定义：
```python
@property
def y_ratio_to_chart(self):
    ...
@y_ratio_to_chart.setter
def y_ratio_to_chart(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.charts`](../../)
* 类 [`ChartTextFrame`](/cells/python-net/zh/aspose.cells.charts/charttextframe)
