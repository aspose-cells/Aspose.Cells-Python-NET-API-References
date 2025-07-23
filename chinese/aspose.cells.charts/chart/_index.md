---
title: Chart类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 30
url: /zh/aspose.cells.charts/chart/
is_root: false
---
## Chart类
封装代表单个 Excel 图表的对象。



Chart 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [style](/cells/python-net/zh/aspose.cells.charts/chart/style) |获取并设置内置样式。|
| [chart_object](/cells/python-net/zh/aspose.cells.charts/chart/chart_object) |表示图表形状；|
| [hide_pivot_field_buttons](/cells/python-net/zh/aspose.cells.charts/chart/hide_pivot_field_buttons) |指示仅当图表为数据透视图时是否隐藏数据透视图字段按钮。|
| [pivot_options](/cells/python-net/zh/aspose.cells.charts/chart/pivot_options) |指定图表上显示的枢轴控件|
| [pivot_source](/cells/python-net/zh/aspose.cells.charts/chart/pivot_source) |来源是数据透视表的数据。<br/>如果 PivotSource 不为空，则图表为 PivotChart。|
| [plot_by](/cells/python-net/zh/aspose.cells.charts/chart/plot_by) |获取并设置是否按行或列绘图。|
| [plot_empty_cells_type](/cells/python-net/zh/aspose.cells.charts/chart/plot_empty_cells_type) |获取并设置如何绘制空单元格。|
| [plot_visible_cells](/cells/python-net/zh/aspose.cells.charts/chart/plot_visible_cells) |指示是否仅绘制可见单元格。|
| [plot_visible_cells_only](/cells/python-net/zh/aspose.cells.charts/chart/plot_visible_cells_only) |指示是否仅绘制可见单元格。|
| [display_na_as_blank](/cells/python-net/zh/aspose.cells.charts/chart/display_na_as_blank) |指示是否将#N/A显示为空白值。|
| [name](/cells/python-net/zh/aspose.cells.charts/chart/name) |获取并设置图表的名称。|
| [size_with_window](/cells/python-net/zh/aspose.cells.charts/chart/size_with_window) |如果 Microsoft 则为真 Excel 调整图表大小以匹配图表工作表窗口的大小。|
| [worksheet](/cells/python-net/zh/aspose.cells.charts/chart/worksheet) |获取包含此图表的工作表。|
| [shapes](/cells/python-net/zh/aspose.cells.charts/chart/shapes) |返回此图表中的所有绘图形状。|
| [print_size](/cells/python-net/zh/aspose.cells.charts/chart/print_size) |获取并设置打印图表的大小。|
| [type](/cells/python-net/zh/aspose.cells.charts/chart/type) |获取或设置图表的类型。|
| [n_series](/cells/python-net/zh/aspose.cells.charts/chart/n_series) |获取表示图表中数据系列的 [`SeriesCollection`](/cells/python-net/zh/aspose.cells.charts/seriescollection) 集合。|
| [filtered_n_series](/cells/python-net/zh/aspose.cells.charts/chart/filtered_n_series) |获取一个 [`SeriesCollection`](/cells/python-net/zh/aspose.cells.charts/seriescollection) 集合，表示图表中过滤的数据系列。|
| [title](/cells/python-net/zh/aspose.cells.charts/chart/title) |获取图表的标题。|
| [sub_title](/cells/python-net/zh/aspose.cells.charts/chart/sub_title) |获取图表的副标题。<br/>仅适用于ODS格式的文件。|
| [plot_area](/cells/python-net/zh/aspose.cells.charts/chart/plot_area) |获取包含轴刻度标签的图表绘图区域。|
| [chart_area](/cells/python-net/zh/aspose.cells.charts/chart/chart_area) |获取工作表中的图表区域。|
| [category_axis](/cells/python-net/zh/aspose.cells.charts/chart/category_axis) |获取图表的 X 轴。|
| [value_axis](/cells/python-net/zh/aspose.cells.charts/chart/value_axis) |获取图表的 Y 轴。|
| [second_value_axis](/cells/python-net/zh/aspose.cells.charts/chart/second_value_axis) |获取图表的第二个 Y 轴。|
| [second_category_axis](/cells/python-net/zh/aspose.cells.charts/chart/second_category_axis) |获取图表的第二个 X 轴。|
| [series_axis](/cells/python-net/zh/aspose.cells.charts/chart/series_axis) |获取图表的系列轴。|
| [legend](/cells/python-net/zh/aspose.cells.charts/chart/legend) |获取图表图例。|
| [chart_data_table](/cells/python-net/zh/aspose.cells.charts/chart/chart_data_table) |表示图表数据表。|
| [show_legend](/cells/python-net/zh/aspose.cells.charts/chart/show_legend) |获取或设置一个值，指示是否显示图表图例。默认值为 true。|
| [is_rectangular_cornered](/cells/python-net/zh/aspose.cells.charts/chart/is_rectangular_cornered) |获取或设置一个值，该值指示图表区域是否为矩形角。<br/>默认为真。|
| [show_data_table](/cells/python-net/zh/aspose.cells.charts/chart/show_data_table) |获取或设置一个值，该值指示图表是否显示数据表。|
| [first_slice_angle](/cells/python-net/zh/aspose.cells.charts/chart/first_slice_angle) |获取或设置第一个饼图或圆环图切片的角度，以度为单位（从垂直方向顺时针旋转）。<br/>仅适用于饼图、三维饼图和圆环图，0 到 360。|
| [gap_width](/cells/python-net/zh/aspose.cells.charts/chart/gap_width) |返回或设置条形或列簇之间的空间，以条形或列宽度的百分比表示。<br/>此属性的值必须介于 0 到 500 之间。|
| [gap_depth](/cells/python-net/zh/aspose.cells.charts/chart/gap_depth) |获取或设置三维图表中数据系列之间的距离（以标记宽度的百分比表示）。<br/>此属性的值必须介于 0 到 500 之间。|
| [floor](/cells/python-net/zh/aspose.cells.charts/chart/floor) |返回代表三维图表墙的 [`Chart.floor`](/cells/python-net/zh/aspose.cells.charts/chart#floor) 对象。|
| [walls](/cells/python-net/zh/aspose.cells.charts/chart/walls) |返回代表三维图表墙的 [`Chart.walls`](/cells/python-net/zh/aspose.cells.charts/chart#walls) 对象。|
| [back_wall](/cells/python-net/zh/aspose.cells.charts/chart/back_wall) |返回代表三维图表后墙的 [`Chart.walls`](/cells/python-net/zh/aspose.cells.charts/chart#walls) 对象。|
| [side_wall](/cells/python-net/zh/aspose.cells.charts/chart/side_wall) |返回代表三维图表侧壁的 [`Chart.walls`](/cells/python-net/zh/aspose.cells.charts/chart#walls) 对象。|
| [walls_and_gridlines_2d](/cells/python-net/zh/aspose.cells.charts/chart/walls_and_gridlines_2d) |如果网格线在三维图表上以二维方式绘制，则为 True。|
| [rotation_angle](/cells/python-net/zh/aspose.cells.charts/chart/rotation_angle) |表示三维图表视图的旋转（绘图区围绕 z 轴的旋转，以度为单位）。|
| [elevation](/cells/python-net/zh/aspose.cells.charts/chart/elevation) |表示三维图表视图的高度（以度为单位）。|
| [right_angle_axes](/cells/python-net/zh/aspose.cells.charts/chart/right_angle_axes) |如果图表轴为直角，则为 True。仅适用于三维图表（3D 柱形图和三维饼图除外）。|
| [auto_scaling](/cells/python-net/zh/aspose.cells.charts/chart/auto_scaling) |如果 Microsoft 则为真 Excel 缩放三维图表，以使其大小更接近等效的二维图表。<br/> RightAngleAxes 属性必须为 True。|
| [height_percent](/cells/python-net/zh/aspose.cells.charts/chart/height_percent) |返回或设置三维图表的高度占图表宽度的百分比（介于 5% 和 500% 之间）。|
| [perspective](/cells/python-net/zh/aspose.cells.charts/chart/perspective) |返回或设置三维图表视图的透视图。必须介于 0 到 100 之间。<br/>如果 RightAngleAxes 属性为 True，则忽略此属性。|
| [is_3d](/cells/python-net/zh/aspose.cells.charts/chart/is_3d) |指示图表是否为 3d 图表。|
| [depth_percent](/cells/python-net/zh/aspose.cells.charts/chart/depth_percent) |以图表宽度的百分比（介于 20% 和 2000% 之间）表示三维图表的深度。|
| [actual_chart_size](/cells/python-net/zh/aspose.cells.charts/chart/actual_chart_size) |以像素为单位获取图表的实际大小。|
| [placement](/cells/python-net/zh/aspose.cells.charts/chart/placement) |表示图表附加到其下方单元格的方式。|
| [page_setup](/cells/python-net/zh/aspose.cells.charts/chart/page_setup) |代表此图表中的页面设置描述。|
| [line](/cells/python-net/zh/aspose.cells.charts/chart/line) |接通线路。|


### 方法
|方法|描述|
| :- | :- |
| [`calculate(self)`](/cells/python-net/zh/aspose.cells.charts/chart/calculate/#) |如果绘图区域、轴的位置是自动分配的，则计算它们的自定义位置。|
| [`calculate(self, calculate_options)`](/cells/python-net/zh/aspose.cells.charts/chart/calculate/#aspose.cells.charts.chartcalculateoptions) |使用图表计算选项计算绘图区域、轴的自定义位置（如果它们的位置是自动分配的）。|
| [`to_image(self, image_file)`](/cells/python-net/zh/aspose.cells.charts/chart/to_image/#str) |创建图表图像并将其保存到文件中。<br/>文件名的扩展名决定了图像的格式。|
| [`to_image(self, image_file, image_type)`](/cells/python-net/zh/aspose.cells.charts/chart/to_image/#str-aspose.cells.drawing.imagetype) |创建图表图像并将其保存到指定图像类型的文件中。|
| [`to_image(self, image_file, jpeg_quality)`](/cells/python-net/zh/aspose.cells.charts/chart/to_image/#str-int) |创建图表图像并将其保存为 Jpeg 格式的文件。|
| [`to_image(self, stream, jpeg_quality)`](/cells/python-net/zh/aspose.cells.charts/chart/to_image/#io.rawiobase-int) |创建图表图像并将其保存为 Jpeg 格式的流。|
| [`to_image(self, stream, image_type)`](/cells/python-net/zh/aspose.cells.charts/chart/to_image/#io.rawiobase-aspose.cells.drawing.imagetype) |创建图表图像并将其保存到指定格式的流中。|
| [`to_image(self, image_file, options)`](/cells/python-net/zh/aspose.cells.charts/chart/to_image/#str-aspose.cells.rendering.imageorprintoptions) |创建图表图像并将其保存到文件中。<br/>文件名的扩展名决定了图像的格式。|
| [`to_image(self, stream, options)`](/cells/python-net/zh/aspose.cells.charts/chart/to_image/#io.rawiobase-aspose.cells.rendering.imageorprintoptions) |创建图表图像并将其保存到指定格式的流中。|
| [`to_pdf(self, file_name)`](/cells/python-net/zh/aspose.cells.charts/chart/to_pdf/#str) |将图表保存为 pdf 文件。|
| [`to_pdf(self, file_name, desired_page_width, desired_page_height, h_alignment_type, v_alignment_type)`](/cells/python-net/zh/aspose.cells.charts/chart/to_pdf/#str-float-float-aspose.cells.pagelayoutalignmenttype-aspose.cells.pagelayoutalignmenttype) |将图表保存为 pdf 文件。|
| [`to_pdf(self, stream)`](/cells/python-net/zh/aspose.cells.charts/chart/to_pdf/#io.rawiobase) |创建图表 pdf 并将其保存到流中。|
| [`to_pdf(self, stream, desired_page_width, desired_page_height, h_alignment_type, v_alignment_type)`](/cells/python-net/zh/aspose.cells.charts/chart/to_pdf/#io.rawiobase-float-float-aspose.cells.pagelayoutalignmenttype-aspose.cells.pagelayoutalignmenttype) |创建图表 pdf 并将其保存到流中。|
| [`is_refered_by_chart(self, row_index, column_index)`](/cells/python-net/zh/aspose.cells.charts/chart/is_refered_by_chart/#int-int) |返回单元格是否由图表引用。|
| [`is_cell_refered_by_chart(self, sheet_index, row_index, column_index)`](/cells/python-net/zh/aspose.cells.charts/chart/is_cell_refered_by_chart/#int-int-int) |返回单元格是否由图表引用。|
| [`is_chart_data_changed(self)`](/cells/python-net/zh/aspose.cells.charts/chart/is_chart_data_changed/#) |检测图表的数据源是否已更改。|
| [`refresh_pivot_data(self)`](/cells/python-net/zh/aspose.cells.charts/chart/refresh_pivot_data/#) |从数据透视表刷新图表的数据。|
| [`change_template(self, data)`](/cells/python-net/zh/aspose.cells.charts/chart/change_template/#bytes) |使用预设模板更改图表类型。|
| [`move(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column)`](/cells/python-net/zh/aspose.cells.charts/chart/move/#int-int-int-int) |将图表移动到指定位置。|
| [`get_actual_size(self)`](/cells/python-net/zh/aspose.cells.charts/chart/get_actual_size/#) |以像素为单位获取图表的实际大小。|
| [`has_axis(self, aixs_type, is_primary)`](/cells/python-net/zh/aspose.cells.charts/chart/has_axis/#aspose.cells.charts.axistype-bool) |返回图表上存在的轴。|
| [`switch_row_column(self)`](/cells/python-net/zh/aspose.cells.charts/chart/switch_row_column/#) |切换行/列。|
| [`get_chart_data_range(self)`](/cells/python-net/zh/aspose.cells.charts/chart/get_chart_data_range/#) |获取图表的数据源范围。|
| [`set_chart_data_range(self, area, is_vertical)`](/cells/python-net/zh/aspose.cells.charts/chart/set_chart_data_range/#str-bool) |指定图表的数据范围。|



### 例子

以下代码显示如何使用.Net 代码创建图表。

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType

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
chartIndex = sheet.charts.add(ChartType.COLUMN, 9, 9, 21, 15)
chart = sheet.charts[chartIndex]
chart.set_chart_data_range("A1:B4", True)
chart.show_legend = True
chart.title.text = "Income Analysis"

```

### 也可以看看
* 模块[`aspose.cells.charts`](..)
* 类 [`SeriesCollection`](/cells/python-net/zh/aspose.cells.charts/seriescollection)
