---
title: is_chart_data_changed方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 80
url: /zh/aspose.cells.charts/chart/is_chart_data_changed/
is_root: false
---
##  is_chart_data_changed(self) {#}
检测图表的数据源是否已更改。


### 返回

如果图表发生变化则返回 true，否则返回 false


```python

def is_chart_data_changed(self):
    ...
```


### 注意事项

该方法在将图表渲染为图像格式之前检测图表数据源中的变化。
第一次调用 Chart.toImage 时，图表源数据（例如 XValuesParseData、ValuesParseData）将被记录。
在再次调用Chart.toImage方法之前，调用IsChartDataChanged方法检查Chart是否需要重新渲染。


### 也可以看看
* 模块[`aspose.cells.charts`](../../)
* 类 [`Chart`](/cells/python-net/zh/aspose.cells.charts/chart)
