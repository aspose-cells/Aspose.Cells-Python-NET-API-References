---
title: ImageOrPrintOptions类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 30
url: /zh/aspose.cells.rendering/imageorprintoptions/
is_root: false
---
## ImageOrPrintOptions类
允许在将工作表渲染为图像、打印工作表或将图表渲染为图像时指定选项。



ImageOrPrintOptions 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/__init__/#) |导演。|


### 属性
|属性|描述|
| :- | :- |
| [save_format](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/save_format) |获取或设置输出文件格式类型<br/>支持 Tiff/XPS|
| [print_with_status_dialog](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/print_with_status_dialog) |如果 PrintWithStatusDialog = true ，将会有一个对话框显示当前打印状态。<br/>否则不会显示这样的对话框。|
| [horizontal_resolution](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/horizontal_resolution) |获取或设置生成图像的水平分辨率（以每英寸点数为单位）。|
| [vertical_resolution](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/vertical_resolution) |获取或设置生成图像的垂直分辨率（以每英寸点数为单位）。|
| [tiff_compression](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/tiff_compression) |获取或设置仅在将页面保存为 `Tiff` 格式时应用的压缩类型。|
| [tiff_color_depth](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/tiff_color_depth) |获取或设置仅在将页面保存为 `Tiff` 格式时应用的位深度。|
| [tiff_binarization_method](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/tiff_binarization_method) |获取或设置将图像转换为 1 bpp 格式时使用的方法<br/>当 [`ImageOrPrintOptions.image_type`](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions#image_type) 为 Tiff 且 [`ImageOrPrintOptions.tiff_compression`](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions#tiff_compression) 等于 Ccitt3 或 Ccitt4 时。|
| [printing_page](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/printing_page) |指示哪些页面将不会被打印。|
| [quality](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/quality) |获取或设置确定生成图像质量的值<br/>仅在将页面保存为 `Jpeg` 格式时适用。默认值为 100|
| [image_type](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/image_type) |获取或设置生成的图像的格式。<br/>默认值：PNG。|
| [is_cell_auto_fit](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/is_cell_auto_fit) |指示单元格的宽度和高度是否根据单元格值自动调整。<br/>默认值为 false。|
| [one_page_per_sheet](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/one_page_per_sheet) |如果 OnePagePerSheet 为 true ，则一个 sheet 的所有内容将输出到结果中的仅一页。<br/> pagesetup 的纸张大小将无效，并且 pagesetup 的其他设置<br/>仍将有效。|
| [all_columns_in_one_page_per_sheet](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/all_columns_in_one_page_per_sheet) |如果 AllColumnsInOnePagePerSheet 为 true ，则结果中一张表的所有列内容将仅输出到一页。<br/> pagesetup 的纸张大小宽度将无效，并且 pagesetup 的其他设置<br/>仍将有效。|
| [chart_image_type](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/chart_image_type) |转换时指示图表图像类型。<br/>默认值：PNG。|
| [embeded_image_name_in_svg](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/embeded_image_name_in_svg) |指示 svg 中嵌入图像的文件名。<br/>这应该是带有目录的完整路径，例如“c:\\xpsEmbedded”|
| [svg_fit_to_view_port](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/svg_fit_to_view_port) |如果此属性为真，则生成的 svg 将适合视口。|
| [svg_css_prefix](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/svg_css_prefix) |获取或设置svg中css名称的前缀，默认值为空字符串。|
| [only_area](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/only_area) |如果此属性为 true ，则将输出一个区域，并且不会发生任何比例。|
| [text_rendering_hint](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/text_rendering_hint) |指定文本渲染的质量。<br/>默认值为 TextRenderingHint.SystemDefault|
| [smoothing_mode](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/smoothing_mode) |指定是否对直线、曲线和填充区域的边缘应用平滑（抗锯齿）。<br/>默认值为 SmoothingMode.None|
| [transparent](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/transparent) |指示生成的图像的背景是否应透明。|
| [pixel_format](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/pixel_format) |获取或设置生成的图像的像素格式。|
| [is_font_substitution_char_granularity](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/is_font_substitution_char_granularity) |指示当单元格字体不兼容时是否仅替换字符的字体。|
| [page_index](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/page_index) |获取或设置要保存的第一页的从 0 开始的索引。|
| [page_count](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/page_count) |获取或设置要保存的页数。|
| [is_optimized](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/is_optimized) |指示是否优化输出元素。|
| [default_font](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/default_font) |当 Excel 中的字符是 Unicode 且未在单元格样式中设置正确的字体时，<br/>它们可能在 pdf、图像中以块的形式出现。<br/>设置默认字体（例如 MingLiu 或 MS Gothic）来显示这些字符。<br/>如果未设置此属性，Aspose.Cells 将使用系统默认字体来显示这些unicode字符。|
| [check_workbook_default_font](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/check_workbook_default_font) |当 Excel 中的字符是 Unicode 且未在单元格样式中设置正确的字体时，<br/>它们可能在 pdf、图像中以块的形式出现。<br/>将其设置为 true 以尝试首先使用工作簿的默认字体显示这些字符。|
| [output_blank_page_when_nothing_to_print](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/output_blank_page_when_nothing_to_print) |指示当没有内容可打印时是否输出空白页。|
| [gridline_type](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/gridline_type) |获取或设置网格线类型。|
| [gridline_color](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/gridline_color) |获取或设置网格线颜色。|
| [text_cross_type](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/text_cross_type) |获取或设置当文本宽度大于单元格宽度时显示的文本类型。|
| [emf_type](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/emf_type) |获取或设置指定 Metafile 格式的 EmfType。<br/>默认值为 EmfPlusDual。|
| [default_edit_language](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/default_edit_language) |获取或设置默认编辑语言。|
| [sheet_set](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/sheet_set) |获取或设置要渲染的工作表。默认值为工作簿中所有可见的工作表：[`SheetSet.visible`](/cells/python-net/zh/aspose.cells.rendering/sheetset#visible)。|
| [emf_render_setting](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/emf_render_setting) |用于在源文件中渲染 Emf 元文件的设置。|
| [custom_render_settings](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/custom_render_settings) |在渲染期间获取或设置自定义设置。|


### 方法
|方法|描述|
| :- | :- |
| [`set_desired_size(self, desired_width, desired_height)`](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/set_desired_size/#int-int) |设置所需的图像宽度和高度。|
| [`set_desired_size(self, desired_width, desired_height, keep_aspect_ratio)`](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/set_desired_size/#int-int-bool) |设置所需的图像宽度和高度。|



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
