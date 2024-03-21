---
title: ImageOrPrintOptions类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 40
url: /zh/aspose.cells.rendering/imageorprintoptions/
is_root: false
---
## ImageOrPrintOptions类
允许在将工作表渲染为图像、打印工作表或将图表渲染为图像时指定选项。



ImageOrPrintOptions 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [__init__](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/__init__/#) |构造 ImageOrPrintOptions 的新实例|


### 特性
|属性|描述|
| :- | :- |
| [save_format](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/save_format) |获取或设置输出文件格式类型<br/>支持蒂夫/XPS|
| [print_with_status_dialog](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/print_with_status_dialog) |如果 PrintWithStatusDialog = true ，将会出现一个对话框显示当前打印状态。<br/>否则不会显示这样的对话框。|
| [horizontal_resolution](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/horizontal_resolution) |获取或设置生成的图像的水平分辨率（以每英寸点数为单位）。<br/>应用除 Emf 格式图像之外的生成图像方法。|
| [vertical_resolution](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/vertical_resolution) |获取或设置生成的图像的垂直分辨率（以每英寸点数为单位）。<br/>除Emf格式图像外，均采用生成图像方法。|
| [tiff_compression](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/tiff_compression) |获取或设置仅在将页面保存为 `Tiff` 格式时应用的压缩类型。|
| [tiff_color_depth](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/tiff_color_depth) |获取或设置仅在将页面保存为 `Tiff` 格式时应用的位深度。|
| [tiff_binarization_method](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/tiff_binarization_method) |获取或设置将图像转换为 1 bpp 格式时使用的方法<br/>当 [`ImageOrPrintOptions.image_type`](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions#image_type) 为 Tiff 并且 [`ImageOrPrintOptions.tiff_compression`](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions#tiff_compression) 等于 Ccitt3 或 Ccitt4 时。|
| [printing_page](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/printing_page) |指示将不打印哪些页面。|
| [quality](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/quality) |获取或设置确定生成图像质量的值<br/>仅在将页面保存为 `Jpeg` 格式时应用。默认值为 100|
| [image_type](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/image_type) |获取或设置生成图像的格式。<br/>默认值：PNG。|
| [is_cell_auto_fit](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/is_cell_auto_fit) |指示单元格的宽度和高度是否自动根据单元格值进行调整。<br/>默认值为 false。|
| [one_page_per_sheet](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/one_page_per_sheet) |如果 OnePagePerSheet 为 true ，则一张表的所有内容将仅输出到结果中的一页。<br/> pagesetup的纸张尺寸将会失效，pagesetup的其他设置<br/>仍然会生效。|
| [all_columns_in_one_page_per_sheet](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/all_columns_in_one_page_per_sheet) |如果 AllColumnsInOnePagePerSheet 为 true ，一张表的所有列内容将仅输出到结果中的一页。<br/>pagesetup的纸张尺寸宽度将失效，pagesetup的其他设置<br/>仍然会生效。|
| [draw_object_event_handler](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/draw_object_event_handler) |实现该接口以在渲染时获取DrawObject并Bound。|
| [chart_image_type](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/chart_image_type) |指定转换时的图表图像类型。<br/>默认值：PNG。|
| [embeded_image_name_in_svg](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/embeded_image_name_in_svg) |指示 svg 中嵌入图像的文件名。<br/>这应该是包含“c:\\xpsEmbedded”等目录的完整路径|
| [svg_fit_to_view_port](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/svg_fit_to_view_port) |如果此属性为 true，则生成的 svg 将适合视图端口。|
| [only_area](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/only_area) |如果该属性为 true ，则将输出一个 Area，并且不会产生任何缩放效果。|
| [text_rendering_hint](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/text_rendering_hint) |指定文本呈现的质量。<br/>默认值为 TextRenderingHint.SystemDefault|
| [smoothing_mode](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/smoothing_mode) |指定是否将平滑（抗锯齿）应用于直线、曲线以及填充区域的边缘。<br/>默认值为 SmoothingMode.None|
| [transparent](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/transparent) |指示生成的图像的背景是否应该是透明的。|
| [pixel_format](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/pixel_format) |获取或设置生成图像的像素格式。|
| [warning_callback](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/warning_callback) |获取或设置警告回调。|
| [page_saving_callback](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/page_saving_callback) |控制/指示页面保存过程的进度。|
| [is_font_substitution_char_granularity](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/is_font_substitution_char_granularity) |指示当单元格字体不兼容时是否仅替换该字符的字体。|
| [page_index](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/page_index) |获取或设置要保存的第一页的从 0 开始的索引。|
| [page_count](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/page_count) |获取或设置要保存的页数。|
| [is_optimized](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/is_optimized) |指示是否优化输出元素。|
| [default_font](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/default_font) |当Excel中的字符是Unicode且未在单元格样式中设置正确的字体时，<br/>它们可能在 pdf、图像中显示为块。<br/>设置默认字体（例如 MingLiu 或 MS Gothic）来显示这些字符。<br/>如果不设置该属性，Aspose.Cells将使用系统默认字体来显示这些unicode字符。|
| [check_workbook_default_font](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/check_workbook_default_font) |当Excel中的字符是Unicode且未在单元格样式中设置正确的字体时，<br/>它们可能在 pdf、图像中显示为块。<br/>将其设置为 true 以尝试使用工作簿的默认字体首先显示这些字符。|
| [output_blank_page_when_nothing_to_print](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/output_blank_page_when_nothing_to_print) |指示当没有任何内容可打印时是否输出空白页。|
| [gridline_type](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/gridline_type) |获取或设置网格线类型。|
| [text_cross_type](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/text_cross_type) |获取或设置当文本宽度大于单元格宽度时显示的文本类型。|
| [emf_type](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/emf_type) |获取或设置指定图元文件格式的 EmfType。<br/>默认值为 EmfPlusDual。|
| [default_edit_language](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/default_edit_language) |获取或设置默认编辑语言。|
| [sheet_set](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/sheet_set) |获取或设置要渲染的工作表。默认为工作簿中的所有可见工作表：[`SheetSet.visible`](/cells/python-net/zh/aspose.cells.rendering/sheetset#visible)。|
| [emf_render_setting](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/emf_render_setting) |用于渲染 Emf 图元文件的设置。|


### 方法
|方法|描述|
| :- | :- |
| [set_desired_size](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/set_desired_size/#int-int) |设置所需的图像宽度和高度。|
| [set_desired_size](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/set_desired_size/#int-int-bool) |设置所需的图像宽度和高度。|



### 例子

```python
from aspose.cells import Workbook
from aspose.cells.drawing import ImageType
from aspose.cells.rendering import ImageOrPrintOptions

# Set Image Or Print Options
options = ImageOrPrintOptions()
# Set output image format
options.image_type = ImageType.PNG
# Set Horizontal resolution
options.horizontal_resolution = 300
# Set Vertical Resolution
options.vertical_resolution = 300
# Instantiate Workbook
book = Workbook("test.xls")
# Save chart as Image using ImageOrPrint Options
book.worksheets[0].charts[0].to_image("chart.png", options)

```

### 也可以看看
* 模块[`aspose.cells.rendering`](..)
