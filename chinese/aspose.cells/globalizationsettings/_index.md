---
title: GlobalizationSettings类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 740
url: /zh/aspose.cells/globalizationsettings/
is_root: false
---
## GlobalizationSettings类
代表全球化设置。



GlobalizationSettings 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells/globalizationsettings/__init__/#) |构造一个新的 GlobalizationSettings 实例|


### 属性
|属性|描述|
| :- | :- |
| [chart_settings](/cells/python-net/zh/aspose.cells/globalizationsettings/chart_settings) |获取或设置图表的全球化设置。|
| [pivot_settings](/cells/python-net/zh/aspose.cells/globalizationsettings/pivot_settings) |获取或设置数据透视表的全球化设置。|
| [list_separator](/cells/python-net/zh/aspose.cells/globalizationsettings/list_separator) |获取列表的分隔符、函数的参数等。|
| [row_separator_of_formula_array](/cells/python-net/zh/aspose.cells/globalizationsettings/row_separator_of_formula_array) |获取公式中数组数据行的分隔符。|
| [column_separator_of_formula_array](/cells/python-net/zh/aspose.cells/globalizationsettings/column_separator_of_formula_array) |获取公式中数组行数据项的分隔符。|


### 方法
|方法|描述|
| :- | :- |
| [`get_pivot_total_name(self)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_pivot_total_name/#) |获取数据透视表中“总计”标签的名称。<br/>当数据透视表的数据区域包含两个或更多个数据透视字段时，您需要重写此方法。|
| [`get_pivot_grand_total_name(self)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_pivot_grand_total_name/#) |获取数据透视表中“总计”标签的名称。|
| [`get_multiple_items_name(self)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_multiple_items_name/#) |获取数据透视表中“（多项）”标签的名称。|
| [`get_all_name(self)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_all_name/#) |获取数据透视表中“（全部）”标签的名称。|
| [`get_protection_name_of_pivot_table(self)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_protection_name_of_pivot_table/#) |获取数据透视表中的保护名称。|
| [`get_column_labels_of_pivot_table(self)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_column_labels_of_pivot_table/#) |获取数据透视表中“列标签”标签的名称。|
| [`get_row_labels_name_of_pivot_table(self)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_row_labels_name_of_pivot_table/#) |获取数据透视表中“行标签”标签的名称。|
| [`get_empty_data_name(self)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_empty_data_name/#) |获取数据透视表中“（空白）”标签的名称。|
| [`get_data_field_header_name_of_pivot_table(self)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_data_field_header_name_of_pivot_table/#) |获取数据透视表中值区字段标题的名称。|
| [`get_sub_total_name(self, sub_total_type)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_sub_total_name/#aspose.cells.pivot.pivotfieldsubtotaltype) |获取数据透视表中 [`PivotFieldSubtotalType`](/cells/python-net/zh/aspose.cells.pivot/pivotfieldsubtotaltype) 类型的名称。|
| [`get_total_name(self, function_type)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_total_name/#aspose.cells.consolidationfunction) |获取函数的完整名称。|
| [`get_grand_total_name(self, function_type)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_grand_total_name/#aspose.cells.consolidationfunction) |获取函数的总计名称。|
| [`get_default_sheet_name(self)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_default_sheet_name/#) |获取自动添加工作表的默认工作表名称。<br/>默认为“Sheet”。|
| [`get_table_row_type_of_headers(self)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_table_row_type_of_headers/#) |获取由表头组成的表行的类型名称。<br/>默认为“Headers”，因此公式中的“#Headers”代表表头。|
| [`get_table_row_type_of_data(self)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_table_row_type_of_data/#) |获取由引用表的数据区域组成的表行的类型名称。<br/>默认为“数据”，因此公式中的“#Data”代表表格的数据区域。|
| [`get_table_row_type_of_all(self)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_table_row_type_of_all/#) |获取由引用表中的所有行组成的表行的类型名称。<br/>默认值为“全部”，因此公式中的“#All”代表引用表中的所有行。|
| [`get_table_row_type_of_totals(self)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_table_row_type_of_totals/#) |获取由引用表的总行组成的表行的类型名称。<br/>默认值为“Totals”，因此公式中的“#Totals”代表引用表的总行数。|
| [`get_table_row_type_of_current(self)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_table_row_type_of_current/#) |获取引用表中当前行所组成的表行的类型名称。<br/>默认为“This Row”，因此公式中的“#This Row”代表引用表中的当前行。|
| [`get_error_value_string(self, err)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_error_value_string/#str) |获取单元格错误值的显示字符串值|
| [`get_boolean_value_string(self, bv)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_boolean_value_string/#bool) |获取单元格布尔值的显示字符串值|
| [`get_local_function_name(self, standard_name)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_local_function_name/#str) |根据给定的标准函数名获取与语言环境相关的函数名。|
| [`get_standard_function_name(self, local_name)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_standard_function_name/#str) |根据给定的区域相关函数名称获取标准函数名称。|
| [`get_local_built_in_name(self, standard_name)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_local_built_in_name/#str) |根据给定的标准文本获取内置名称的区域相关文本。|
| [`get_standard_built_in_name(self, local_name)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_standard_built_in_name/#str) |根据给定的区域相关文本获取内置名称的标准文本。|
| [`get_standard_header_footer_font_style_name(self, localfont_style_name)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_standard_header_footer_font_style_name/#str) |根据给定的区域字体样式名称获取页眉/页脚的标准英文字体样式名称（常规、粗体、斜体）。|
| [`get_comment_title_name(self, type)`](/cells/python-net/zh/aspose.cells/globalizationsettings/get_comment_title_name/#aspose.cells.rendering.commenttitletype) |根据注意事项标题类型获取与语言环境相关的注意事项标题名称。|
| [`compare(self, v1, v2, ignore_case)`](/cells/python-net/zh/aspose.cells/globalizationsettings/compare/#str-str-bool) |根据某些排序规则比较两个字符串值。|



### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`PivotFieldSubtotalType`](/cells/python-net/zh/aspose.cells.pivot/pivotfieldsubtotaltype)
