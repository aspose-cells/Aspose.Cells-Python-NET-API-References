---
title: Line类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 270
url: /zh/aspose.cells.drawing/line/
is_root: false
---
## Line类
封装表示行格式的对象。



Line 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [compound_type](/cells/python-net/zh/aspose.cells.drawing/line/compound_type) |指定复合线类型|
| [dash_type](/cells/python-net/zh/aspose.cells.drawing/line/dash_type) |规定虚线类型|
| [cap_type](/cells/python-net/zh/aspose.cells.drawing/line/cap_type) |指定结束大写。|
| [join_type](/cells/python-net/zh/aspose.cells.drawing/line/join_type) |指定连接端。|
| [begin_type](/cells/python-net/zh/aspose.cells.drawing/line/begin_type) |指定线的开头的箭头。|
| [end_type](/cells/python-net/zh/aspose.cells.drawing/line/end_type) |指定线末端的箭头。|
| [begin_arrow_length](/cells/python-net/zh/aspose.cells.drawing/line/begin_arrow_length) |指定线起点箭头的长度。|
| [end_arrow_length](/cells/python-net/zh/aspose.cells.drawing/line/end_arrow_length) |指定线末端箭头的长度。|
| [begin_arrow_width](/cells/python-net/zh/aspose.cells.drawing/line/begin_arrow_width) |指定线起点箭头的宽度。|
| [end_arrow_width](/cells/python-net/zh/aspose.cells.drawing/line/end_arrow_width) |指定线末端箭头的宽度。|
| [theme_color](/cells/python-net/zh/aspose.cells.drawing/line/theme_color) |获取并设置主题颜色。|
| [color](/cells/python-net/zh/aspose.cells.drawing/line/color) |代表线条的颜色。|
| [transparency](/cells/python-net/zh/aspose.cells.drawing/line/transparency) |返回或设置线条的透明度，范围是 0.0（不透明）到 1.0（透明）。|
| [style](/cells/python-net/zh/aspose.cells.drawing/line/style) |代表线条的风格。|
| [weight](/cells/python-net/zh/aspose.cells.drawing/line/weight) |获取或设置该行的 [`WeightType`](/cells/python-net/zh/aspose.cells.drawing/weighttype)。|
| [weight_pt](/cells/python-net/zh/aspose.cells.drawing/line/weight_pt) |获取或设置线的粗细（以点为单位）。|
| [weight_px](/cells/python-net/zh/aspose.cells.drawing/line/weight_px) |获取或设置线条的粗细（以像素为单位）。|
| [formatting_type](/cells/python-net/zh/aspose.cells.drawing/line/formatting_type) |获取或设置格式类型。|
| [is_automatic_color](/cells/python-net/zh/aspose.cells.drawing/line/is_automatic_color) |指示是否自动分配线条颜色。|
| [is_visible](/cells/python-net/zh/aspose.cells.drawing/line/is_visible) |表示该线是否可见。|
| [is_auto](/cells/python-net/zh/aspose.cells.drawing/line/is_auto) |指示此线条样式是否自动分配。|
| [gradient_fill](/cells/python-net/zh/aspose.cells.drawing/line/gradient_fill) |代表渐变填充。|



### 例子

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartMarkerType, ChartType
from aspose.cells.drawing import LineType, WeightType
from aspose.pydrawing import Color

workbook = Workbook()
sheet = workbook.worksheets[0]
cells = sheet.cells
cells.get(0, 1).put_value("Income")
cells.get(1, 0).put_value("Company A")
cells.get(2, 0).put_value("Company B")
cells.get(3, 0).put_value("Company C")
cells.get(1, 1).put_value(10000)
cells.get(2, 1).put_value(20000)
cells.get(3, 1).put_value(30000)
chartIndex = sheet.charts.add(ChartType.LINE, 9, 9, 21, 15)
chart = sheet.charts[chartIndex]
# Add series
chart.n_series.add("A2:B4", True)
# Set category data
chart.n_series.category_data = "=Sheet1!$A$2:$A$4"
# Applying a dotted line style on the lines of an NSeries
chart.n_series[0].border.style = LineType.DOT
chart.n_series[0].border.color = Color.red
# Applying a triangular marker style on the data markers of an NSeries
chart.n_series[0].marker.marker_style = ChartMarkerType.TRIANGLE
# Setting the weight of all lines in an NSeries to medium
chart.n_series[0].border.weight = WeightType.MEDIUM_LINE

```

### 也可以看看
* 模块[`aspose.cells.drawing`](..)
* 类 [`WeightType`](/cells/python-net/zh/aspose.cells.drawing/weighttype)
