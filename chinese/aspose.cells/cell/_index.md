---
title: Cell类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 110
url: /zh/aspose.cells/cell/
is_root: false
---
## Cell类
封装代表单个工作簿单元格的对象。



Cell 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [worksheet](/cells/python-net/zh/aspose.cells/cell/worksheet) |获取父工作表。|
| [date_time_value](/cells/python-net/zh/aspose.cells/cell/date_time_value) |获取单元格中包含的 DateTime 值。|
| [row](/cells/python-net/zh/aspose.cells/cell/row) |获取单元格的行号（从零开始）。|
| [column](/cells/python-net/zh/aspose.cells/cell/column) |获取单元格的列号（从零开始）。|
| [is_formula](/cells/python-net/zh/aspose.cells/cell/is_formula) |表示指定的单元格是否包含公式。|
| [has_custom_function](/cells/python-net/zh/aspose.cells/cell/has_custom_function) |检查此单元格的公式中是否有自定义函数（不受支持的函数）。|
| [type](/cells/python-net/zh/aspose.cells/cell/type) |表示单元格值类型。|
| [name](/cells/python-net/zh/aspose.cells/cell/name) |获取单元格的名称。|
| [is_error_value](/cells/python-net/zh/aspose.cells/cell/is_error_value) |检查此单元格的值是否有错误。|
| [is_numeric_value](/cells/python-net/zh/aspose.cells/cell/is_numeric_value) |指示此单元格的值是否为数字（int、double 和 datetime）|
| [string_value](/cells/python-net/zh/aspose.cells/cell/string_value) |获取单元格中包含的字符串值。如果此单元格的类型为字符串，则返回字符串值本身。<br/>对于其他单元格类型，将返回格式化的字符串值（使用此单元格的指定样式进行格式化）。<br/>格式化的单元格值与从 Excel 复制单元格为文本时所获得的值相同（例如<br/>将单元格复制到文本编辑器或导出为 csv）。|
| [string_value_without_format](/cells/python-net/zh/aspose.cells/cell/string_value_without_format) |获取单元格的值作为不带任何格式的字符串。|
| [number_category_type](/cells/python-net/zh/aspose.cells/cell/number_category_type) |表示此单元格的数字格式的类别类型。|
| [display_string_value](/cells/python-net/zh/aspose.cells/cell/display_string_value) |通过单元格的显示样式获取此单元格的格式化字符串值。|
| [int_value](/cells/python-net/zh/aspose.cells/cell/int_value) |获取单元格中包含的整数值。|
| [double_value](/cells/python-net/zh/aspose.cells/cell/double_value) |获取单元格中包含的双精度值。|
| [float_value](/cells/python-net/zh/aspose.cells/cell/float_value) |获取单元格中包含的浮点值。|
| [bool_value](/cells/python-net/zh/aspose.cells/cell/bool_value) |获取单元格中包含的布尔值。|
| [has_custom_style](/cells/python-net/zh/aspose.cells/cell/has_custom_style) |指示此单元格是否有自定义样式设置（不同于继承的默认样式设置）<br/>来自相应的行、列或工作簿）。|
| [shared_style_index](/cells/python-net/zh/aspose.cells/cell/shared_style_index) |获取样式池中单元格的共享样式索引。|
| [formula](/cells/python-net/zh/aspose.cells/cell/formula) |获取或设置 [`Cell`](/cells/python-net/zh/aspose.cells/cell) 的公式。|
| [formula_local](/cells/python-net/zh/aspose.cells/cell/formula_local) |获取单元格的区域格式公式。|
| [r1c1_formula](/cells/python-net/zh/aspose.cells/cell/r1c1_formula) |获取或设置 [`Cell`](/cells/python-net/zh/aspose.cells/cell) 的 R1C1 公式。|
| [contains_external_link](/cells/python-net/zh/aspose.cells/cell/contains_external_link) |指示此单元格是否包含外部链接。<br/>仅当单元格为公式单元格时适用。|
| [is_array_header](/cells/python-net/zh/aspose.cells/cell/is_array_header) |表示单元格的公式是数组公式<br/>它是数组的第一个单元格。|
| [is_dynamic_array_formula](/cells/python-net/zh/aspose.cells/cell/is_dynamic_array_formula) |指示单元格的公式是动态数组公式（true）还是传统数组公式（false）。|
| [is_array_formula](/cells/python-net/zh/aspose.cells/cell/is_array_formula) |指示单元格公式是否为数组公式。|
| [is_in_array](/cells/python-net/zh/aspose.cells/cell/is_in_array) |指示单元格公式是否为数组公式。|
| [is_shared_formula](/cells/python-net/zh/aspose.cells/cell/is_shared_formula) |指示单元格公式是否是共享公式的一部分。|
| [is_table_formula](/cells/python-net/zh/aspose.cells/cell/is_table_formula) |指示此单元格是否是表格公式的一部分。|
| [is_in_table](/cells/python-net/zh/aspose.cells/cell/is_in_table) |指示此单元格是否是表格公式的一部分。|
| [value](/cells/python-net/zh/aspose.cells/cell/value) |获取/设置此单元格包含的值。|
| [is_style_set](/cells/python-net/zh/aspose.cells/cell/is_style_set) |指示单元格的样式是否已设置。如果返回 false，则表示此单元格具有默认的单元格格式。|
| [is_merged](/cells/python-net/zh/aspose.cells/cell/is_merged) |检查单元格是否属于合并范围的一部分。|
| [comment](/cells/python-net/zh/aspose.cells/cell/comment) |获取此单元格的注意事项。|
| [html_string](/cells/python-net/zh/aspose.cells/cell/html_string) |获取并设置此单元格中包含数据和一些格式的 html 字符串。|
| [is_check_box_style](/cells/python-net/zh/aspose.cells/cell/is_check_box_style) |指示是否将此单元格设置为复选框。|
| [embedded_image](/cells/python-net/zh/aspose.cells/cell/embedded_image) |获取并设置单元格中嵌入的图像。|


### 方法
|方法|描述|
| :- | :- |
| [`put_value(self, bool_value)`](/cells/python-net/zh/aspose.cells/cell/put_value/#bool) |将布尔值放入单元格。|
| [`put_value(self, int_value)`](/cells/python-net/zh/aspose.cells/cell/put_value/#int) |将整数值放入单元格。|
| [`put_value(self, double_value)`](/cells/python-net/zh/aspose.cells/cell/put_value/#float) |将双精度值放入单元格。|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/zh/aspose.cells/cell/put_value/#str-bool-bool) |将值放入单元格，如果合适，该值将转换为其他数据类型，并且单元格的数字格式将被重置。|
| [`put_value(self, string_value, is_converted)`](/cells/python-net/zh/aspose.cells/cell/put_value/#str-bool) |将字符串值放入单元格，并在适当的情况下将该值转换为其他数据类型。|
| [`put_value(self, string_value)`](/cells/python-net/zh/aspose.cells/cell/put_value/#str) |将字符串值放入单元格。|
| [`put_value(self, date_time)`](/cells/python-net/zh/aspose.cells/cell/put_value/#datetime) |将 DateTime 值放入单元格。|
| [`put_value(self, object_value)`](/cells/python-net/zh/aspose.cells/cell/put_value/#any) |将对象值放入单元格。|
| [`get_display_style(self)`](/cells/python-net/zh/aspose.cells/cell/get_display_style/#) |获取此单元格的显示样式。|
| [`get_display_style(self, include_merged_borders)`](/cells/python-net/zh/aspose.cells/cell/get_display_style/#bool) |获取此单元格的显示样式。|
| [`get_display_style(self, adjacent_borders)`](/cells/python-net/zh/aspose.cells/cell/get_display_style/#aspose.cells.bordertype) |获取此单元格的显示样式。|
| [`get_style(self)`](/cells/python-net/zh/aspose.cells/cell/get_style/#) |获取单元格样式。|
| [`get_style(self, check_borders)`](/cells/python-net/zh/aspose.cells/cell/get_style/#bool) |如果 checkBorders 为真，则检查其他单元格的边框是否会影响此单元格的样式。|
| [`set_style(self, style)`](/cells/python-net/zh/aspose.cells/cell/set_style/#aspose.cells.style) |设置单元格样式。|
| [`set_style(self, style, explicit_flag)`](/cells/python-net/zh/aspose.cells/cell/set_style/#aspose.cells.style-bool) |将改变的样式属性应用到单元格。|
| [`set_style(self, style, flag)`](/cells/python-net/zh/aspose.cells/cell/set_style/#aspose.cells.style-aspose.cells.styleflag) |根据标志应用单元格样式。|
| [`set_formula(self, formula, value)`](/cells/python-net/zh/aspose.cells/cell/set_formula/#str-any) |设置公式以及公式的值（计算结果）。|
| [`set_formula(self, formula, options)`](/cells/python-net/zh/aspose.cells/cell/set_formula/#str-aspose.cells.formulaparseoptions) |设置公式以及公式的值（计算结果）。|
| [`set_formula(self, formula, is_r1c1, is_local, value)`](/cells/python-net/zh/aspose.cells/cell/set_formula/#str-bool-bool-any) |设置公式和公式的值。|
| [`set_formula(self, formula, options, value)`](/cells/python-net/zh/aspose.cells/cell/set_formula/#str-aspose.cells.formulaparseoptions-any) |设置公式以及公式的值（计算结果）。|
| [`set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local)`](/cells/python-net/zh/aspose.cells/cell/set_array_formula/#str-int-int-bool-bool) |将数组公式设置为单元格区域。|
| [`set_array_formula(self, array_formula, row_number, column_number)`](/cells/python-net/zh/aspose.cells/cell/set_array_formula/#str-int-int) |将数组公式（在 ms excel 中通过 CTRL+SHIFT+ENTER 输入的传统数组公式）设置为单元格范围。|
| [`set_array_formula(self, array_formula, row_number, column_number, options)`](/cells/python-net/zh/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.formulaparseoptions) |将数组公式设置为单元格区域。|
| [`set_array_formula(self, array_formula, row_number, column_number, options, values)`](/cells/python-net/zh/aspose.cells/cell/set_array_formula/#str-int-int-aspose.cells.formulaparseoptions-list) |将数组公式设置为单元格区域。|
| [`set_shared_formula(self, shared_formula, row_number, column_number, is_r1c1, is_local)`](/cells/python-net/zh/aspose.cells/cell/set_shared_formula/#str-int-int-bool-bool) |将公式设置到单元格区域。|
| [`set_shared_formula(self, shared_formula, row_number, column_number)`](/cells/python-net/zh/aspose.cells/cell/set_shared_formula/#str-int-int) |将共享公式设置为单元格区域。|
| [`set_shared_formula(self, shared_formula, row_number, column_number, options)`](/cells/python-net/zh/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.formulaparseoptions) |将共享公式设置为单元格区域。|
| [`set_shared_formula(self, shared_formula, row_number, column_number, options, values)`](/cells/python-net/zh/aspose.cells/cell/set_shared_formula/#str-int-int-aspose.cells.formulaparseoptions-list) |将共享公式设置为单元格区域。|
| [`get_leafs(self)`](/cells/python-net/zh/aspose.cells/cell/get_leafs/#) |获取直接引用此单元格的所有单元格，并且当此单元格被修改时需要更新。|
| [`get_leafs(self, recursive)`](/cells/python-net/zh/aspose.cells/cell/get_leafs/#bool) |获取当此单元格被修改时将更新的所有单元格。|
| [`set_dynamic_array_formula(self, array_formula, options, calculate_value)`](/cells/python-net/zh/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-bool) |设置动态数组公式，并使公式尽可能溢出到相邻的单元格。|
| [`set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value)`](/cells/python-net/zh/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-list-bool-bool) |设置动态数组公式，并使公式尽可能溢出到相邻的单元格。|
| [`set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts)`](/cells/python-net/zh/aspose.cells/cell/set_dynamic_array_formula/#str-aspose.cells.formulaparseoptions-list-bool-bool-aspose.cells.calculationoptions) |设置动态数组公式，并使公式尽可能溢出到相邻的单元格。|
| [`set_table_formula(self, row_number, column_number, row_input_cell, column_input_cell, values)`](/cells/python-net/zh/aspose.cells/cell/set_table_formula/#int-int-str-str-list) |从该单元格开始为给定范围创建双变量数据表。|
| [`set_table_formula(self, row_number, column_number, input_cell, is_row_input, values)`](/cells/python-net/zh/aspose.cells/cell/set_table_formula/#int-int-str-bool-list) |从该单元格开始为给定范围创建单变量数据表。|
| [`set_table_formula(self, row_number, column_number, row_index_of_row_input_cell, column_index_of_row_input_cell, row_index_of_column_input_cell, column_index_of_column_input_cell, values)`](/cells/python-net/zh/aspose.cells/cell/set_table_formula/#int-int-int-int-int-int-list) |从该单元格开始为给定范围创建双变量数据表。|
| [`set_table_formula(self, row_number, column_number, row_index_of_input_cell, column_index_of_input_cell, is_row_input, values)`](/cells/python-net/zh/aspose.cells/cell/set_table_formula/#int-int-int-int-bool-list) |从该单元格开始为给定范围创建单变量数据表。|
| [`get_characters(self)`](/cells/python-net/zh/aspose.cells/cell/get_characters/#) |返回所有 Characters 对象<br/>代表单元格文本内的字符范围。|
| [`get_characters(self, flag)`](/cells/python-net/zh/aspose.cells/cell/get_characters/#bool) |返回所有 Characters 对象<br/>代表单元格文本内的字符范围。|
| [`calculate(self, options)`](/cells/python-net/zh/aspose.cells/cell/calculate/#aspose.cells.calculationoptions) |计算单元格的公式。|
| [`get_string_value(self, format_strategy)`](/cells/python-net/zh/aspose.cells/cell/get_string_value/#aspose.cells.cellvalueformatstrategy) |通过特定的格式化策略获取字符串值。|
| [`get_width_of_value(self)`](/cells/python-net/zh/aspose.cells/cell/get_width_of_value/#) |以像素为单位获取值的宽度。|
| [`get_height_of_value(self)`](/cells/python-net/zh/aspose.cells/cell/get_height_of_value/#) |以像素为单位获取值的高度。|
| [`get_format_conditions(self)`](/cells/python-net/zh/aspose.cells/cell/get_format_conditions/#) |获取适用于此单元格的格式条件。|
| [`get_formula(self, is_r1c1, is_local)`](/cells/python-net/zh/aspose.cells/cell/get_formula/#bool-bool) |获取该单元格的公式。|
| [`get_precedents(self)`](/cells/python-net/zh/aspose.cells/cell/get_precedents/#) |获取此单元格公式中出现的所有引用。|
| [`get_dependents(self, is_all)`](/cells/python-net/zh/aspose.cells/cell/get_dependents/#bool) |获取公式直接引用该单元格的所有单元格。|
| [`get_precedents_in_calculation(self)`](/cells/python-net/zh/aspose.cells/cell/get_precedents_in_calculation/#) |获取此单元格公式在计算时使用的所有先例（引用当前工作簿中的单元格）。|
| [`get_dependents_in_calculation(self, recursive)`](/cells/python-net/zh/aspose.cells/cell/get_dependents_in_calculation/#bool) |获取所有计算结果依赖于该单元格的单元格。|
| [`get_array_range(self)`](/cells/python-net/zh/aspose.cells/cell/get_array_range/#) |如果单元格的公式是数组公式，则获取数组范围。|
| [`remove_array_formula(self, leave_normal_formula)`](/cells/python-net/zh/aspose.cells/cell/remove_array_formula/#bool) |删除数组公式。|
| [`copy(self, cell)`](/cells/python-net/zh/aspose.cells/cell/copy/#aspose.cells.cell) |从源单元格复制数据。|
| [`characters(self, start_index, length)`](/cells/python-net/zh/aspose.cells/cell/characters/#int-int) |返回一个 Characters 对象，该对象代表单元格文本内的字符范围。|
| [`replace(self, place_holder, new_value, options)`](/cells/python-net/zh/aspose.cells/cell/replace/#str-str-aspose.cells.replaceoptions) |用选项替换单元格的文本。|
| [`insert_text(self, index, text)`](/cells/python-net/zh/aspose.cells/cell/insert_text/#int-str) |在单元格中插入一些字符。<br/>如果单元格格式丰富，此方法可以保留原始格式。|
| [`is_rich_text(self)`](/cells/python-net/zh/aspose.cells/cell/is_rich_text/#) |指示此单元格的字符串值是否为富格式文本。|
| [`set_characters(self, characters)`](/cells/python-net/zh/aspose.cells/cell/set_characters/#list) |设置单元格的富文本格式。|
| [`get_merged_range(self)`](/cells/python-net/zh/aspose.cells/cell/get_merged_range/#) |返回代表合并范围的 [`Range`](/cells/python-net/zh/aspose.cells/range) 对象。|
| [`get_html_string(self, html5)`](/cells/python-net/zh/aspose.cells/cell/get_html_string/#bool) |获取此单元格中包含数据和一些格式的 html 字符串。|
| [`to_json(self)`](/cells/python-net/zh/aspose.cells/cell/to_json/#) |将 [`Cell`](/cells/python-net/zh/aspose.cells/cell) 转换为 JSON 结构数据。|
| [`equals(self, cell)`](/cells/python-net/zh/aspose.cells/cell/equals/#aspose.cells.cell) |检查此对象是否与另一个单元格对象引用同一个单元格。|
| [`get_conditional_formatting_result(self)`](/cells/python-net/zh/aspose.cells/cell/get_conditional_formatting_result/#) |获取条件格式的结果。|
| [`get_validation(self)`](/cells/python-net/zh/aspose.cells/cell/get_validation/#) |获取应用于此单元格的验证。|
| [`get_validation_value(self)`](/cells/python-net/zh/aspose.cells/cell/get_validation_value/#) |获取应用于此单元格的验证值。|
| [`get_table(self)`](/cells/python-net/zh/aspose.cells/cell/get_table/#) |获取包含该单元格的表。|
| [`get_rich_value(self)`](/cells/python-net/zh/aspose.cells/cell/get_rich_value/#) |获取单元格的丰富价值。|



### 例子

```python
from aspose.cells import TextAlignmentType, Workbook
from aspose.pydrawing import Color

excel = Workbook()
cells = excel.worksheets[0].cells
# Put a string into a cell
cell = cells.get(0, 0)
cell.put_value("Hello")
first = cell.string_value
# Put an integer into a cell
cell = cells.get("B1")
cell.put_value(12)
second = cell.int_value
# Put a double into a cell
cell = cells.get(0, 2)
cell.put_value(-1.234)
third = cell.double_value
# Put a formula into a cell
cell = cells.get("D1")
cell.formula = "=B1 + C1"
# Put a combined formula: "sum(average(b1,c1), b1)" to cell at b2
cell = cells.get("b2")
cell.formula = "=sum(average(b1,c1), b1)"
# Set style of a cell
style = cell.get_style()
# Set background color
style.background_color = Color.yellow
# Set format of a cell
style.font.name = "Courier New"
style.vertical_alignment = TextAlignmentType.TOP
cell.set_style(style)

```

### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`Cell`](/cells/python-net/zh/aspose.cells/cell)
* 类 [`Range`](/cells/python-net/zh/aspose.cells/range)
