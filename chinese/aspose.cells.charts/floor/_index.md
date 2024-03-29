---
title: Floor类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 170
url: /zh/aspose.cells.charts/floor/
is_root: false
---
## Floor类
封装代表 3D 图表底部的对象。



**遗产：** [`Floor`](/cells/python-net/aspose.cells.charts/floor) → 
[`Area`](/cells/python-net/zh/aspose.cells.drawing/area)



Floor 类型公开以下成员：

### 特性
|属性|描述|
| :- | :- |
| [background_color](/cells/python-net/zh/aspose.cells.charts/floor/background_color) |获取或设置[`Area`](/cells/python-net/zh/aspose.cells.drawing/area)的背景颜色。|
| [foreground_color](/cells/python-net/zh/aspose.cells.charts/floor/foreground_color) |获取或设置前景色。|
| [formatting](/cells/python-net/zh/aspose.cells.charts/floor/formatting) |代表区域的格式。|
| [invert_if_negative](/cells/python-net/zh/aspose.cells.charts/floor/invert_if_negative) |如果该属性为 true 并且图表点的值为负数，<br/>前景色和背景色将被交换。|
| [fill_format](/cells/python-net/zh/aspose.cells.charts/floor/fill_format) |表示一个 [`Area.fill_format`](/cells/python-net/zh/aspose.cells.drawing/area#fill_format) 对象，其中包含指定图表或形状的填充格式属性。|
| [transparency](/cells/python-net/zh/aspose.cells.charts/floor/transparency) |返回或设置区域的透明度，其值范围为 0.0（不透明）到 1.0（透明）。|
| [border](/cells/python-net/zh/aspose.cells.charts/floor/border) |获取或设置边框 [`Line`](/cells/python-net/zh/aspose.cells.drawing/line)。|



### 例子

```python
from aspose.cells import License, Workbook
from aspose.cells.charts import ChartType
from aspose.cells.drawing import GradientPresetType, GradientStyleType
from aspose.pydrawing import Color

# Instantiate the License class
license = License()
# Pass only the name of the license file embedded in the assembly
license.set_license("Aspose.Cells.lic")
# Instantiate the workbook object
workbook = Workbook()
# Get cells collection
cells = workbook.worksheets[0].cells
# Put values in cells
cells.get("A1").put_value(1)
cells.get("A2").put_value(2)
cells.get("A3").put_value(3)
# get charts colletion
charts = workbook.worksheets[0].charts
# add a new chart
index = charts.add(ChartType.COLUMN_3D_STACKED, 5, 0, 15, 5)
# get the newly added chart
chart = charts[index]
# set charts nseries
chart.n_series.add("A1:A3", True)
# Show data labels
chart.n_series[0].data_labels.show_value = True
# Get chart's floor
floor = chart.floor
# set floor's border as red
floor.border.color = Color.red
# set fill format
floor.fill_format.set_preset_color_gradient(GradientPresetType.CALM_WATER, GradientStyleType.DIAGONAL_DOWN, 2)
# save the file
workbook.save(r"dest.xls")

```

### 也可以看看
* 模块[`aspose.cells.charts`](..)
* 类 [`Area`](/cells/python-net/zh/aspose.cells.drawing/area)
* 类 [`Floor`](/cells/python-net/zh/aspose.cells.charts/floor)
* 类 [`Line`](/cells/python-net/zh/aspose.cells.drawing/line)
