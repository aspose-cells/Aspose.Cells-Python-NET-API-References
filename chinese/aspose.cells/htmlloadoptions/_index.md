---
title: HtmlLoadOptions类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 780
url: /zh/aspose.cells/htmlloadoptions/
is_root: false
---
## HtmlLoadOptions类
表示导入 html 文件时的选项。



**继承：** [`HtmlLoadOptions`](/cells/python-net/aspose.cells/htmlloadoptions) → 
[`AbstractTextLoadOptions`](/cells/python-net/aspose.cells/abstracttextloadoptions) → 
[`LoadOptions`](/cells/python-net/zh/aspose.cells/loadoptions)



HtmlLoadOptions 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells/htmlloadoptions/__init__/#) |创建加载文件的选项。|
| [`__init__(self, load_format)`](/cells/python-net/zh/aspose.cells/htmlloadoptions/__init__/#aspose.cells.loadformat) |创建加载文件的选项。|


### 属性
|属性|描述|
| :- | :- |
| [load_format](/cells/python-net/zh/aspose.cells/htmlloadoptions/load_format) |获取加载格式。|
| [password](/cells/python-net/zh/aspose.cells/htmlloadoptions/password) |获取和设置工作簿的密码。|
| [parsing_formula_on_open](/cells/python-net/zh/aspose.cells/htmlloadoptions/parsing_formula_on_open) |指示读取文件时是否解析公式。|
| [parsing_pivot_cached_records](/cells/python-net/zh/aspose.cells/htmlloadoptions/parsing_pivot_cached_records) |指示在加载文件时是否解析数据透视表缓存记录。<br/>默认值为 false。|
| [language_code](/cells/python-net/zh/aspose.cells/htmlloadoptions/language_code) |根据保存文件的国家/地区代码获取或设置工作簿版本的用户界面语言。|
| [region](/cells/python-net/zh/aspose.cells/htmlloadoptions/region) |获取或设置将要加载的工作簿所使用的区域设置。|
| [default_style_settings](/cells/python-net/zh/aspose.cells/htmlloadoptions/default_style_settings) |获取初始化工作簿样式的默认样式设置|
| [standard_font](/cells/python-net/zh/aspose.cells/htmlloadoptions/standard_font) |设置默认标准字体名称|
| [standard_font_size](/cells/python-net/zh/aspose.cells/htmlloadoptions/standard_font_size) |设置默认标准字体大小。|
| [ignore_not_printed](/cells/python-net/zh/aspose.cells/htmlloadoptions/ignore_not_printed) |如果直接打印文件，则忽略未打印的数据|
| [check_data_valid](/cells/python-net/zh/aspose.cells/htmlloadoptions/check_data_valid) |检查模板文件中的数据是否有效。|
| [check_excel_restriction](/cells/python-net/zh/aspose.cells/htmlloadoptions/check_excel_restriction) |当用户修改单元格相关对象时是否检查Excel文件的限制。<br/>例如，excel不允许输入长度超过32K的字符串值。<br/>当您输入一个长度超过 32K 的值（例如 Cell.PutValue(string)）时，如果此属性为真，您将收到异常。<br/>如果此属性为 false，我们将接受您输入的字符串值作为单元格的值，以便稍后<br/>您可以输出其他文件格式的完整字符串值，例如 CSV。<br/>但是，如果您设置了对 Excel 文件格式无效的值，<br/>请勿将工作簿保存为 Excel 文件格式。否则，生成的 Excel 文件可能会出现意外错误。|
| [keep_unparsed_data](/cells/python-net/zh/aspose.cells/htmlloadoptions/keep_unparsed_data) |从模板文件加载工作簿时，是否将未解析的数据保留在内存中。默认值为 true。|
| [load_filter](/cells/python-net/zh/aspose.cells/htmlloadoptions/load_filter) |指示如何加载数据的过滤器。|
| [memory_setting](/cells/python-net/zh/aspose.cells/htmlloadoptions/memory_setting) |获取或设置已加载工作簿的内存模式。|
| [auto_fitter_options](/cells/python-net/zh/aspose.cells/htmlloadoptions/auto_fitter_options) |获取并设置自动适配选项|
| [auto_filter](/cells/python-net/zh/aspose.cells/htmlloadoptions/auto_filter) |指示加载文件时是否自动过滤数据。|
| [font_configs](/cells/python-net/zh/aspose.cells/htmlloadoptions/font_configs) |获取并设置单独的字体配置。<br/>仅适用于使用此 [`LoadOptions`](/cells/python-net/zh/aspose.cells/loadoptions) 加载的 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook)。|
| [ignore_useless_shapes](/cells/python-net/zh/aspose.cells/htmlloadoptions/ignore_useless_shapes) |表示是否忽略无用的形状。|
| [preserve_padding_spaces_in_formula](/cells/python-net/zh/aspose.cells/htmlloadoptions/preserve_padding_spaces_in_formula) |指示是否保留公式标记之间填充的空格和换行符<br/>在获取和设置公式时。<br/>默认值为 false。|
| [encoding](/cells/python-net/zh/aspose.cells/htmlloadoptions/encoding) |获取并设置默认编码。仅适用于 csv 文件。|
| [load_style_strategy](/cells/python-net/zh/aspose.cells/htmlloadoptions/load_style_strategy) |指示将字符串值转换为数字或日期时间时对解析值应用样式的策略。|
| [convert_numeric_data](/cells/python-net/zh/aspose.cells/htmlloadoptions/convert_numeric_data) |获取或设置一个值，该值指示文本文件中的字符串是否转换为数字数据。|
| [convert_date_time_data](/cells/python-net/zh/aspose.cells/htmlloadoptions/convert_date_time_data) |获取或设置一个值，该值指示文本文件中的字符串是否转换为日期数据。|
| [keep_precision](/cells/python-net/zh/aspose.cells/htmlloadoptions/keep_precision) |指示如果长度为 15 则是否不解析字符串值。|
| [attached_files_directory](/cells/python-net/zh/aspose.cells/htmlloadoptions/attached_files_directory) |附加文件将保存到的目录。|
| [load_formulas](/cells/python-net/zh/aspose.cells/htmlloadoptions/load_formulas) |指示如果原始 html 文件包含公式，是否导入公式|
| [support_div_tag](/cells/python-net/zh/aspose.cells/htmlloadoptions/support_div_tag) |html文件包含`<div>`标签时，是否支持该标签的布局。<br/>默认值为 false。|
| [delete_redundant_spaces](/cells/python-net/zh/aspose.cells/htmlloadoptions/delete_redundant_spaces) |使用`<br>`标签表示文本换行时是否删除多余的空格。<br/>默认值为 false。|
| [auto_fit_cols_and_rows](/cells/python-net/zh/aspose.cells/htmlloadoptions/auto_fit_cols_and_rows) |是否自动调整行列大小，默认值为 false。|
| [convert_formulas_data](/cells/python-net/zh/aspose.cells/htmlloadoptions/convert_formulas_data) |如果为真，则当字符串值以字符“=”开头时，将字符串转换为公式，默认值为假。|
| [has_formula](/cells/python-net/zh/aspose.cells/htmlloadoptions/has_formula) |如果文本以“=”开头，则表示文本是否为公式。|
| [prog_id](/cells/python-net/zh/aspose.cells/htmlloadoptions/prog_id) |获取创建文件的程序 ID。<br/>仅适用于 MHT 文件。|
| [table_load_options](/cells/python-net/zh/aspose.cells/htmlloadoptions/table_load_options) |获取 HtmlTableLoadOptionCollection 实例|


### 方法
|方法|描述|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/zh/aspose.cells/htmlloadoptions/set_paper_size/#aspose.cells.papersizetype) |从默认打印机设置中设置默认打印纸张尺寸。|



### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`AbstractTextLoadOptions`](/cells/python-net/zh/aspose.cells/abstracttextloadoptions)
* 类 [`HtmlLoadOptions`](/cells/python-net/zh/aspose.cells/htmlloadoptions)
* 类 [`LoadOptions`](/cells/python-net/zh/aspose.cells/loadoptions)
* 类 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook)
