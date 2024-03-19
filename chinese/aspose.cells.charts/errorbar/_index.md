---
title: ErrorBar类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 160
url: /zh/aspose.cells.charts/errorbar/
is_root: false
---
## ErrorBar类
代表数据系列的误差线。



**遗产：** [`ErrorBar`](/cells/python-net/aspose.cells.charts/errorbar) → 
[`Line`](/cells/python-net/zh/aspose.cells.drawing/line)



ErrorBar 类型公开以下成员：

### 特性
|属性|描述|
| :- | :- |
| [compound_type](/cells/python-net/zh/aspose.cells.charts/errorbar/compound_type) |指定复合线类型|
| [dash_type](/cells/python-net/zh/aspose.cells.charts/errorbar/dash_type) |指定虚线类型|
| [cap_type](/cells/python-net/zh/aspose.cells.charts/errorbar/cap_type) |指定结束大写字母。|
| [join_type](/cells/python-net/zh/aspose.cells.charts/errorbar/join_type) |指定连接帽。|
| [begin_type](/cells/python-net/zh/aspose.cells.charts/errorbar/begin_type) |指定行首的箭头。|
| [end_type](/cells/python-net/zh/aspose.cells.charts/errorbar/end_type) |指定行尾的箭头。|
| [begin_arrow_length](/cells/python-net/zh/aspose.cells.charts/errorbar/begin_arrow_length) |指定行首的箭头长度。|
| [end_arrow_length](/cells/python-net/zh/aspose.cells.charts/errorbar/end_arrow_length) |指定线末端箭头的长度。|
| [begin_arrow_width](/cells/python-net/zh/aspose.cells.charts/errorbar/begin_arrow_width) |指定线条开头的箭头宽度。|
| [end_arrow_width](/cells/python-net/zh/aspose.cells.charts/errorbar/end_arrow_width) |指定线末端箭头的宽度。|
| [theme_color](/cells/python-net/zh/aspose.cells.charts/errorbar/theme_color) |获取和设置主题颜色。|
| [color](/cells/python-net/zh/aspose.cells.charts/errorbar/color) |代表线条的颜色。|
| [transparency](/cells/python-net/zh/aspose.cells.charts/errorbar/transparency) |返回或设置线条的透明度，其值范围为 0.0（不透明）到 1.0（透明）。|
| [style](/cells/python-net/zh/aspose.cells.charts/errorbar/style) |代表线条的风格。|
| [weight](/cells/python-net/zh/aspose.cells.charts/errorbar/weight) |获取或设置线路的 [`WeightType`](/cells/python-net/zh/aspose.cells.drawing/weighttype)。|
| [weight_pt](/cells/python-net/zh/aspose.cells.charts/errorbar/weight_pt) |获取或设置以点为单位的线的粗细。|
| [weight_px](/cells/python-net/zh/aspose.cells.charts/errorbar/weight_px) |获取或设置线条的粗细（以像素为单位）。|
| [formatting_type](/cells/python-net/zh/aspose.cells.charts/errorbar/formatting_type) |获取或设置格式类型。|
| [is_automatic_color](/cells/python-net/zh/aspose.cells.charts/errorbar/is_automatic_color) |指示线条颜色是否自动指定。|
| [is_visible](/cells/python-net/zh/aspose.cells.charts/errorbar/is_visible) |表示该线是否可见。|
| [is_auto](/cells/python-net/zh/aspose.cells.charts/errorbar/is_auto) |指示此线型是否自动分配。|
| [gradient_fill](/cells/python-net/zh/aspose.cells.charts/errorbar/gradient_fill) |代表渐变填充。|
| [type](/cells/python-net/zh/aspose.cells.charts/errorbar/type) |代表误差条金额类型。|
| [display_type](/cells/python-net/zh/aspose.cells.charts/errorbar/display_type) |代表误差条显示类型。|
| [amount](/cells/python-net/zh/aspose.cells.charts/errorbar/amount) |表示误差条的量。<br/>该金额必须大于或等于零。|
| [show_marker_t_top](/cells/python-net/zh/aspose.cells.charts/errorbar/show_marker_t_top) |指示是否使用 T 形顶格式化误差线。|
| [plus_value](/cells/python-net/zh/aspose.cells.charts/errorbar/plus_value) |当误差条类型为自定义时，表示正误差量。|
| [minus_value](/cells/python-net/zh/aspose.cells.charts/errorbar/minus_value) |当误差条类型为自定义时，表示负误差量。|



### 例子

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType, ErrorBarDisplayType, ErrorBarType

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("a1").put_value(2)
cells.get("a2").put_value(5)
cells.get("a3").put_value(3)
cells.get("a4").put_value(6)
cells.get("b1").put_value(4)
cells.get("b2").put_value(3)
cells.get("b3").put_value(6)
cells.get("b4").put_value(7)
cells.get("C1").put_value("Q1")
cells.get("C2").put_value("Q2")
cells.get("C3").put_value("Y1")
cells.get("C4").put_value("Y2")
chartIndex = workbook.worksheets[0].charts.add(ChartType.COLUMN, 11, 0, 27, 10)
chart = workbook.worksheets[0].charts[chartIndex]
chart.n_series.add("A1:B4", True)
chart.n_series.category_data = "C1:C4"
for i in range(len(chart.n_series)):
    aseries = chart.n_series[i]
    aseries.y_error_bar.display_type = ErrorBarDisplayType.MINUS
    aseries.y_error_bar.type = ErrorBarType.FIXED_VALUE
    aseries.y_error_bar.amount = 5.0

```

### 也可以看看
* 模块[`aspose.cells.charts`](..)
* 类 [`ErrorBar`](/cells/python-net/zh/aspose.cells.charts/errorbar)
* 类 [`Line`](/cells/python-net/zh/aspose.cells.drawing/line)
* 类 [`WeightType`](/cells/python-net/zh/aspose.cells.drawing/weighttype)
