---
title: major_unit_scale属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 320
url: /zh/aspose.cells.charts/axis/major_unit_scale/
is_root: false
---
## major_unit_scale属性

表示类别轴的主要单位尺度。

### 例子

```python
from aspose.cells.charts import CategoryType, TimeUnit

chart.category_axis.category_type = CategoryType.TIME_SCALE
chart.category_axis.major_unit_scale = TimeUnit.MONTHS
chart.category_axis.major_unit = 2.0

```
### 定义：
```python
@property
def major_unit_scale(self):
    ...
@major_unit_scale.setter
def major_unit_scale(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.charts`](../../)
* 类 [`Axis`](/cells/python-net/zh/aspose.cells.charts/axis)
* 类 [`TimeUnit`](/cells/python-net/zh/aspose.cells.charts/timeunit)
