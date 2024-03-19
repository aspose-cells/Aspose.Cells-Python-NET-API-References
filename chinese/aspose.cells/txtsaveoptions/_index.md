---
title: TxtSaveOptions类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1590
url: /zh/aspose.cells/txtsaveoptions/
is_root: false
---
## TxtSaveOptions类
表示 csv/制表符分隔/其他文本格式的保存选项。



**遗产：** [`TxtSaveOptions`](/cells/python-net/aspose.cells/txtsaveoptions) → 
[`SaveOptions`](/cells/python-net/zh/aspose.cells/saveoptions)



TxtSaveOptions 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [__init__](/cells/python-net/zh/aspose.cells/txtsaveoptions/__init__/#) |创建文本文件保存选项。|
| [__init__](/cells/python-net/zh/aspose.cells/txtsaveoptions/__init__/#aspose.cells.SaveFormat) |创建文本文件保存选项。|


### 特性
|属性|描述|
| :- | :- |
| [save_format](/cells/python-net/zh/aspose.cells/txtsaveoptions/save_format) |获取保存文件格式。|
| [clear_data](/cells/python-net/zh/aspose.cells/txtsaveoptions/clear_data) |保存文件后将工作簿清空。|
| [cached_file_folder](/cells/python-net/zh/aspose.cells/txtsaveoptions/cached_file_folder) |缓存文件夹用于存储一些大数据。|
| [validate_merged_areas](/cells/python-net/zh/aspose.cells/txtsaveoptions/validate_merged_areas) |指示保存文件之前是否验证合并的单元格。|
| [merge_areas](/cells/python-net/zh/aspose.cells/txtsaveoptions/merge_areas) |指示在保存文件之前是否合并条件格式和验证区域。|
| [create_directory](/cells/python-net/zh/aspose.cells/txtsaveoptions/create_directory) |如果为 true 并且该目录不存在，则在保存文件之前将自动创建该目录。|
| [sort_names](/cells/python-net/zh/aspose.cells/txtsaveoptions/sort_names) |指示在保存文件之前是否对定义的名称进行排序。|
| [sort_external_names](/cells/python-net/zh/aspose.cells/txtsaveoptions/sort_external_names) |指示在保存文件之前是否对外部定义的名称进行排序。|
| [refresh_chart_cache](/cells/python-net/zh/aspose.cells/txtsaveoptions/refresh_chart_cache) |是否刷新图表缓存数据|
| [warning_callback](/cells/python-net/zh/aspose.cells/txtsaveoptions/warning_callback) |获取或设置警告回调。|
| [update_smart_art](/cells/python-net/zh/aspose.cells/txtsaveoptions/update_smart_art) |指示是否更新智能艺术设置。<br/>默认值为 false。|
| [separator](/cells/python-net/zh/aspose.cells/txtsaveoptions/separator) |获取和设置文本文件的字符分隔符。|
| [separator_string](/cells/python-net/zh/aspose.cells/txtsaveoptions/separator_string) |获取和设置一个字符串值作为分隔符。|
| [encoding](/cells/python-net/zh/aspose.cells/txtsaveoptions/encoding) |获取和设置默认编码。|
| [always_quoted](/cells/python-net/zh/aspose.cells/txtsaveoptions/always_quoted) |指示是否始终为每个字段添加“”。<br/>如果为 true，则所有值都将被引用；<br/>如果为 false，则仅在需要时才会引用值（例如，<br/>当值包含特殊字符（例如 '"' 、 '\n' 或分隔符）时。<br/>默认为 false。|
| [quote_type](/cells/python-net/zh/aspose.cells/txtsaveoptions/quote_type) |获取或设置如何在导出的文本文件中引用值。|
| [format_strategy](/cells/python-net/zh/aspose.cells/txtsaveoptions/format_strategy) |获取和设置将单元格值导出为字符串时的格式策略。|
| [light_cells_data_provider](/cells/python-net/zh/aspose.cells/txtsaveoptions/light_cells_data_provider) |用于在轻型模式下保存工作簿的数据提供程序。|
| [trim_leading_blank_row_and_column](/cells/python-net/zh/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column) |指示是否应像 ms excel 那样修剪前导空白行和列。<br/>默认为 true。|
| [trim_tailing_blank_cells](/cells/python-net/zh/aspose.cells/txtsaveoptions/trim_tailing_blank_cells) |指示是否应修剪一行中的尾部空白单元格。默认为 false。|
| [keep_separators_for_blank_row](/cells/python-net/zh/aspose.cells/txtsaveoptions/keep_separators_for_blank_row) |指示是否应为空白行输出分隔符。<br/>默认值为 false，因此默认情况下空白行的内容将为空。|
| [export_area](/cells/python-net/zh/aspose.cells/txtsaveoptions/export_area) |要导出的单元格范围。|
| [export_quote_prefix](/cells/python-net/zh/aspose.cells/txtsaveoptions/export_quote_prefix) |指示单引号是否应作为一个单元格值的一部分导出<br/>当 [`Style.quote_prefix`](/cells/python-net/zh/aspose.cells/style#quote_prefix) 为真时。默认为 false。|
| [export_all_sheets](/cells/python-net/zh/aspose.cells/txtsaveoptions/export_all_sheets) |指示是否将所有工作表导出到文本文件。<br/>如果为 false，则仅导出活动工作表，就像 MS Excel 一样。|



### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`SaveOptions`](/cells/python-net/zh/aspose.cells/saveoptions)
* 类 [`TxtSaveOptions`](/cells/python-net/zh/aspose.cells/txtsaveoptions)
