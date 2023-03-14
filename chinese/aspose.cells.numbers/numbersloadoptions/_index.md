---
title: NumbersLoadOptions类
second_title: Aspose.Cells for Python via .NET API 参考资料
description:
type: docs
weight: 10
url: /zh/aspose.cells.numbers/numbersloadoptions/
is_root: false
---
## NumbersLoadOptions类
表示加载 Apple Numbers 文件的选项。



**继承：** [NumbersLoadOptions](/cells/python-net/aspose.cells.numbers/numbersloadoptions) → 
[LoadOptions](/cells/python-net/zh/aspose.cells/loadoptions)



NumbersLoadOptions 类型公开了以下成员：

### 构造器
|构造器|描述|
| :- | :- |
| [NumbersLoadOptions()](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/__init__/#) |构造函数。|


### 特性
|属性|描述|
| :- | :- |
| [load_format](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/load_format) |获取加载格式。|
| [password](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/password) |获取和设置工作簿的密码。|
| [parsing_formula_on_open](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/parsing_formula_on_open) |表示读取文件时是否解析公式。|
| [parsing_pivot_cached_records](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/parsing_pivot_cached_records) |指示加载文件时是否解析枢轴缓存记录。<br/>默认值为假。|
| [language_code](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/language_code) |获取或设置基于已保存文件的 CountryCode 的 Workbook 版本的用户界面语言。|
| [region](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/region) |获取或设置加载文件时基于 CountryCode 的系统区域设置。|
| [default_style_settings](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/default_style_settings) |获取用于初始化工作簿样式的默认样式设置|
| [standard_font](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/standard_font) |设置默认标准字体名称|
| [standard_font_size](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/standard_font_size) |设置默认标准字体大小。|
| [interrupt_monitor](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/interrupt_monitor) |获取和设置中断监视器。|
| [ignore_not_printed](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/ignore_not_printed) |直接打印文件忽略不打印的数据|
| [check_data_valid](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/check_data_valid) |检查模板文件中的数据是否有效。|
| [check_excel_restriction](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/check_excel_restriction) |用户修改单元格相关对象时是否检查excel文件的限制。<br/>例如，excel 不允许输入超过 32K 的字符串值。<br/>当您输入一个大于 32K 的值时，例如 Cell.PutValue(string)，如果此属性为真，您将得到一个异常。<br/>如果此属性为 false，我们将接受您输入的字符串值作为单元格的值，以便稍后<br/>您可以输出其他文件格式的完整字符串值，例如 CSV。<br/>但是，如果您设置了这种对 excel 文件格式无效的值，<br/>您以后不应将工作簿另存为 excel 文件格式。否则生成的excel文件可能会出现意外错误。|
| [keep_unparsed_data](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/keep_unparsed_data) |从模板文件加载工作簿时，是否将未解析的数据保留在内存中。默认为真。|
| [load_filter](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/load_filter) |表示如何加载数据的过滤器。|
| [light_cells_data_handler](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/light_cells_data_handler) |读取模板文件时处理单元格数据的数据处理器。|
| [memory_setting](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/memory_setting) |获取或设置内存使用选项。|
| [warning_callback](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/warning_callback) |获取或设置警告回调。|
| [auto_fitter_options](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/auto_fitter_options) |获取和设置自动装配选项|
| [auto_filter](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/auto_filter) |指示加载文件时是否自动过滤数据。|
| [font_configs](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/font_configs) |获取和设置单独的字体配置。<br/>仅适用于使用此 [LoadOptions](/cells/python-net/zh/aspose.cells/loadoptions) 加载的 [Workbook](/cells/python-net/zh/aspose.cells/workbook)。|
| [load_table_type](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/load_table_type) |获取和设置在一个工作表中加载多个表的类型。|


### 方法
|方法|描述|
| :- | :- |
| [set_paper_size(type)](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions/set_paper_size/#PaperSizeType) |从默认打印机设置中设置默认打印纸张尺寸。|



### 也可以看看
* 模块 [aspose.cells.numbers](..)
* 类 [LoadOptions](/cells/python-net/zh/aspose.cells/loadoptions)
* 类 [NumbersLoadOptions](/cells/python-net/zh/aspose.cells.numbers/numbersloadoptions)
* 类 [Workbook](/cells/python-net/zh/aspose.cells/workbook)
