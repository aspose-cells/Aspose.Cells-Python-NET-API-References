---
title: EbookLoadOptions类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 540
url: /zh/aspose.cells/ebookloadoptions/
is_root: false
---
## EbookLoadOptions类
表示导入电子书文件时的选项。



**遗产：** [`EbookLoadOptions`](/cells/python-net/aspose.cells/ebookloadoptions) → 
[`HtmlLoadOptions`](/cells/python-net/aspose.cells/htmlloadoptions) → 
[`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/zh/aspose.cells/loadoptions)



EbookLoadOptions 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [__init__](/cells/python-net/zh/aspose.cells/ebookloadoptions/__init__/#) |创建加载电子书文件的选项。|
| [__init__](/cells/python-net/zh/aspose.cells/ebookloadoptions/__init__/#aspose.cells.LoadFormat) |创建加载电子书文件的选项。|


### 特性
|属性|描述|
| :- | :- |
| [load_format](/cells/python-net/zh/aspose.cells/ebookloadoptions/load_format) |获取加载格式。|
| [password](/cells/python-net/zh/aspose.cells/ebookloadoptions/password) |获取和设置工作簿的密码。|
| [parsing_formula_on_open](/cells/python-net/zh/aspose.cells/ebookloadoptions/parsing_formula_on_open) |表示读取文件时是否解析公式。|
| [parsing_pivot_cached_records](/cells/python-net/zh/aspose.cells/ebookloadoptions/parsing_pivot_cached_records) |指示加载文件时解析数据透视表是否缓存记录。<br/>默认值为 false。|
| [language_code](/cells/python-net/zh/aspose.cells/ebookloadoptions/language_code) |根据保存文件的 CountryCode 获取或设置 Workbook 版本的用户界面语言。|
| [region](/cells/python-net/zh/aspose.cells/ebookloadoptions/region) |根据加载文件时的 CountryCode 获取或设置系统区域设置。|
| [default_style_settings](/cells/python-net/zh/aspose.cells/ebookloadoptions/default_style_settings) |获取用于初始化工作簿样式的默认样式设置|
| [standard_font](/cells/python-net/zh/aspose.cells/ebookloadoptions/standard_font) |设置默认标准字体名称|
| [standard_font_size](/cells/python-net/zh/aspose.cells/ebookloadoptions/standard_font_size) |设置默认标准字体大小。|
| [interrupt_monitor](/cells/python-net/zh/aspose.cells/ebookloadoptions/interrupt_monitor) |获取和设置中断监视器。|
| [ignore_not_printed](/cells/python-net/zh/aspose.cells/ebookloadoptions/ignore_not_printed) |直接打印文件则忽略未打印的数据|
| [check_data_valid](/cells/python-net/zh/aspose.cells/ebookloadoptions/check_data_valid) |检查模板文件中的数据是否有效。|
| [check_excel_restriction](/cells/python-net/zh/aspose.cells/ebookloadoptions/check_excel_restriction) |用户修改单元格相关对象时是否检查excel文件的限制。<br/>例如，Excel不允许输入超过32K的字符串值。<br/>当您输入超过 32K 的值（例如 Cell.PutValue(string)）时，如果此属性为 true，您将收到异常。<br/>如果此属性为 false，我们将接受您输入的字符串值作为单元格的值，以便稍后<br/>您可以输出其他文件格式的完整字符串值，例如 CSV。<br/>但是，如果您设置了这种对 Excel 文件格式无效的值，<br/>您稍后不应将工作簿另存为 Excel 文件格式。否则生成的 Excel 文件可能会出现意外错误。|
| [keep_unparsed_data](/cells/python-net/zh/aspose.cells/ebookloadoptions/keep_unparsed_data) |从模板文件加载工作簿时，是否将未解析的数据保留在内存中。默认为 true。|
| [load_filter](/cells/python-net/zh/aspose.cells/ebookloadoptions/load_filter) |过滤器表示如何加载数据。|
| [light_cells_data_handler](/cells/python-net/zh/aspose.cells/ebookloadoptions/light_cells_data_handler) |读取模板文件时处理单元格数据的数据处理程序。|
| [memory_setting](/cells/python-net/zh/aspose.cells/ebookloadoptions/memory_setting) |获取或设置内存使用选项。|
| [warning_callback](/cells/python-net/zh/aspose.cells/ebookloadoptions/warning_callback) |获取或设置警告回调。|
| [auto_fitter_options](/cells/python-net/zh/aspose.cells/ebookloadoptions/auto_fitter_options) |获取和设置自动调整器选项|
| [auto_filter](/cells/python-net/zh/aspose.cells/ebookloadoptions/auto_filter) |指示加载文件时是否自动过滤数据。|
| [font_configs](/cells/python-net/zh/aspose.cells/ebookloadoptions/font_configs) |获取和设置单独的字体配置。<br/>仅适用于使用此 [`LoadOptions`](/cells/python-net/zh/aspose.cells/loadoptions) 加载的 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook)。|
| [ignore_useless_shapes](/cells/python-net/zh/aspose.cells/ebookloadoptions/ignore_useless_shapes) |指示是否忽略无用的形状。|
| [preserve_padding_spaces_in_formula](/cells/python-net/zh/aspose.cells/ebookloadoptions/preserve_padding_spaces_in_formula) |指示是否保留公式标记之间填充的空格和换行符<br/>获取和设置公式时。<br/>默认值为 false。|
| [encoding](/cells/python-net/zh/aspose.cells/ebookloadoptions/encoding) |获取和设置默认编码。仅适用于 csv 文件。|
| [load_style_strategy](/cells/python-net/zh/aspose.cells/ebookloadoptions/load_style_strategy) |指示将字符串值转换为数字或日期时间时对解析值应用样式的策略。|
| [convert_numeric_data](/cells/python-net/zh/aspose.cells/ebookloadoptions/convert_numeric_data) |获取或设置一个值，该值指示文本文件中的字符串是否转换为数值数据。|
| [convert_date_time_data](/cells/python-net/zh/aspose.cells/ebookloadoptions/convert_date_time_data) |获取或设置一个值，该值指示文本文件中的字符串是否转换为日期数据。|
| [keep_precision](/cells/python-net/zh/aspose.cells/ebookloadoptions/keep_precision) |表示如果长度为15，是否不解析字符串值。|
| [attached_files_directory](/cells/python-net/zh/aspose.cells/ebookloadoptions/attached_files_directory) |附加文件将保存到的目录。|
| [load_formulas](/cells/python-net/zh/aspose.cells/ebookloadoptions/load_formulas) |原html文件包含公式时是否导入公式|
| [support_div_tag](/cells/python-net/zh/aspose.cells/ebookloadoptions/support_div_tag) |html文件中包含`<div>`标签时是否支持该标签的布局。<br/>默认值为 false。|
| [delete_redundant_spaces](/cells/python-net/zh/aspose.cells/ebookloadoptions/delete_redundant_spaces) |指示文本使用`<br>`标签换行时是否删除多余空格。<br/>默认值为 false。|
| [auto_fit_cols_and_rows](/cells/python-net/zh/aspose.cells/ebookloadoptions/auto_fit_cols_and_rows) |指示是否自动调整列和行。默认值为 false。|
| [convert_formulas_data](/cells/python-net/zh/aspose.cells/ebookloadoptions/convert_formulas_data) |如果为 true，则当字符串值以字符“=”开头时，将字符串转换为公式，默认值为 false。|
| [has_formula](/cells/python-net/zh/aspose.cells/ebookloadoptions/has_formula) |如果文本以“=”开头，则指示文本是否为公式。|
| [stream_provider](/cells/python-net/zh/aspose.cells/ebookloadoptions/stream_provider) |获取或设置用于导入对象的 StreamProviderImportHtmlFile。|
| [prog_id](/cells/python-net/zh/aspose.cells/ebookloadoptions/prog_id) |获取创建文件的程序ID。<br/>仅适用于 MHT 文件。|
| [table_load_options](/cells/python-net/zh/aspose.cells/ebookloadoptions/table_load_options) |获取 HtmlTableLoadOptionCollection 实例|


### 方法
|方法|描述|
| :- | :- |
| [set_paper_size](/cells/python-net/zh/aspose.cells/ebookloadoptions/set_paper_size/#aspose.cells.PaperSizeType) |根据默认打印机设置设置默认打印纸张尺寸。|



### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`AbstractTextLoadOptions`](/cells/python-net/zh/aspose.cells/abstracttextloadoptions)
* 类 [`EbookLoadOptions`](/cells/python-net/zh/aspose.cells/ebookloadoptions)
* 类 [`HtmlLoadOptions`](/cells/python-net/zh/aspose.cells/htmlloadoptions)
* 类 [`LoadOptions`](/cells/python-net/zh/aspose.cells/loadoptions)
* 类 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook)
