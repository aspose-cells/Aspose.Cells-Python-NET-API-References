---
title: CellsHelper类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 210
url: /zh/aspose.cells/cellshelper/
is_root: false
---
## CellsHelper类
提供帮助功能。



CellsHelper 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [significant_digits](/cells/python-net/zh/aspose.cells/cellshelper/significant_digits) |获取并设置有效数字的数量。<br/>默认值为 17。|
| [dpi](/cells/python-net/zh/aspose.cells/cellshelper/dpi) |获取机器的DPI。|
| [startup_path](/cells/python-net/zh/aspose.cells/cellshelper/startup_path) |获取或设置启动路径，供一些外部公式引用使用。|
| [alt_start_path](/cells/python-net/zh/aspose.cells/cellshelper/alt_start_path) |获取或设置备用启动路径，由一些外部公式引用引用。|
| [library_path](/cells/python-net/zh/aspose.cells/cellshelper/library_path) |获取或设置一些外部公式引用所引用的库路径。|
| [custom_implementation_factory](/cells/python-net/zh/aspose.cells/cellshelper/custom_implementation_factory) |获取或设置用于创建具有特殊实现的实例的工厂。|
| [is_cloud_platform](/cells/python-net/zh/aspose.cells/cellshelper/is_cloud_platform) |在云平台上运行时请设置此属性为 True，例如：Azure、AWSLambda 等，|


### 方法
|方法|描述|
| :- | :- |
| [`create_safe_sheet_name(, name_proposal)`](/cells/python-net/zh/aspose.cells/cellshelper/create_safe_sheet_name/#str) |检查给定的工作表名称并在需要时创建一个有效的工作表名称。<br/>如果给定的 Sheet 名称符合 Excel Sheet 名称规则，则返回该名称。<br/>否则，如果长度超过限制，字符串将被截断<br/>并且无效字符将被替换为' '，然后返回重建的字符串值。|
| [`create_safe_sheet_name(, name_proposal, replace_char)`](/cells/python-net/zh/aspose.cells/cellshelper/create_safe_sheet_name/#str-char) |检查给定的工作表名称并在需要时创建一个有效的工作表名称。<br/>如果给定的 Sheet 名称符合 Excel Sheet 名称规则，则返回该名称。<br/>否则，如果长度超过限制，字符串将被截断<br/>无效字符将被给定的字符替换，然后返回重建的字符串值。|
| [`get_text_width(, text, font, scaling)`](/cells/python-net/zh/aspose.cells/cellshelper/get_text_width/#str-aspose.cells.font-float) |以点为单位获取文本的宽度。|
| [`get_version()`](/cells/python-net/zh/aspose.cells/cellshelper/get_version/#) |获取发布版本。|
| [`cell_name_to_index(, cell_name, row, column)`](/cells/python-net/zh/aspose.cells/cellshelper/cell_name_to_index/#str-any-any) |根据单元格名称获取单元格行和列索引。|
| [`cell_index_to_name(, row, column)`](/cells/python-net/zh/aspose.cells/cellshelper/cell_index_to_name/#int-int) |根据行和列索引获取单元格名称。|
| [`column_index_to_name(, column)`](/cells/python-net/zh/aspose.cells/cellshelper/column_index_to_name/#int) |根据列索引获取列名。|
| [`column_name_to_index(, column_name)`](/cells/python-net/zh/aspose.cells/cellshelper/column_name_to_index/#str) |根据列名获取列索引。|
| [`row_index_to_name(, row)`](/cells/python-net/zh/aspose.cells/cellshelper/row_index_to_name/#int) |根据行索引获取行名。|
| [`row_name_to_index(, row_name)`](/cells/python-net/zh/aspose.cells/cellshelper/row_name_to_index/#str) |根据行名获取行索引。|
| [`convert_r1c1_formula_to_a1(, r_1c1_formula, row, column)`](/cells/python-net/zh/aspose.cells/cellshelper/convert_r1c1_formula_to_a1/#str-int-int) |将单元格的 r1c1 公式转换为 A1 公式。|
| [`convert_a1_formula_to_r1c1(, formula, row, column)`](/cells/python-net/zh/aspose.cells/cellshelper/convert_a1_formula_to_r1c1/#str-int-int) |将单元格的 A1 公式转换为 r1c1 公式。|
| [`get_date_time_from_double(, double_value, date1904)`](/cells/python-net/zh/aspose.cells/cellshelper/get_date_time_from_double/#float-bool) |将双精度值转换为日期时间值。|
| [`get_double_from_date_time(, date_time, date1904)`](/cells/python-net/zh/aspose.cells/cellshelper/get_double_from_date_time/#datetime-bool) |将日期时间转换为双精度值。|
| [`get_used_colors(, workbook)`](/cells/python-net/zh/aspose.cells/cellshelper/get_used_colors/#aspose.cells.workbook) |获取工作簿中使用的所有颜色。|
| [`add_add_in_function(, function, min_count_of_parameters, max_count_of_parameters, paramers_type, function_value_type)`](/cells/python-net/zh/aspose.cells/cellshelper/add_add_in_function/#str-int-int-list-aspose.cells.parametertype) |添加插件功能。|
| [`merge_files(, files, cached_file, dest_file)`](/cells/python-net/zh/aspose.cells/cellshelper/merge_files/#list-str-str) |将一些大的 xls 文件合并为一个 xls 文件。|
| [`get_cache_folder()`](/cells/python-net/zh/aspose.cells/cellshelper/get_cache_folder/#) |获取可用作数据缓存的临时文件的文件夹。|
| [`set_cache_folder(, cache)`](/cells/python-net/zh/aspose.cells/cellshelper/set_cache_folder/#str) |设置可用作数据缓存的临时文件的文件夹。|
| [`need_quote_in_formula(, sheet_name)`](/cells/python-net/zh/aspose.cells/cellshelper/need_quote_in_formula/#str) |指示工作表名称是否应括在单引号中|
| [`init_for_dot_net_core()`](/cells/python-net/zh/aspose.cells/cellshelper/init_for_dot_net_core/#) |对.NetCore程序进行初始化。<br/>我们建议您首先调用此方法进行所有 .NetCore 初始化。<br/>例如：<br/>初始化DotNetCore()<br/>工作簿 wb = new Workbook();|



### 也可以看看
* 模块[`aspose.cells`](..)
