---
title: Trendline类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 340
url: /zh/aspose.cells.charts/trendline/
is_root: false
---
## Trendline类
代表图表中的趋势线。



**继承：** [`Trendline`](/cells/python-net/aspose.cells.charts/trendline) → 
[`Line`](/cells/python-net/zh/aspose.cells.drawing/line)



Trendline 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [compound_type](/cells/python-net/zh/aspose.cells.charts/trendline/compound_type) |指定复合线类型|
| [dash_type](/cells/python-net/zh/aspose.cells.charts/trendline/dash_type) |规定虚线类型|
| [cap_type](/cells/python-net/zh/aspose.cells.charts/trendline/cap_type) |指定结束大写。|
| [join_type](/cells/python-net/zh/aspose.cells.charts/trendline/join_type) |指定连接端。|
| [begin_type](/cells/python-net/zh/aspose.cells.charts/trendline/begin_type) |指定线的开头的箭头。|
| [end_type](/cells/python-net/zh/aspose.cells.charts/trendline/end_type) |指定线末端的箭头。|
| [begin_arrow_length](/cells/python-net/zh/aspose.cells.charts/trendline/begin_arrow_length) |指定线起点箭头的长度。|
| [end_arrow_length](/cells/python-net/zh/aspose.cells.charts/trendline/end_arrow_length) |指定线末端箭头的长度。|
| [begin_arrow_width](/cells/python-net/zh/aspose.cells.charts/trendline/begin_arrow_width) |指定线起点箭头的宽度。|
| [end_arrow_width](/cells/python-net/zh/aspose.cells.charts/trendline/end_arrow_width) |指定线末端箭头的宽度。|
| [theme_color](/cells/python-net/zh/aspose.cells.charts/trendline/theme_color) |获取并设置主题颜色。|
| [color](/cells/python-net/zh/aspose.cells.charts/trendline/color) |代表线条的颜色。|
| [transparency](/cells/python-net/zh/aspose.cells.charts/trendline/transparency) |返回或设置线条的透明度，范围是 0.0（不透明）到 1.0（透明）。|
| [style](/cells/python-net/zh/aspose.cells.charts/trendline/style) |代表线条的风格。|
| [weight](/cells/python-net/zh/aspose.cells.charts/trendline/weight) |获取或设置该行的 [`WeightType`](/cells/python-net/zh/aspose.cells.drawing/weighttype)。|
| [weight_pt](/cells/python-net/zh/aspose.cells.charts/trendline/weight_pt) |获取或设置线的粗细（以点为单位）。|
| [weight_px](/cells/python-net/zh/aspose.cells.charts/trendline/weight_px) |获取或设置线条的粗细（以像素为单位）。|
| [formatting_type](/cells/python-net/zh/aspose.cells.charts/trendline/formatting_type) |获取或设置格式类型。|
| [is_automatic_color](/cells/python-net/zh/aspose.cells.charts/trendline/is_automatic_color) |指示是否自动分配线条颜色。|
| [is_visible](/cells/python-net/zh/aspose.cells.charts/trendline/is_visible) |表示该线是否可见。|
| [is_auto](/cells/python-net/zh/aspose.cells.charts/trendline/is_auto) |指示此线条样式是否自动分配。|
| [gradient_fill](/cells/python-net/zh/aspose.cells.charts/trendline/gradient_fill) |代表渐变填充。|
| [is_name_auto](/cells/python-net/zh/aspose.cells.charts/trendline/is_name_auto) |如果 Microsoft Excel 自动确定趋势线的名称，则返回。|
| [type](/cells/python-net/zh/aspose.cells.charts/trendline/type) |返回趋势线类型。|
| [name](/cells/python-net/zh/aspose.cells.charts/trendline/name) |返回趋势线的名称。|
| [order](/cells/python-net/zh/aspose.cells.charts/trendline/order) |当趋势线类型为多项式时，返回或设置趋势线顺序（大于 1 的整数）。<br/>顺序必须介于 2 到 6 之间。|
| [period](/cells/python-net/zh/aspose.cells.charts/trendline/period) |返回或设置移动平均趋势线的周期。|
| [forward](/cells/python-net/zh/aspose.cells.charts/trendline/forward) |返回或设置趋势线向前延伸的周期数（或散点图上的单位数）。<br/>周期数必须大于或等于零。|
| [backward](/cells/python-net/zh/aspose.cells.charts/trendline/backward) |返回或设置趋势线向后延伸的周期数（或散点图上的单位数）。<br/>周期数必须大于或等于零。<br/>如果图表类型为柱状图，周期数必须介于 0 到 0.5 之间|
| [display_equation](/cells/python-net/zh/aspose.cells.charts/trendline/display_equation) |表示趋势线公式是否显示在图表上（与 R 平方值位于同一数据标签中）。 将此属性设置为 True 会自动打开数据标签。|
| [display_r_squared](/cells/python-net/zh/aspose.cells.charts/trendline/display_r_squared) |表示趋势线的 R 平方值是否显示在图表上（与公式位于同一数据标签中）。将此属性设置为 True 会自动打开数据标签。|
| [intercept](/cells/python-net/zh/aspose.cells.charts/trendline/intercept) |返回或设置趋势线与数值轴的交叉点。|
| [data_labels](/cells/python-net/zh/aspose.cells.charts/trendline/data_labels) |表示指定系列的 DataLabels 对象。|
| [legend_entry](/cells/python-net/zh/aspose.cells.charts/trendline/legend_entry) |根据该趋势线获取图例条目|



### 例子

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType, TrendlineType

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Excel object
sheetIndex = workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[sheetIndex]
# Adding a sample value to "A1" cell
worksheet.cells.get("A1").put_value(50)
# Adding a sample value to "A2" cell
worksheet.cells.get("A2").put_value(100)
# Adding a sample value to "A3" cell
worksheet.cells.get("A3").put_value(150)
# Adding a sample value to "A4" cell
worksheet.cells.get("A4").put_value(200)
# Adding a sample value to "B1" cell
worksheet.cells.get("B1").put_value(60)
# Adding a sample value to "B2" cell
worksheet.cells.get("B2").put_value(32)
# Adding a sample value to "B3" cell
worksheet.cells.get("B3").put_value(50)
# Adding a sample value to "B4" cell
worksheet.cells.get("B4").put_value(40)
# Adding a sample value to "C1" cell as category data
worksheet.cells.get("C1").put_value("Q1")
# Adding a sample value to "C2" cell as category data
worksheet.cells.get("C2").put_value("Q2")
# Adding a sample value to "C3" cell as category data
worksheet.cells.get("C3").put_value("Y1")
# Adding a sample value to "C4" cell as category data
worksheet.cells.get("C4").put_value("Y2")
# Adding a chart to the worksheet
chartIndex = worksheet.charts.add(ChartType.COLUMN, 5, 0, 15, 5)
# Accessing the instance of the newly added chart
chart = worksheet.charts[chartIndex]
# Adding NSeries (chart data source) to the chart ranging from "A1" cell to "B4"
chart.n_series.add("A1:B4", True)
# Setting the data source for the category data of NSeries
chart.n_series.category_data = "C1:C4"
# adding a linear trendline
index = chart.n_series[0].trend_lines.add(TrendlineType.LINEAR)
trendline = chart.n_series[0].trend_lines[index]
# Setting the custom name of the trendline.
trendline.name = "Linear"
# Displaying the equation on chart
trendline.display_equation = True
# Displaying the R-Squared value on chart
trendline.display_r_squared = True
# Saving the Excel file
workbook.save("book1.xls")

```

### 也可以看看
* 模块[`aspose.cells.charts`](..)
* 类 [`Line`](/cells/python-net/zh/aspose.cells.drawing/line)
* 类 [`Trendline`](/cells/python-net/zh/aspose.cells.charts/trendline)
* 类 [`WeightType`](/cells/python-net/zh/aspose.cells.drawing/weighttype)
