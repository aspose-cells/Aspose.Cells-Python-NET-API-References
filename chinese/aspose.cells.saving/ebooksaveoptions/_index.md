---
title: EbookSaveOptions类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells.saving/ebooksaveoptions/
is_root: false
---
## EbookSaveOptions类
代表保存电子书文件的选项。



**继承：** [`EbookSaveOptions`](/cells/python-net/aspose.cells.saving/ebooksaveoptions) → 
[`HtmlSaveOptions`](/cells/python-net/aspose.cells/htmlsaveoptions) → 
[`SaveOptions`](/cells/python-net/zh/aspose.cells/saveoptions)



EbookSaveOptions 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/__init__/#) |创建用于保存电子书文件的选项。|
| [`__init__(self, save_format)`](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/__init__/#aspose.cells.saveformat) |创建用于保存电子书文件的选项。|


### 属性
|属性|描述|
| :- | :- |
| [save_format](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/save_format) |获取保存文件格式。|
| [clear_data](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/clear_data) |保存文件后将工作簿清空。|
| [cached_file_folder](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/cached_file_folder) |可用作数据缓存的临时文件的文件夹。|
| [validate_merged_areas](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/validate_merged_areas) |指示在保存文件之前是否验证合并的单元格。|
| [merge_areas](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/merge_areas) |指示在保存文件之前是否合并条件格式和验证的区域。|
| [create_directory](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/create_directory) |如果为 true 并且目录不存在，则在保存文件之前会自动创建目录。|
| [sort_names](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/sort_names) |表示在保存文件之前是否对定义的名称进行排序。|
| [sort_external_names](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/sort_external_names) |表示在保存文件之前是否对外部定义的名称进行排序。|
| [refresh_chart_cache](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/refresh_chart_cache) |是否刷新图表缓存数据|
| [check_excel_restriction](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/check_excel_restriction) |当用户修改单元格相关对象时是否检查Excel文件的限制。<br/>例如，excel不允许输入长度超过32K的字符串值。<br/>当您输入的值超过 32K 时，它将被截断。|
| [update_smart_art](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/update_smart_art) |指示是否更新智能艺术设置。<br/>默认值为 false。|
| [encrypt_document_properties](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/encrypt_document_properties) |指示保存为 .xls 文件时是否加密文档属性。<br/>默认值为 true。|
| [ignore_invisible_shapes](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/ignore_invisible_shapes) |指示是否导出那些不可见的形状|
| [page_title](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/page_title) |HTML 页面的标题。<br/>仅用于保存到 html 流。|
| [attached_files_directory](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/attached_files_directory) |附加文件将保存到的目录。<br/>仅用于保存到 html 流。|
| [attached_files_url_prefix](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/attached_files_url_prefix) |在 html 文件中指定附加文件（例如图像）的 Url 前缀。<br/>仅用于保存到 html 流。|
| [default_font_name](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/default_font_name) |指定导出html的默认字体名称，当style的字体不存在时，将使用默认字体，<br/>如果此属性为空，Aspose.Cells 将使用与原始字体具有相同系列的通用字体，<br/>默认值为空。|
| [add_generic_font](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/add_generic_font) |指示是否向 CSS 字体系列添加通用字体。<br/>默认值为 true|
| [worksheet_scalable](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/worksheet_scalable) |指示在将文件保存为 html 时是否通过工作表缩放级别放大或缩小 html，默认值为 false。|
| [is_export_comments](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/is_export_comments) |表示保存文件为html时是否导出注意事项，默认值为false。|
| [export_comments_type](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_comments_type) |表示将注意事项导出到 html 文件的类型。|
| [disable_downlevel_revealed_comments](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/disable_downlevel_revealed_comments) |表示在导出文件为 html 时是否禁用 Downlevel-revealed 条件注释，默认值为 false。|
| [is_exp_image_to_temp_dir](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/is_exp_image_to_temp_dir) |指示是否将图像文件导出到临时目录。<br/>仅用于保存到 html 流。|
| [image_scalable](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/image_scalable) |是否使用可缩放单位描述图像宽度<br/>当使用可缩放单位来描述列宽时。<br/>默认值为 true。|
| [width_scalable](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/width_scalable) |指示是否将以比例为单位的列宽导出到 html。<br/>默认值为 false。|
| [export_single_tab](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_single_tab) |指示当文件只有一个工作表时是否导出单个标签。<br/>默认值为 false。|
| [export_images_as_base64](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_images_as_base64) |指定图像是否以 Base64 格式保存为 HTML、MHTML 或 EPUB。|
| [export_active_worksheet_only](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_active_worksheet_only) |指示是否仅将活动工作表导出为 html 文件。<br/>如果为真，则只有活动工作表将被导出到 html 文件；<br/>如果为假，则整个工作簿将被导出为 html 文件。<br/>默认值为 false。|
| [export_print_area_only](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_print_area_only) |是否仅将打印区域导出到 html 文件。默认值为 false。|
| [export_area](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_area) |获取或设置当前活动工作表的导出 CellArea。<br/>如果设置此属性，则当前活动工作表的打印区域将被省略。<br/>将文件保存为 html 时，只会导出指定区域。|
| [parse_html_tag_in_cell](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/parse_html_tag_in_cell) |指示单元格中的 html 标签（例如 `<div></div>`）是否应解析为单元格值或按原样保留。<br/>默认值为 true。|
| [html_cross_string_type](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/html_cross_string_type) |指示在以 html 格式保存 Excel 文件时跨单元格字符串是否以与 MS Excel 相同的方式显示。<br/>默认情况下该值为默认值，因此，对于跨单元格字符串，Aspose.Cells 和 MS Excel 创建的 html 文件之间几乎没有区别。<br/>但是对于创建大型 html 文件的性能，将值设置为 Cross 会比将其设置为 Default 或 Fit2Cell 快几倍。|
| [hidden_col_display_type](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/hidden_col_display_type) | excel 中的隐藏列（此列的宽度为 0），在将其保存为 html 格式之前，<br/>如果HtmlHiddenColDisplayType为“Remove”，则隐藏列将不会输出，<br/>如果值为“Hidden”，则该列会被输出，但被隐藏，默认值为“Hidden”|
| [hidden_row_display_type](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/hidden_row_display_type) | excel 中的隐藏行（此行的高度为 0），在将其保存为 html 格式之前，<br/>如果HtmlHiddenRowDisplayType为“Remove”，则隐藏行将不会输出，<br/>如果值为“Hidden”，则该行会被输出，但被隐藏，默认值为“Hidden”|
| [encoding](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/encoding) |如果未设置，则使用 Encoding.UTF8 作为默认编码类型。|
| [image_options](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/image_options) |导出前获取 ImageOrPrintOptions 对象|
| [save_as_single_file](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/save_as_single_file) |指示是否将 html 保存为单个文件。<br/>默认值为 false。|
| [show_all_sheets](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/show_all_sheets) |指示保存为单个 html 文件时是否显示所有工作表。|
| [export_page_headers](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_page_headers) |指示是否导出页眉。|
| [export_page_footers](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_page_footers) |指示是否导出页眉。|
| [export_hidden_worksheet](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_hidden_worksheet) |是否导出隐藏的工作表内容。默认值为true。|
| [presentation_preference](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/presentation_preference) |指示 html 或 mht 文件是否为演示首选项。<br/>默认值为 false。<br/>如果想要获得更美观的呈现效果，请将该值设置为 true。|
| [cell_css_prefix](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/cell_css_prefix) |获取或设置css名称的前缀，默认值为“”。|
| [table_css_id](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/table_css_id) |获取并设置类型 css 名称的前缀，例如 tr、col、td 等，它们包含在 table 元素中<br/>具有特定的 TableCssId 属性。默认值为 ""。|
| [is_full_path_link](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/is_full_path_link) |指示sheet00x.htm、filelist.xml和tabstrip.htm中是否使用完整路径链接。<br/>默认值为 false。|
| [export_worksheet_css_separately](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_worksheet_css_separately) |是否单独导出工作表css。默认为false。|
| [export_similar_border_style](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_similar_border_style) |当浏览器不支持该边框样式时，指示是否导出类似的边框样式。<br/>如果要将html或mht文件导入excel，请保留默认值。<br/>默认值为 false。|
| [merge_empty_td_forcely](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/merge_empty_td_forcely) |指定导出文件为html时是否强制合并空的TD元素。<br/>设置为 true 后，html 文件的大小会明显减小，默认值为 false。<br/>如果您想将 html 文件导入到 excel 或在将文件保存为 html 时导出完美的网格线，<br/>请保留默认值。|
| [merge_empty_td_type](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/merge_empty_td_type) |合并连续空单元格（空 td 元素）的选项<br/>默认值为 MergeEmptyTdType.Default。|
| [export_cell_coordinate](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_cell_coordinate) |指定保存为 HTML 格式时是否导出 Excel 中非空白单元格的坐标。默认值为 false。<br/>如果要将输出的html导入到excel中，请保留默认值。|
| [export_extra_headings](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_extra_headings) |指示当文本长度超过最大显示列时是否导出额外的标题。<br/>默认值为false，如果要将html文件导入excel，请保持默认值。|
| [export_headings](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_headings) |指示在保存到 HTML 文件时是否导出工作表的行和列标题。|
| [export_row_column_headings](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_row_column_headings) |指示在保存到 HTML 文件时是否导出工作表的行和列标题。|
| [export_formula](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_formula) |保存为 html 文件时是否导出公式，默认值为 true。<br/>如果要将输出的html导入到excel中，请保留默认值。|
| [add_tooltip_text](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/add_tooltip_text) |指示当数据无法完全显示时是否添加工具提示文本。<br/>默认值为 false。|
| [export_grid_lines](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_grid_lines) |是否导出网格线。默认为false。|
| [export_bogus_row_data](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_bogus_row_data) |是否导出伪造的底行数据，默认为 true。如果要导入 html 或 mht 文件<br/>若要excel，请保留默认值。|
| [exclude_unused_styles](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/exclude_unused_styles) |指示是否排除未使用的样式。<br/>对于生成的html文件，排除未使用的样式可以使文件大小更小<br/>而不影响视觉效果。所以该属性的默认值为true。<br/>如果用户需要保留工作簿中生成的 html 的所有样式（例如用户<br/>如果稍后需要从生成的html中恢复工作簿），请将此属性设置为false。|
| [export_document_properties](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_document_properties) |指示是否导出文档属性。默认值为 true。如果要导入<br/>html或mht文件转换为excel，请保留默认值。|
| [export_worksheet_properties](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_worksheet_properties) |是否导出工作表属性。默认值为 true。如果要导入<br/>html或mht文件转换为excel，请保留默认值。|
| [export_workbook_properties](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_workbook_properties) |指示是否导出工作簿属性。默认值为 true。如果要导入<br/>html或mht文件转换为excel，请保留默认值。|
| [export_frame_scripts_and_properties](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_frame_scripts_and_properties) |是否导出框架脚本和文档属性，默认值为 true。如果要导入 html 或 mht 文件<br/>若要excel，请保留默认值。|
| [export_data_options](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/export_data_options) |导出html文件数据的规则，默认为All。|
| [link_target_type](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/link_target_type) |指示 `<a>` 链接中的目标属性类型。默认值为 HtmlLinkTargetType.Parent。|
| [is_ie_compatible](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/is_ie_compatible) |指示输出HTML是否与IE浏览器兼容。<br/>默认值为 false|
| [format_data_ignore_column_width](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/format_data_ignore_column_width) |指示当溢出列时是否显示单元格的完整格式化数据。<br/>如果为真，则忽略列宽并导出单元格的整个数据。<br/>如果为假，则数据将以与 Excel 相同的方式导出。<br/>默认值为 false。|
| [calculate_formula](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/calculate_formula) |指示在保存 html 文件之前是否计算公式。|
| [is_js_browser_compatible](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/is_js_browser_compatible) |指示 JavaScript 是否与不支持 JavaScript 的浏览器兼容。<br/>默认值为 true。|
| [is_mobile_compatible](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/is_mobile_compatible) |指示输出 HTML 是否与移动设备兼容。<br/>默认值为 false。|
| [css_styles](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/css_styles) |获取或设置格式化程序的附加 CSS 样式。<br/>仅当 [`HtmlSaveOptions.save_as_single_file`](/cells/python-net/zh/aspose.cells/htmlsaveoptions#save_as_single_file) 为 True 时才有效。<br/><br/> CssStyles="body {padding: 5px}";|
| [hide_overflow_wrapped_text](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/hide_overflow_wrapped_text) |指示当单元格格式设置为自动换行时是否隐藏溢出文本。<br/>默认值为 false|
| [is_border_collapsed](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/is_border_collapsed) |指示表格边框是否折叠。<br/>默认值为 true。|
| [encode_entity_as_code](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/encode_entity_as_code) |指示是否将 html 字符实体替换为十进制代码。<br/>（例如，“&nbsp;”被替换为“&#160;”）。<br/>默认值为 false。|
| [office_math_output_mode](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/office_math_output_mode) |指示如何将 OfficeMath 对象导出到 HTML，默认值为图像。|
| [cell_name_attribute](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/cell_name_attribute) |指定指示要写入的 CellName 的属性。<br/>（例如，如果值为“id”，则对于单元格“A1”，输出将为：<td id='A1'>).<br/>默认值为空。|
| [disable_css](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/disable_css) |指示是否仅应用内联样式，而不依赖 CSS。<br/>默认值为 false。|
| [enable_css_custom_properties](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/enable_css_custom_properties) |使用 CSS 自定义属性优化 html 的输出。例如，对于同一幅 base64 图片出现多次的情况，使用自定义属性可以使图片数据仅保存一次，从而提升最终 html 的性能。<br/>默认值为 false。|
| [html_version](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/html_version) |指定保存 HTML 格式时应使用的 HTML 标准的版本。<br/>默认值是 HtmlVersion.Default。|
| [sheet_set](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions/sheet_set) |获取或设置要渲染的工作表。默认值为工作簿中所有可见的工作表：[`SheetSet.visible`](/cells/python-net/zh/aspose.cells.rendering/sheetset#visible)。|



### 也可以看看
* 模块[`aspose.cells.saving`](..)
* 类 [`EbookSaveOptions`](/cells/python-net/zh/aspose.cells.saving/ebooksaveoptions)
* 类 [`HtmlSaveOptions`](/cells/python-net/zh/aspose.cells/htmlsaveoptions)
* 类 [`SaveOptions`](/cells/python-net/zh/aspose.cells/saveoptions)
