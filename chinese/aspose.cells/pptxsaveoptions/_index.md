---
title: PptxSaveOptions类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1230
url: /zh/aspose.cells/pptxsaveoptions/
is_root: false
---
## PptxSaveOptions类
代表 pptx 保存选项。



**遗产：** [`PptxSaveOptions`](/cells/python-net/aspose.cells/pptxsaveoptions) → 
[`PaginatedSaveOptions`](/cells/python-net/aspose.cells/paginatedsaveoptions) → 
[`SaveOptions`](/cells/python-net/zh/aspose.cells/saveoptions)



PptxSaveOptions 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [__init__](/cells/python-net/zh/aspose.cells/pptxsaveoptions/__init__/#) |代表 pptx 保存选项。|
| [__init__](/cells/python-net/zh/aspose.cells/pptxsaveoptions/__init__/#bool) |代表保存 .pptx 文件的选项。|


### 特性
|属性|描述|
| :- | :- |
| [save_format](/cells/python-net/zh/aspose.cells/pptxsaveoptions/save_format) |获取保存文件格式。|
| [clear_data](/cells/python-net/zh/aspose.cells/pptxsaveoptions/clear_data) |保存文件后将工作簿清空。|
| [cached_file_folder](/cells/python-net/zh/aspose.cells/pptxsaveoptions/cached_file_folder) |缓存文件夹用于存储一些大数据。|
| [validate_merged_areas](/cells/python-net/zh/aspose.cells/pptxsaveoptions/validate_merged_areas) |指示保存文件之前是否验证合并的单元格。|
| [merge_areas](/cells/python-net/zh/aspose.cells/pptxsaveoptions/merge_areas) |指示在保存文件之前是否合并条件格式和验证区域。|
| [create_directory](/cells/python-net/zh/aspose.cells/pptxsaveoptions/create_directory) |如果为 true 并且该目录不存在，则在保存文件之前将自动创建该目录。|
| [sort_names](/cells/python-net/zh/aspose.cells/pptxsaveoptions/sort_names) |指示在保存文件之前是否对定义的名称进行排序。|
| [sort_external_names](/cells/python-net/zh/aspose.cells/pptxsaveoptions/sort_external_names) |指示在保存文件之前是否对外部定义的名称进行排序。|
| [refresh_chart_cache](/cells/python-net/zh/aspose.cells/pptxsaveoptions/refresh_chart_cache) |是否刷新图表缓存数据|
| [warning_callback](/cells/python-net/zh/aspose.cells/pptxsaveoptions/warning_callback) |获取或设置警告回调。|
| [update_smart_art](/cells/python-net/zh/aspose.cells/pptxsaveoptions/update_smart_art) |指示是否更新智能艺术设置。<br/>默认值为 false。|
| [default_font](/cells/python-net/zh/aspose.cells/pptxsaveoptions/default_font) |当Excel中的字符是Unicode且未在单元格样式中设置正确的字体时，<br/>它们可能在 pdf、图像中显示为块。<br/>设置默认字体（例如 MingLiu 或 MS Gothic）来显示这些字符。<br/>如果不设置该属性，Aspose.Cells将使用系统默认字体来显示这些unicode字符。|
| [check_workbook_default_font](/cells/python-net/zh/aspose.cells/pptxsaveoptions/check_workbook_default_font) |当Excel中的字符是Unicode且未在单元格样式中设置正确的字体时，<br/>它们可能在 pdf、图像中显示为块。<br/>将其设置为 true 以尝试使用工作簿的默认字体首先显示这些字符。|
| [check_font_compatibility](/cells/python-net/zh/aspose.cells/pptxsaveoptions/check_font_compatibility) |指示是否检查文本中每个字符的字体兼容性。|
| [is_font_substitution_char_granularity](/cells/python-net/zh/aspose.cells/pptxsaveoptions/is_font_substitution_char_granularity) |指示当单元格字体不兼容时是否仅替换该字符的字体。|
| [one_page_per_sheet](/cells/python-net/zh/aspose.cells/pptxsaveoptions/one_page_per_sheet) |如果 OnePagePerSheet 为 true ，则一张表的所有内容将仅输出到结果中的一页。<br/> pagesetup的纸张尺寸将会失效，pagesetup的其他设置<br/>仍然会生效。|
| [all_columns_in_one_page_per_sheet](/cells/python-net/zh/aspose.cells/pptxsaveoptions/all_columns_in_one_page_per_sheet) |如果 AllColumnsInOnePagePerSheet 为 true ，一张表的所有列内容将仅输出到结果中的一页。<br/> pagesetup的纸张尺寸宽度将被忽略，pagesetup的其他设置<br/>仍然会生效。|
| [ignore_error](/cells/python-net/zh/aspose.cells/pptxsaveoptions/ignore_error) |指示是否需要在渲染时隐藏错误。<br/>错误可能是形状、图像、图表渲染等方面的错误。|
| [output_blank_page_when_nothing_to_print](/cells/python-net/zh/aspose.cells/pptxsaveoptions/output_blank_page_when_nothing_to_print) |指示当没有任何内容可打印时是否输出空白页。|
| [page_index](/cells/python-net/zh/aspose.cells/pptxsaveoptions/page_index) |获取或设置要保存的第一页的从 0 开始的索引。|
| [page_count](/cells/python-net/zh/aspose.cells/pptxsaveoptions/page_count) |获取或设置要保存的页数。|
| [printing_page_type](/cells/python-net/zh/aspose.cells/pptxsaveoptions/printing_page_type) |指示将不打印哪些页面。|
| [gridline_type](/cells/python-net/zh/aspose.cells/pptxsaveoptions/gridline_type) |获取或设置网格线类型。|
| [text_cross_type](/cells/python-net/zh/aspose.cells/pptxsaveoptions/text_cross_type) |获取或设置当文本宽度大于单元格宽度时显示的文本类型。|
| [default_edit_language](/cells/python-net/zh/aspose.cells/pptxsaveoptions/default_edit_language) |获取或设置默认编辑语言。|
| [sheet_set](/cells/python-net/zh/aspose.cells/pptxsaveoptions/sheet_set) |获取或设置要渲染的工作表。默认为工作簿中的所有可见工作表：[`SheetSet.visible`](/cells/python-net/zh/aspose.cells.rendering/sheetset#visible)。|
| [draw_object_event_handler](/cells/python-net/zh/aspose.cells/pptxsaveoptions/draw_object_event_handler) |实现该接口以在渲染时获取DrawObject并Bound。|
| [page_saving_callback](/cells/python-net/zh/aspose.cells/pptxsaveoptions/page_saving_callback) |控制/指示页面保存过程的进度。|
| [emf_render_setting](/cells/python-net/zh/aspose.cells/pptxsaveoptions/emf_render_setting) |用于渲染 Emf 图元文件的设置。|
| [ignore_hidden_rows](/cells/python-net/zh/aspose.cells/pptxsaveoptions/ignore_hidden_rows) |指示将 Excel 转换为 PowerPoint 时是否忽略隐藏行。|
| [adjust_font_size_for_row_type](/cells/python-net/zh/aspose.cells/pptxsaveoptions/adjust_font_size_for_row_type) |表示如果行高较小，需要调整什么类型的行的字体大小。|
| [export_view_type](/cells/python-net/zh/aspose.cells/pptxsaveoptions/export_view_type) |获取和设置导出到PowerPoint时的显示类型。<br/>默认导出类型为打印。|



### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`PaginatedSaveOptions`](/cells/python-net/zh/aspose.cells/paginatedsaveoptions)
* 类 [`PptxSaveOptions`](/cells/python-net/zh/aspose.cells/pptxsaveoptions)
* 类 [`SaveOptions`](/cells/python-net/zh/aspose.cells/saveoptions)
