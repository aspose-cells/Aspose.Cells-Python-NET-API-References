---
title: DbfLoadOptions类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 10
url: /zh/aspose.cells.loading/dbfloadoptions/
is_root: false
---
## DbfLoadOptions类
表示加载.dbf文件的选项。



**继承：** [`DbfLoadOptions`](/cells/python-net/aspose.cells.loading/dbfloadoptions) → 
[`LoadOptions`](/cells/python-net/zh/aspose.cells/loadoptions)



DbfLoadOptions 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions/__init__/#) |选项。|


### 属性
|属性|描述|
| :- | :- |
| [load_format](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions/load_format) |获取加载格式。|
| [password](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions/password) |获取和设置工作簿的密码。|
| [parsing_formula_on_open](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions/parsing_formula_on_open) |指示读取文件时是否解析公式。|
| [parsing_pivot_cached_records](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions/parsing_pivot_cached_records) |指示在加载文件时是否解析数据透视表缓存记录。<br/>默认值为 false。|
| [language_code](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions/language_code) |根据保存文件的国家/地区代码获取或设置工作簿版本的用户界面语言。|
| [region](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions/region) |获取或设置将要加载的工作簿所使用的区域设置。|
| [default_style_settings](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions/default_style_settings) |获取初始化工作簿样式的默认样式设置|
| [standard_font](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions/standard_font) |设置默认标准字体名称|
| [standard_font_size](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions/standard_font_size) |设置默认标准字体大小。|
| [ignore_not_printed](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions/ignore_not_printed) |如果直接打印文件，则忽略未打印的数据|
| [check_data_valid](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions/check_data_valid) |检查模板文件中的数据是否有效。|
| [check_excel_restriction](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions/check_excel_restriction) |当用户修改单元格相关对象时是否检查Excel文件的限制。<br/>例如，excel不允许输入长度超过32K的字符串值。<br/>当您输入一个长度超过 32K 的值（例如 Cell.PutValue(string)）时，如果此属性为真，您将收到异常。<br/>如果此属性为 false，我们将接受您输入的字符串值作为单元格的值，以便稍后<br/>您可以输出其他文件格式的完整字符串值，例如 CSV。<br/>但是，如果您设置了对 Excel 文件格式无效的值，<br/>请勿将工作簿保存为 Excel 文件格式。否则，生成的 Excel 文件可能会出现意外错误。|
| [keep_unparsed_data](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions/keep_unparsed_data) |从模板文件加载工作簿时，是否将未解析的数据保留在内存中。默认值为 true。|
| [load_filter](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions/load_filter) |指示如何加载数据的过滤器。|
| [memory_setting](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions/memory_setting) |获取或设置已加载工作簿的内存模式。|
| [auto_fitter_options](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions/auto_fitter_options) |获取并设置自动适配选项|
| [auto_filter](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions/auto_filter) |指示加载文件时是否自动过滤数据。|
| [font_configs](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions/font_configs) |获取并设置单独的字体配置。<br/>仅适用于使用此 [`LoadOptions`](/cells/python-net/zh/aspose.cells/loadoptions) 加载的 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook)。|
| [ignore_useless_shapes](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions/ignore_useless_shapes) |表示是否忽略无用的形状。|
| [preserve_padding_spaces_in_formula](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions/preserve_padding_spaces_in_formula) |指示是否保留公式标记之间填充的空格和换行符<br/>在获取和设置公式时。<br/>默认值为 false。|


### 方法
|方法|描述|
| :- | :- |
| [`set_paper_size(self, type)`](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions/set_paper_size/#aspose.cells.papersizetype) |从默认打印机设置中设置默认打印纸张尺寸。|



### 也可以看看
* 模块[`aspose.cells.loading`](..)
* 类 [`DbfLoadOptions`](/cells/python-net/zh/aspose.cells.loading/dbfloadoptions)
* 类 [`LoadOptions`](/cells/python-net/zh/aspose.cells/loadoptions)
* 类 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook)
