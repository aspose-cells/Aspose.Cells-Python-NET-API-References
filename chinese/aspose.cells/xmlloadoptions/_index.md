---
title: XmlLoadOptions类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1760
url: /zh/aspose.cells/xmlloadoptions/
is_root: false
---
## XmlLoadOptions类
代表加载xml的选项。



**遗产：** [`XmlLoadOptions`](/cells/python-net/aspose.cells/xmlloadoptions) → 
[`LoadOptions`](/cells/python-net/zh/aspose.cells/loadoptions)



XmlLoadOptions 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [__init__](/cells/python-net/zh/aspose.cells/xmlloadoptions/__init__/#) |代表加载xml文件的选项。|
| [__init__](/cells/python-net/zh/aspose.cells/xmlloadoptions/__init__/#aspose.cells.LoadFormat) |代表加载xml文件的选项。|


### 特性
|属性|描述|
| :- | :- |
| [load_format](/cells/python-net/zh/aspose.cells/xmlloadoptions/load_format) |获取加载格式。|
| [password](/cells/python-net/zh/aspose.cells/xmlloadoptions/password) |获取和设置工作簿的密码。|
| [parsing_formula_on_open](/cells/python-net/zh/aspose.cells/xmlloadoptions/parsing_formula_on_open) |表示读取文件时是否解析公式。|
| [parsing_pivot_cached_records](/cells/python-net/zh/aspose.cells/xmlloadoptions/parsing_pivot_cached_records) |指示加载文件时解析数据透视表是否缓存记录。<br/>默认值为 false。|
| [language_code](/cells/python-net/zh/aspose.cells/xmlloadoptions/language_code) |根据保存文件的 CountryCode 获取或设置 Workbook 版本的用户界面语言。|
| [region](/cells/python-net/zh/aspose.cells/xmlloadoptions/region) |根据加载文件时的 CountryCode 获取或设置系统区域设置。|
| [default_style_settings](/cells/python-net/zh/aspose.cells/xmlloadoptions/default_style_settings) |获取用于初始化工作簿样式的默认样式设置|
| [standard_font](/cells/python-net/zh/aspose.cells/xmlloadoptions/standard_font) |设置默认标准字体名称|
| [standard_font_size](/cells/python-net/zh/aspose.cells/xmlloadoptions/standard_font_size) |设置默认标准字体大小。|
| [interrupt_monitor](/cells/python-net/zh/aspose.cells/xmlloadoptions/interrupt_monitor) |获取和设置中断监视器。|
| [ignore_not_printed](/cells/python-net/zh/aspose.cells/xmlloadoptions/ignore_not_printed) |直接打印文件则忽略未打印的数据|
| [check_data_valid](/cells/python-net/zh/aspose.cells/xmlloadoptions/check_data_valid) |检查模板文件中的数据是否有效。|
| [check_excel_restriction](/cells/python-net/zh/aspose.cells/xmlloadoptions/check_excel_restriction) |用户修改单元格相关对象时是否检查excel文件的限制。<br/>例如，Excel不允许输入超过32K的字符串值。<br/>当您输入超过 32K 的值（例如 Cell.PutValue(string)）时，如果此属性为 true，您将收到异常。<br/>如果此属性为 false，我们将接受您输入的字符串值作为单元格的值，以便稍后<br/>您可以输出其他文件格式的完整字符串值，例如 CSV。<br/>但是，如果您设置了这种对 Excel 文件格式无效的值，<br/>您稍后不应将工作簿另存为 Excel 文件格式。否则生成的 Excel 文件可能会出现意外错误。|
| [keep_unparsed_data](/cells/python-net/zh/aspose.cells/xmlloadoptions/keep_unparsed_data) |从模板文件加载工作簿时，是否将未解析的数据保留在内存中。默认为 true。|
| [load_filter](/cells/python-net/zh/aspose.cells/xmlloadoptions/load_filter) |过滤器表示如何加载数据。|
| [light_cells_data_handler](/cells/python-net/zh/aspose.cells/xmlloadoptions/light_cells_data_handler) |读取模板文件时处理单元格数据的数据处理程序。|
| [memory_setting](/cells/python-net/zh/aspose.cells/xmlloadoptions/memory_setting) |获取或设置内存使用选项。|
| [warning_callback](/cells/python-net/zh/aspose.cells/xmlloadoptions/warning_callback) |获取或设置警告回调。|
| [auto_fitter_options](/cells/python-net/zh/aspose.cells/xmlloadoptions/auto_fitter_options) |获取和设置自动调整器选项|
| [auto_filter](/cells/python-net/zh/aspose.cells/xmlloadoptions/auto_filter) |指示加载文件时是否自动过滤数据。|
| [font_configs](/cells/python-net/zh/aspose.cells/xmlloadoptions/font_configs) |获取和设置单独的字体配置。<br/>仅适用于使用此 [`LoadOptions`](/cells/python-net/zh/aspose.cells/loadoptions) 加载的 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook)。|
| [ignore_useless_shapes](/cells/python-net/zh/aspose.cells/xmlloadoptions/ignore_useless_shapes) |指示是否忽略无用的形状。|
| [preserve_padding_spaces_in_formula](/cells/python-net/zh/aspose.cells/xmlloadoptions/preserve_padding_spaces_in_formula) |指示是否保留公式标记之间填充的空格和换行符<br/>获取和设置公式时。<br/>默认值为 false。|
| [start_cell](/cells/python-net/zh/aspose.cells/xmlloadoptions/start_cell) |获取和设置起始单元格。|
| [is_xml_map](/cells/python-net/zh/aspose.cells/xmlloadoptions/is_xml_map) |指示是否将 xml 映射到 Excel。<br/>默认值为 false。|
| [contains_multiple_worksheets](/cells/python-net/zh/aspose.cells/xmlloadoptions/contains_multiple_worksheets) |指示是否将 xml 作为多个工作表导入。|
| [convert_numeric_or_date](/cells/python-net/zh/aspose.cells/xmlloadoptions/convert_numeric_or_date) |指示是否将 xml 文件中的值转换为数字或日期。|
| [number_format](/cells/python-net/zh/aspose.cells/xmlloadoptions/number_format) |获取和设置数值的格式。|
| [date_format](/cells/python-net/zh/aspose.cells/xmlloadoptions/date_format) |获取和设置日期值的格式。|
| [ignore_root_attributes](/cells/python-net/zh/aspose.cells/xmlloadoptions/ignore_root_attributes) |指示是否忽略根元素的属性。|


### 方法
|方法|描述|
| :- | :- |
| [set_paper_size](/cells/python-net/zh/aspose.cells/xmlloadoptions/set_paper_size/#aspose.cells.PaperSizeType) |根据默认打印机设置设置默认打印纸张尺寸。|



### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`LoadOptions`](/cells/python-net/zh/aspose.cells/loadoptions)
* 类 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook)
* 类 [`XmlLoadOptions`](/cells/python-net/zh/aspose.cells/xmlloadoptions)
