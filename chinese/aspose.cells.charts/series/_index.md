---
title: Series类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 240
url: /zh/aspose.cells.charts/series/
is_root: false
---
## Series类
封装代表图表中单个数据系列的对象。



Series 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [is_filtered](/cells/python-net/zh/aspose.cells.charts/series/is_filtered) |表示该系列是否被选中或被过滤。True 表示该系列被过滤，不会显示在图表上。|
| [layout_properties](/cells/python-net/zh/aspose.cells.charts/series/layout_properties) |表示布局的属性。|
| [points](/cells/python-net/zh/aspose.cells.charts/series/points) |获取图表中一系列点的集合。|
| [area](/cells/python-net/zh/aspose.cells.charts/series/area) |表示Series对象的背景区域。|
| [border](/cells/python-net/zh/aspose.cells.charts/series/border) |表示系列对象的边框。|
| [name](/cells/python-net/zh/aspose.cells.charts/series/name) |获取或设置数据系列的名称。|
| [display_name](/cells/python-net/zh/aspose.cells.charts/series/display_name) |获取图表上显示的系列名称。|
| [count_of_data_values](/cells/python-net/zh/aspose.cells.charts/series/count_of_data_values) |获取数据值的数量。|
| [is_vertical_values](/cells/python-net/zh/aspose.cells.charts/series/is_vertical_values) |指示数据源是否是垂直的。|
| [values](/cells/python-net/zh/aspose.cells.charts/series/values) |表示此图表系列的 Y 值。|
| [values_format_code](/cells/python-net/zh/aspose.cells.charts/series/values_format_code) |表示 Values 的 NumberList 的格式代码。|
| [x_values_format_code](/cells/python-net/zh/aspose.cells.charts/series/x_values_format_code) |表示X Values的NumberList的格式代码。|
| [x_values](/cells/python-net/zh/aspose.cells.charts/series/x_values) |表示图表系列的 x 值。|
| [bubble_sizes](/cells/python-net/zh/aspose.cells.charts/series/bubble_sizes) |获取或设置图表系列的气泡大小值。|
| [trend_lines](/cells/python-net/zh/aspose.cells.charts/series/trend_lines) |返回此系列的所有趋势线。|
| [smooth](/cells/python-net/zh/aspose.cells.charts/series/smooth) |表示曲线平滑。<br/>如果折线图或散点图的曲线平滑功能已打开，则为 True。<br/>仅适用于线图和由线连接的散点图。|
| [shadow](/cells/python-net/zh/aspose.cells.charts/series/shadow) |如果该系列有阴影则为真。|
| [has_3d_effect](/cells/python-net/zh/aspose.cells.charts/series/has_3d_effect) |如果该系列具有三维外观，则为真。<br/>仅适用于气泡图。|
| [bar_3d_shape_type](/cells/python-net/zh/aspose.cells.charts/series/bar_3d_shape_type) |获取或设置用于三维条形图或柱形图的三维形状类型。|
| [data_labels](/cells/python-net/zh/aspose.cells.charts/series/data_labels) |表示指定 ASeries 的 DataLabels 对象。|
| [type](/cells/python-net/zh/aspose.cells.charts/series/type) |获取或设置数据系列的类型。|
| [marker](/cells/python-net/zh/aspose.cells.charts/series/marker) |获取 [`Series.marker`](/cells/python-net/zh/aspose.cells.charts/series#marker)。|
| [plot_on_second_axis](/cells/python-net/zh/aspose.cells.charts/series/plot_on_second_axis) |指示此系列是否绘制在第二个值轴上。|
| [x_error_bar](/cells/python-net/zh/aspose.cells.charts/series/x_error_bar) |表示该系列的X方向误差线。|
| [y_error_bar](/cells/python-net/zh/aspose.cells.charts/series/y_error_bar) |表示该系列的 Y 方向误差条。|
| [has_hi_lo_lines](/cells/python-net/zh/aspose.cells.charts/series/has_hi_lo_lines) |如果折线图有高低线，则为真。<br/>仅适用于折线图。|
| [hi_lo_lines](/cells/python-net/zh/aspose.cells.charts/series/hi_lo_lines) |返回一个 HiLoLines 对象，该对象代表折线图上一系列的高低线。<br/>仅适用于折线图。|
| [has_series_lines](/cells/python-net/zh/aspose.cells.charts/series/has_series_lines) |如果堆积柱形图或条形图有系列线或<br/>如果饼图或饼图条形图的两个部分之间有连接线。<br/>仅适用于堆积柱形图、条形图、饼图或饼条图。|
| [series_lines](/cells/python-net/zh/aspose.cells.charts/series/series_lines) |返回一个 SeriesLines 对象，该对象代表堆积条形图或堆积柱形图的系列线。<br/>仅适用于堆积条形图和堆积柱形图。|
| [has_drop_lines](/cells/python-net/zh/aspose.cells.charts/series/has_drop_lines) |如果图表有下降线，则为真。<br/>仅适用于折线图或面积图。|
| [drop_lines](/cells/python-net/zh/aspose.cells.charts/series/drop_lines) |返回一个 [`Line`](/cells/python-net/zh/aspose.cells.drawing/line) 对象，该对象代表折线图或面积图上一系列的下拉线。<br/>仅适用于折线图或面积图。|
| [has_up_down_bars](/cells/python-net/zh/aspose.cells.charts/series/has_up_down_bars) |如果折线图有上涨和下跌的条形图，则为真。<br/>仅适用于折线图。|
| [up_bars](/cells/python-net/zh/aspose.cells.charts/series/up_bars) |返回代表折线图上向上条的 DropBars 对象。<br/>仅适用于折线图。|
| [down_bars](/cells/python-net/zh/aspose.cells.charts/series/down_bars) |返回代表折线图上向下条形的 [`DropBars`](/cells/python-net/zh/aspose.cells.charts/dropbars) 对象。<br/>仅适用于折线图。|
| [is_color_varied](/cells/python-net/zh/aspose.cells.charts/series/is_color_varied) |表示点的颜色是否变化。<br/>图表必须仅包含一个系列。|
| [gap_width](/cells/python-net/zh/aspose.cells.charts/series/gap_width) |返回或设置条形或列簇之间的空间，以条形或列宽度的百分比表示。<br/>此属性的值必须介于 0 到 500 之间。|
| [first_slice_angle](/cells/python-net/zh/aspose.cells.charts/series/first_slice_angle) |获取或设置第一个饼图或圆环图切片的角度，以度为单位（从垂直方向顺时针旋转）。<br/>仅适用于饼图、三维饼图和圆环图，0 到 360。|
| [overlap](/cells/python-net/zh/aspose.cells.charts/series/overlap) |指定条形和柱形的定位方式。<br/>可以是 -100 到 100 之间的值。<br/>仅适用于二维条形图和二维柱形图。|
| [second_plot_size](/cells/python-net/zh/aspose.cells.charts/series/second_plot_size) |返回或设置饼图或饼图条形图的次要部分的大小，<br/>占主要饼图大小的百分比。<br/>可以是 5 至 200 之间的值。|
| [split_type](/cells/python-net/zh/aspose.cells.charts/series/split_type) |返回或设置一个值，该值用于确定哪些数据点位于饼图或饼图的第二个饼图或条形图中<br/>饼图。|
| [split_value](/cells/python-net/zh/aspose.cells.charts/series/split_value) |返回或设置一个值，该值将用于确定哪些数据点位于第二个饼图或条形图中<br/>饼图中的饼或饼图中的条。|
| [is_auto_split](/cells/python-net/zh/aspose.cells.charts/series/is_auto_split) |指示阈值是否自动。|
| [bubble_scale](/cells/python-net/zh/aspose.cells.charts/series/bubble_scale) |获取或设置指定图表组中气泡的比例因子。<br/>它可以是从 0（零）到 300 的整数值，<br/>对应于默认大小的百分比。<br/>仅适用于气泡图。|
| [size_represents](/cells/python-net/zh/aspose.cells.charts/series/size_represents) |获取或设置气泡图上气泡大小所代表的含义。|
| [show_negative_bubbles](/cells/python-net/zh/aspose.cells.charts/series/show_negative_bubbles) |如果图表组显示负气泡，则为 True。仅适用于气泡图。|
| [doughnut_hole_size](/cells/python-net/zh/aspose.cells.charts/series/doughnut_hole_size) |返回或设置圆环图组中孔的大小。<br/>孔洞大小以图表大小的百分比表示，介于 10% 到 90% 之间。|
| [explosion](/cells/python-net/zh/aspose.cells.charts/series/explosion) |打开的饼图切片与饼图中心的距离以饼图直径的百分比表示。|
| [has_radar_axis_labels](/cells/python-net/zh/aspose.cells.charts/series/has_radar_axis_labels) |如果雷达图具有分类轴标签，则为 True。仅适用于雷达图。|
| [has_leader_lines](/cells/python-net/zh/aspose.cells.charts/series/has_leader_lines) |如果系列有引导线，则为真。|
| [leader_lines](/cells/python-net/zh/aspose.cells.charts/series/leader_lines) |表示图表上的引线。引线将数据标签连接到数据点。<br/>该对象不是一个集合；没有代表单条引线的对象。|
| [legend_entry](/cells/python-net/zh/aspose.cells.charts/series/legend_entry) |根据该系列获取图例条目。|
| [shape_properties](/cells/python-net/zh/aspose.cells.charts/series/shape_properties) |获取保存该系列的可视形状属性的 [`ShapePropertyCollection`](/cells/python-net/zh/aspose.cells.drawing/shapepropertycollection) 对象。|


### 方法
|方法|描述|
| :- | :- |
| [`move(self, count)`](/cells/python-net/zh/aspose.cells.charts/series/move/#int) |将系列向上或向下移动。|



### 例子

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartMarkerType, ChartType, FormattingType
from aspose.pydrawing import Color

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
seriesIndex = chart.n_series.add("A1:B4", True)
# Setting the data source for the category data of NSeries
chart.n_series.category_data = "C1:C4"
series = chart.n_series[seriesIndex]
# Setting the values of the series.
series.values = "=B1:B4"
# Changing the chart type of the series.
series.type = ChartType.LINE
# Setting marker properties.
series.marker.marker_style = ChartMarkerType.CIRCLE
series.marker.foreground_color_set_type = FormattingType.AUTOMATIC
series.marker.foreground_color = Color.black
series.marker.background_color_set_type = FormattingType.AUTOMATIC
# do your business
# Saving the Excel file
workbook.save("book1.xls")

```

### 也可以看看
* 模块[`aspose.cells.charts`](..)
* 类 [`DropBars`](/cells/python-net/zh/aspose.cells.charts/dropbars)
* 类 [`Line`](/cells/python-net/zh/aspose.cells.drawing/line)
* 类 [`ShapePropertyCollection`](/cells/python-net/zh/aspose.cells.drawing/shapepropertycollection)
