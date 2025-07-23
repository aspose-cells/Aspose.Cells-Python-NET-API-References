---
title: type属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 270
url: /zh/aspose.cells.charts/errorbar/type/
is_root: false
---
## type属性

表示误差线数量 type。

### 例子

```python
from aspose.cells import Workbook
from aspose.cells.charts import ErrorBarType

wb = Workbook("chart.xlsx")
chart = wb.worksheets[0].charts[0]
aseries = chart.n_series[0]
# Sets custom error bar type
aseries.y_error_bar.type = ErrorBarType.CUSTOM
aseries.y_error_bar.plus_value = "=Sheet1!A1"
aseries.y_error_bar.minus_value = "=Sheet1!A2"

```
### 定义：
```python
@property
def type(self):
    ...
@type.setter
def type(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.charts`](../../)
* 类 [`ErrorBar`](/cells/python-net/zh/aspose.cells.charts/errorbar)
* 类 [`ErrorBarType`](/cells/python-net/zh/aspose.cells.charts/errorbartype)
