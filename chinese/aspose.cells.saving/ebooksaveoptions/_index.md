---
title: EbookSaveOptions类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 10
url: /zh/aspose.cells.saving/ebooksaveoptions/
is_root: false
---
## EbookSaveOptions类
代表保存电子书文件的选项。



**遗产：** [`EbookSaveOptions`](/cells/python-net/aspose.cells.saving/ebooksaveoptions) → 
[`HtmlSaveOptions`](/cells/python-net/aspose.cells/htmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/zh/aspose.cells/saveoptions)



EbookSaveOptions 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [__init__](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/__init__/#) |创建用于保存电子书文件的选项。|


### 特性
|属性|描述|
| :- | :- |
| [save_format](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/save_format) |获取保存文件格式。|
| [clear_data](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/clear_data) |保存文件后将工作簿清空。|
| [cached_file_folder](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/cached_file_folder) |缓存文件夹用于存储一些大数据。|
| [validate_merged_areas](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/validate_merged_areas) |指示保存文件之前是否验证合并的单元格。|
| [merge_areas](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/merge_areas) |指示在保存文件之前是否合并条件格式和验证区域。|
| [create_directory](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/create_directory) |如果为 true 并且该目录不存在，则在保存文件之前将自动创建该目录。|
| [sort_names](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/sort_names) |指示在保存文件之前是否对定义的名称进行排序。|
| [sort_external_names](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/sort_external_names) |指示在保存文件之前是否对外部定义的名称进行排序。|
| [refresh_chart_cache](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/refresh_chart_cache) |是否刷新图表缓存数据|
| [warning_callback](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/warning_callback) |获取或设置警告回调。|
| [update_smart_art](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/update_smart_art) |指示是否更新智能艺术设置。<br/>默认值为 false。|
| [ignore_invisible_shapes](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/ignore_invisible_shapes) |指示是否导出那些不可见的形状|
| [page_title](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/page_title) |html 页面的标题。<br/>仅用于保存到 html 流。|
| [attached_files_directory](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/attached_files_directory) |附加文件将保存到的目录。<br/>仅用于保存到 html 流。|
| [attached_files_url_prefix](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/attached_files_url_prefix) |指定 html 文件中图像等附加文件的 Url 前缀。<br/>仅用于保存到 html 流。|
| [default_font_name](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/default_font_name) |指定导出html的默认字体名称，当style的字体不存在时将使用默认字体，<br/>如果该属性为空，Aspose.Cells将使用与原始字体同族的通用字体，<br/>默认值为空。|
| [worksheet_scalable](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/worksheet_scalable) |指示将文件保存为 html 时是否通过工作表缩放级别放大或缩小 html，默认值为 false。|
| [is_export_comments](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/is_export_comments) |表示保存文件到html时是否导出注释，默认为false。|
| [export_comments_type](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_comments_type) |表示将注释导出到 html 文件的类型。|
| [disable_downlevel_revealed_comments](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/disable_downlevel_revealed_comments) |指示将文件导出为 html 时是否禁用下层显示的条件注释，默认值为 false。|
| [is_exp_image_to_temp_dir](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/is_exp_image_to_temp_dir) |指示是否将图像文件导出到临时目录。<br/>仅用于保存到 html 流。|
| [image_scalable](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/image_scalable) |是否使用可缩放单位来描述图像宽度<br/>当使用可缩放单位来描述列宽时。<br/>默认值是true。|
| [width_scalable](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/width_scalable) |指示是否以比例单位导出列宽到html。<br/>默认值为 false。|
| [export_single_tab](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_single_tab) |当文件只有一个工作表时是否导出单个选项卡。<br/>默认值为 false。|
| [export_images_as_base64](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_images_as_base64) |指定图像是否以 Base64 格式保存为 HTML、MHTML 或 EPUB。|
| [export_active_worksheet_only](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_active_worksheet_only) |指示是否仅将活动工作表导出到 html 文件。<br/>如果为 true，则仅将活动工作表导出到 html 文件；<br/>如果为 false，则整个工作簿将导出到 html 文件。<br/>默认值为 false。|
| [export_print_area_only](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_print_area_only) |指示是否仅将打印区域导出为html 文件。默认值为 false。|
| [export_area](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_area) |获取或设置当前活动工作表的导出单元格区域。<br/>如果设置此属性，当前活动工作表的打印区域将被忽略。<br/>将文件保存为 html 时，只会导出指定区域。|
| [parse_html_tag_in_cell](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/parse_html_tag_in_cell) |指示单元格中的html标签（例如`<div></div>`）是否应该解析为单元格值或保留原样。<br/>默认值是true。|
| [html_cross_string_type](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/html_cross_string_type) |指示以 html 格式保存 Excel 文件时是否以与 MS Excel 相同的方式显示跨单元格字符串。<br/>默认情况下，该值为“Default”，因此，对于跨单元格字符串，Aspose.Cells 创建的 html 文件与 MS Excel 创建的 html 文件几乎没有区别。<br/>但对于创建大型 html 文件的性能，将该值设置为 Cross 会比设置为 Default 或 Fit2Cell 快数倍。|
| [hidden_col_display_type](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/hidden_col_display_type) | Excel中的隐藏列（该列的宽度为0），在将其保存为html格式之前，<br/>如果 HtmlHiddenColDisplayType 为“Remove”，则不会输出隐藏列，<br/>如果值为“Hidden”，则该列将被输出，但被隐藏，默认值为“Hidden”|
| [hidden_row_display_type](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/hidden_row_display_type) | Excel中的隐藏行（该行的高度为0），在将其保存为html格式之前，<br/>如果 HtmlHiddenRowDisplayType 为“Remove”，则不会输出隐藏行，<br/>如果值为“Hidden”，则该行将被输出，但被隐藏，默认值为“Hidden”|
| [encoding](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/encoding) |如果未设置，则使用 Encoding.UTF8 作为默认编码类型。|
| [export_object_listener](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_object_listener) |获取或设置用于导出对象的 ExportObjectListener。|
| [file_path_provider](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/file_path_provider) |获取或设置用于将Worksheet单独导出为html的IFilePathProvider。|
| [stream_provider](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/stream_provider) |获取或设置用于导出对象的 IStreamProvider。|
| [image_options](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/image_options) |导出前获取 ImageOrPrintOptions 对象|
| [save_as_single_file](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/save_as_single_file) |指示是否将 html 保存为单个文件。<br/>默认值为 false。|
| [show_all_sheets](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/show_all_sheets) |指示保存为单个 html 文件时是否显示所有工作表。|
| [export_page_headers](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_page_headers) |是否导出页眉。|
| [export_page_footers](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_page_footers) |是否导出页眉。|
| [export_hidden_worksheet](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_hidden_worksheet) |是否导出隐藏的工作表内容。默认值为true。|
| [presentation_preference](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/presentation_preference) |指示 html 或 mht 文件是呈现首选项。<br/>默认值为 false。<br/>如果你想获得更漂亮的展示效果，请将该值设置为true。|
| [cell_css_prefix](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/cell_css_prefix) |获取和设置css名称的前缀，默认值为“”。|
| [table_css_id](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/table_css_id) |获取和设置类型css名称的前缀，例如tr，col，td等，它们包含在表格元素中<br/>它具有特定的 TableCssId 属性。默认值为“”。|
| [is_full_path_link](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/is_full_path_link) |指示是否在sheet00x.htm、filelist.xml和tabstrip.htm中使用全路径链接。<br/>默认值为 false。|
| [export_worksheet_css_separately](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_worksheet_css_separately) |是否单独导出工作表css。默认为false。|
| [export_similar_border_style](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_similar_border_style) |当浏览器不支持边框样式时，是否导出类似的边框样式。<br/>如果要将html或mht文件导入excel，请保留默认值。<br/>默认值为 false。|
| [merge_empty_td_forcely](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/merge_empty_td_forcely) |指示导出文件为html时是否强制合并空TD元素。<br/>设置值为 true 后，html 文件的大小将显着减小。默认值为 false。<br/>如果您想将html文件导入excel或在将文件保存为html时导出完美的网格线，<br/>请保留默认值。|
| [merge_empty_td_type](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/merge_empty_td_type) |指示以 html 格式保存 Excel 文件时是否会以与 MS Excel 相同的方式合并空 TD 元素。<br/>默认值为 MergeEmptyTdType.Default。|
| [export_cell_coordinate](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_cell_coordinate) |指示将文件保存为 html 时是否导出非空白单元格的 Excel 坐标。默认值为 false。<br/>如果要将输出html导入excel，请保留默认值。|
| [export_extra_headings](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_extra_headings) |当文本长度超过最大显示列数时是否导出额外标题。<br/>默认值为 false。如果要将html文件导入excel，请保留默认值。|
| [export_headings](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_headings) |指示保存到 HTML 文件时是否导出工作表的行标题和列标题。|
| [export_row_column_headings](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_row_column_headings) |指示保存到 HTML 文件时是否导出工作表的行标题和列标题。|
| [export_formula](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_formula) |指示保存文件到html时是否导出公式。默认值是true。<br/>如果要将输出html导入excel，请保留默认值。|
| [add_tooltip_text](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/add_tooltip_text) |数据无法完全显示时是否添加提示文本。<br/>默认值为 false。|
| [export_grid_lines](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_grid_lines) |是否导出网格线，默认为false。|
| [export_bogus_row_data](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_bogus_row_data) |是否导出伪造的底行数据。默认值为true。如果要导入html或mht文件<br/>为了更好，请保留默认值。|
| [exclude_unused_styles](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/exclude_unused_styles) |指示是否排除未使用的样式。<br/>对于生成的html文件，排除未使用的样式可以使文件体积更小<br/>不影响视觉效果。所以这个属性的默认值为true。<br/>如果用户需要为生成的html保留工作簿中的所有样式（例如用户的场景）<br/>稍后需要从生成的 html 恢复工作簿），请将此属性设置为 false。|
| [export_document_properties](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_document_properties) |表示是否导出文档属性。默认值为true。如果要导入<br/>html或mht文件到excel，请保留默认值。|
| [export_worksheet_properties](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_worksheet_properties) |是否导出工作表属性。默认值为true。如果要导入<br/>html或mht文件到excel，请保留默认值。|
| [export_workbook_properties](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_workbook_properties) |是否导出工作簿属性。默认值为true。如果要导入<br/>html或mht文件到excel，请保留默认值。|
| [export_frame_scripts_and_properties](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_frame_scripts_and_properties) |指示是否导出框架脚本和文档属性。默认值为true。如果要导入html或mht文件<br/>为了更好，请保留默认值。|
| [export_data_options](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_data_options) |导出html文件数据的规则，默认为全部。|
| [link_target_type](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/link_target_type) |指示`<a>`链接中目标属性的类型。默认值为 HtmlLinkTargetType.Parent。|
| [is_ie_compatible](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/is_ie_compatible) |指示输出HTML是否兼容IE浏览器。<br/>默认值为 false|
| [format_data_ignore_column_width](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/format_data_ignore_column_width) |指示溢出列时是否显示单元格的全部格式化数据。<br/>如果为 true，则忽略列宽，并且将导出单元格的整个数据。<br/>如果为 false，则数据将以与 Excel 相同的方式导出。<br/>默认值为 false。|
| [calculate_formula](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/calculate_formula) |指示是否在保存 html 文件之前计算公式。|
| [is_js_browser_compatible](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/is_js_browser_compatible) |指示 JavaScript 是否与不支持 JavaScript 的浏览器兼容。<br/>默认值是true。|
| [is_mobile_compatible](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/is_mobile_compatible) |指示输出HTML是否与移动设备兼容。<br/>默认值为 false。|
| [css_styles](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/css_styles) |获取或设置格式化程序的附加 css 样式。<br/>仅当 [`HtmlSaveOptions.save_as_single_file`](/cells/python-net/zh/aspose.cells/htmlsaveoptions#save_as_single_file) 为 True 时才有效。<br/><br/> CssStyles =“正文{填充：5px}”；|



### 也可以看看
* 模块[`aspose.cells.saving`](..)
* 类 [`EbookSaveOptions`](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions)
* 类 [`HtmlSaveOptions`](/cells/python-net/zh/aspose.cells/htmlsaveoptions)
* 类 [`SaveOptions`](/cells/python-net/zh/aspose.cells/saveoptions)
