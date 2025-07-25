---
title: Cells类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 160
url: /zh/aspose.cells/cells/
is_root: false
---
## Cells类
封装了与单元格相关的对象的集合，例如 [`Cell`](/cells/python-net/zh/aspose.cells/cell)、[`Row`](/cells/python-net/zh/aspose.cells/row) 等。



Cells 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [ods_cell_fields](/cells/python-net/zh/aspose.cells/cells/ods_cell_fields) |获取ods的字段列表。|
| [count](/cells/python-net/zh/aspose.cells/cells/count) |获取实例化的 Cell 对象的总数。|
| [count_large](/cells/python-net/zh/aspose.cells/cells/count_large) |获取实例化的 Cell 对象的总数。|
| [rows](/cells/python-net/zh/aspose.cells/cells/rows) |获取代表此工作表中各个行的 [`Row`](/cells/python-net/zh/aspose.cells/row) 对象的集合。|
| [merged_cells](/cells/python-net/zh/aspose.cells/cells/merged_cells) |获取合并单元格的集合。|
| [multi_thread_reading](/cells/python-net/zh/aspose.cells/cells/multi_thread_reading) |获取或设置单元格数据模型是否应支持多线程读取。<br/>此属性的默认值为 false。|
| [memory_setting](/cells/python-net/zh/aspose.cells/cells/memory_setting) |获取或设置此单元格的内存使用选项。|
| [style](/cells/python-net/zh/aspose.cells/cells/style) |获取并设置工作表的默认样式。|
| [is_default_column_hidden](/cells/python-net/zh/aspose.cells/cells/is_default_column_hidden) |  |
| [standard_width_inch](/cells/python-net/zh/aspose.cells/cells/standard_width_inch) |获取或设置工作表中的默认列宽，以英寸为单位。|
| [standard_width_pixels](/cells/python-net/zh/aspose.cells/cells/standard_width_pixels) |获取或设置工作表中的默认列宽，以像素为单位。|
| [standard_width](/cells/python-net/zh/aspose.cells/cells/standard_width) |获取或设置工作表中的默认列宽，以字符为单位。|
| [standard_height](/cells/python-net/zh/aspose.cells/cells/standard_height) |获取或设置此工作表中的默认行高，以磅为单位。|
| [standard_height_pixels](/cells/python-net/zh/aspose.cells/cells/standard_height_pixels) |获取或设置此工作表中的默认行高，以像素为单位。|
| [standard_height_inch](/cells/python-net/zh/aspose.cells/cells/standard_height_inch) |获取或设置此工作表中的默认行高，以英寸为单位。|
| [preserve_string](/cells/python-net/zh/aspose.cells/cells/preserve_string) |获取或设置一个值，该值指示是否所有工作表值都保留为字符串。<br/>默认为 false。|
| [min_row](/cells/python-net/zh/aspose.cells/cells/min_row) |包含数据或样式的单元格的最小行索引。|
| [max_row](/cells/python-net/zh/aspose.cells/cells/max_row) |包含数据或样式的单元格的最大行索引。|
| [min_column](/cells/python-net/zh/aspose.cells/cells/min_column) |集合中已实例化的单元格的最小列索引（不包括列<br/>其中为整个列定义了样式，但其中没有实例化任何单元格）。|
| [max_column](/cells/python-net/zh/aspose.cells/cells/max_column) |集合中已实例化的单元格的最大列索引（不包括列<br/>其中为整个列定义了样式，但其中没有实例化任何单元格）。|
| [min_data_row](/cells/python-net/zh/aspose.cells/cells/min_data_row) |包含数据的单元格的最小行索引。|
| [max_data_row](/cells/python-net/zh/aspose.cells/cells/max_data_row) |包含数据的单元格的最大行索引。|
| [min_data_column](/cells/python-net/zh/aspose.cells/cells/min_data_column) |包含数据的单元格的最小列索引。|
| [max_data_column](/cells/python-net/zh/aspose.cells/cells/max_data_column) |包含数据的单元格的最大列索引。|
| [is_default_row_height_matched](/cells/python-net/zh/aspose.cells/cells/is_default_row_height_matched) |表示行高和默认字体高度匹配|
| [is_default_row_hidden](/cells/python-net/zh/aspose.cells/cells/is_default_row_hidden) |指示该行是否默认隐藏。|
| [columns](/cells/python-net/zh/aspose.cells/cells/columns) |获取代表此工作表中各个列的 [`Column`](/cells/python-net/zh/aspose.cells/column) 对象的集合。|
| [ranges](/cells/python-net/zh/aspose.cells/cells/ranges) |获取运行时创建的 [`Range`](/cells/python-net/zh/aspose.cells/range) 对象的集合。|
| [last_cell](/cells/python-net/zh/aspose.cells/cells/last_cell) |获取此工作表中的最后一个单元格。|
| [max_display_range](/cells/python-net/zh/aspose.cells/cells/max_display_range) |获取包含数据、合并单元格和形状的最大范围。|
| [first_cell](/cells/python-net/zh/aspose.cells/cells/first_cell) |获取此工作表中的第一个单元格。|


### 方法
|方法|描述|
| :- | :- |
| [`create_range(self, upper_left_cell, lower_right_cell)`](/cells/python-net/zh/aspose.cells/cells/create_range/#str-str) |从一系列单元格创建一个 [`Range`](/cells/python-net/zh/aspose.cells/range) 对象。|
| [`create_range(self, first_row, first_column, total_rows, total_columns)`](/cells/python-net/zh/aspose.cells/cells/create_range/#int-int-int-int) |从一系列单元格创建一个 [`Range`](/cells/python-net/zh/aspose.cells/range) 对象。|
| [`create_range(self, address)`](/cells/python-net/zh/aspose.cells/cells/create_range/#str) |从范围的地址创建一个 [`Range`](/cells/python-net/zh/aspose.cells/range) 对象。|
| [`create_range(self, first_index, number, is_vertical)`](/cells/python-net/zh/aspose.cells/cells/create_range/#int-int-bool) |从单元格行或单元格列创建 [`Range`](/cells/python-net/zh/aspose.cells/range) 对象。|
| [`get(self, row, column)`](/cells/python-net/zh/aspose.cells/cells/get/#int-int) |通过 .Net 添加 API for Python，因为这 [int row, int column] 不受支持|
| [`get(self, cell_name)`](/cells/python-net/zh/aspose.cells/cells/get/#str) |通过 .Net 添加 API for Python，因为此 [string cellName] 不受支持|
| [`import_object_array(self, obj_array, first_row, first_column, is_vertical)`](/cells/python-net/zh/aspose.cells/cells/import_object_array/#list-int-int-bool) |将数据数组导入工作表。|
| [`import_object_array(self, obj_array, first_row, first_column, is_vertical, skip)`](/cells/python-net/zh/aspose.cells/cells/import_object_array/#list-int-int-bool-int) |将数据数组导入工作表。|
| [`import_array(self, string_array, first_row, first_column, is_vertical)`](/cells/python-net/zh/aspose.cells/cells/import_array/#list-int-int-bool) |将字符串数组导入工作表。|
| [`import_array(self, int_array, first_row, first_column, is_vertical)`](/cells/python-net/zh/aspose.cells/cells/import_array/#list-int-int-bool) |将整数数组导入工作表。|
| [`import_array(self, double_array, first_row, first_column, is_vertical)`](/cells/python-net/zh/aspose.cells/cells/import_array/#list-int-int-bool) |将双精度数组导入工作表。|
| [`import_csv(self, file_name, splitter, convert_numeric_data, first_row, first_column)`](/cells/python-net/zh/aspose.cells/cells/import_csv/#str-str-bool-int-int) |将 CSV 文件导入到单元格。|
| [`import_csv(self, stream, splitter, convert_numeric_data, first_row, first_column)`](/cells/python-net/zh/aspose.cells/cells/import_csv/#io.rawiobase-str-bool-int-int) |将 CSV 文件导入到单元格。|
| [`import_csv(self, file_name, options, first_row, first_column)`](/cells/python-net/zh/aspose.cells/cells/import_csv/#str-aspose.cells.txtloadoptions-int-int) |将 CSV 文件导入到单元格。|
| [`import_csv(self, stream, options, first_row, first_column)`](/cells/python-net/zh/aspose.cells/cells/import_csv/#io.rawiobase-aspose.cells.txtloadoptions-int-int) |将 CSV 文件导入到单元格。|
| [`merge(self, first_row, first_column, total_rows, total_columns)`](/cells/python-net/zh/aspose.cells/cells/merge/#int-int-int-int) |将指定范围的单元格合并为一个单元格。|
| [`merge(self, first_row, first_column, total_rows, total_columns, merge_conflict)`](/cells/python-net/zh/aspose.cells/cells/merge/#int-int-int-int-bool) |将指定范围的单元格合并为一个单元格。|
| [`merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict)`](/cells/python-net/zh/aspose.cells/cells/merge/#int-int-int-int-bool-bool) |将指定范围的单元格合并为一个单元格。|
| [`get_row_height(self, row, is_original, unit_type)`](/cells/python-net/zh/aspose.cells/cells/get_row_height/#int-bool-aspose.cells.cellsunittype) |获取行高。|
| [`get_row_height(self, row)`](/cells/python-net/zh/aspose.cells/cells/get_row_height/#int) |获取指定行的高度，以点为单位。|
| [`get_column_width(self, column, is_original, unit_type)`](/cells/python-net/zh/aspose.cells/cells/get_column_width/#int-bool-aspose.cells.cellsunittype) |获取列宽。|
| [`get_column_width(self, column)`](/cells/python-net/zh/aspose.cells/cells/get_column_width/#int) |获取普通视图中指定列的宽度（以字符为单位）|
| [`get_column_width_pixel(self, column)`](/cells/python-net/zh/aspose.cells/cells/get_column_width_pixel/#int) |获取普通视图中指定列的宽度，以像素为单位。|
| [`get_column_width_pixel(self, column, original)`](/cells/python-net/zh/aspose.cells/cells/get_column_width_pixel/#int-bool) |获取普通视图中指定列的宽度，以像素为单位。|
| [`copy_columns(self, source_cells0, source_column_index, destination_column_index, column_number, paste_options)`](/cells/python-net/zh/aspose.cells/cells/copy_columns/#aspose.cells.cells-int-int-int-aspose.cells.pasteoptions) |复制整列的数据和格式。|
| [`copy_columns(self, source_cells0, source_column_index, destination_column_index, column_number)`](/cells/python-net/zh/aspose.cells/cells/copy_columns/#aspose.cells.cells-int-int-int) |复制整列的数据和格式。|
| [`copy_columns(self, source_cells, source_column_index, source_total_columns, destination_column_index, destination_total_columns)`](/cells/python-net/zh/aspose.cells/cells/copy_columns/#aspose.cells.cells-int-int-int-int) |复制整列的数据和格式。|
| [`copy_rows(self, source_cells, source_row_index, destination_row_index, row_number)`](/cells/python-net/zh/aspose.cells/cells/copy_rows/#aspose.cells.cells-int-int-int) |复制一些整行的数据和格式。|
| [`copy_rows(self, source_cells0, source_row_index, destination_row_index, row_number, copy_options)`](/cells/python-net/zh/aspose.cells/cells/copy_rows/#aspose.cells.cells-int-int-int-aspose.cells.copyoptions) |复制一些整行的数据和格式。|
| [`copy_rows(self, source_cells0, source_row_index, destination_row_index, row_number, copy_options, paste_options)`](/cells/python-net/zh/aspose.cells/cells/copy_rows/#aspose.cells.cells-int-int-int-aspose.cells.copyoptions-aspose.cells.pasteoptions) |复制一些整行的数据和格式。|
| [`group_columns(self, first_index, last_index)`](/cells/python-net/zh/aspose.cells/cells/group_columns/#int-int) |对列进行分组。|
| [`group_columns(self, first_index, last_index, is_hidden)`](/cells/python-net/zh/aspose.cells/cells/group_columns/#int-int-bool) |对列进行分组。|
| [`ungroup_rows(self, first_index, last_index, is_all)`](/cells/python-net/zh/aspose.cells/cells/ungroup_rows/#int-int-bool) |取消行分组。|
| [`ungroup_rows(self, first_index, last_index)`](/cells/python-net/zh/aspose.cells/cells/ungroup_rows/#int-int) |取消行分组。|
| [`group_rows(self, first_index, last_index, is_hidden)`](/cells/python-net/zh/aspose.cells/cells/group_rows/#int-int-bool) |对行进行分组。|
| [`group_rows(self, first_index, last_index)`](/cells/python-net/zh/aspose.cells/cells/group_rows/#int-int) |对行进行分组。|
| [`delete_column(self, column_index, update_reference)`](/cells/python-net/zh/aspose.cells/cells/delete_column/#int-bool) |删除一列。|
| [`delete_column(self, column_index)`](/cells/python-net/zh/aspose.cells/cells/delete_column/#int) |删除一列。|
| [`delete_columns(self, column_index, total_columns, update_reference)`](/cells/python-net/zh/aspose.cells/cells/delete_columns/#int-int-bool) |删除几列。|
| [`delete_columns(self, column_index, total_columns, options)`](/cells/python-net/zh/aspose.cells/cells/delete_columns/#int-int-aspose.cells.deleteoptions) |删除几列。|
| [`delete_row(self, row_index)`](/cells/python-net/zh/aspose.cells/cells/delete_row/#int) |删除一行。|
| [`delete_row(self, row_index, update_reference)`](/cells/python-net/zh/aspose.cells/cells/delete_row/#int-bool) |删除一行。|
| [`delete_rows(self, row_index, total_rows)`](/cells/python-net/zh/aspose.cells/cells/delete_rows/#int-int) |删除多行。|
| [`delete_rows(self, row_index, total_rows, update_reference)`](/cells/python-net/zh/aspose.cells/cells/delete_rows/#int-int-bool) |删除工作表中的多行。|
| [`delete_rows(self, row_index, total_rows, options)`](/cells/python-net/zh/aspose.cells/cells/delete_rows/#int-int-aspose.cells.deleteoptions) |删除工作表中的多行。|
| [`delete_blank_columns(self)`](/cells/python-net/zh/aspose.cells/cells/delete_blank_columns/#) |删除所有不包含任何数据的空白列。|
| [`delete_blank_columns(self, options)`](/cells/python-net/zh/aspose.cells/cells/delete_blank_columns/#aspose.cells.deleteoptions) |删除所有不包含任何数据的空白列。|
| [`delete_blank_rows(self)`](/cells/python-net/zh/aspose.cells/cells/delete_blank_rows/#) |删除所有不包含任何数据或其他对象的空白行。|
| [`delete_blank_rows(self, options)`](/cells/python-net/zh/aspose.cells/cells/delete_blank_rows/#aspose.cells.deleteoptions) |删除所有不包含任何数据或某些特殊对象（例如可见注释、数据透视表）的空白行。|
| [`insert_columns(self, column_index, total_columns)`](/cells/python-net/zh/aspose.cells/cells/insert_columns/#int-int) |在工作表中插入一些列。|
| [`insert_columns(self, column_index, total_columns, update_reference)`](/cells/python-net/zh/aspose.cells/cells/insert_columns/#int-int-bool) |在工作表中插入一些列。|
| [`insert_columns(self, column_index, total_columns, options)`](/cells/python-net/zh/aspose.cells/cells/insert_columns/#int-int-aspose.cells.insertoptions) |在工作表中插入一些列。|
| [`insert_column(self, column_index, update_reference)`](/cells/python-net/zh/aspose.cells/cells/insert_column/#int-bool) |在工作表中插入新列。|
| [`insert_column(self, column_index)`](/cells/python-net/zh/aspose.cells/cells/insert_column/#int) |在工作表中插入新列。|
| [`insert_rows(self, row_index, total_rows, update_reference)`](/cells/python-net/zh/aspose.cells/cells/insert_rows/#int-int-bool) |在工作表中插入多行。|
| [`insert_rows(self, row_index, total_rows, options)`](/cells/python-net/zh/aspose.cells/cells/insert_rows/#int-int-aspose.cells.insertoptions) |在工作表中插入多行。|
| [`insert_rows(self, row_index, total_rows)`](/cells/python-net/zh/aspose.cells/cells/insert_rows/#int-int) |在工作表中插入多行。|
| [`clear_range(self, range)`](/cells/python-net/zh/aspose.cells/cells/clear_range/#aspose.cells.cellarea) |清除一定范围的内容和格式。|
| [`clear_range(self, start_row, start_column, end_row, end_column)`](/cells/python-net/zh/aspose.cells/cells/clear_range/#int-int-int-int) |清除一定范围的内容和格式。|
| [`clear_contents(self, range)`](/cells/python-net/zh/aspose.cells/cells/clear_contents/#aspose.cells.cellarea) |清除一定范围的内容。|
| [`clear_contents(self, start_row, start_column, end_row, end_column)`](/cells/python-net/zh/aspose.cells/cells/clear_contents/#int-int-int-int) |清除一定范围的内容。|
| [`clear_formats(self, range)`](/cells/python-net/zh/aspose.cells/cells/clear_formats/#aspose.cells.cellarea) |清除范围的格式。|
| [`clear_formats(self, start_row, start_column, end_row, end_column)`](/cells/python-net/zh/aspose.cells/cells/clear_formats/#int-int-int-int) |清除范围的格式。|
| [`find(self, what, previous_cell)`](/cells/python-net/zh/aspose.cells/cells/find/#any-aspose.cells.cell) |查找包含输入对象的单元格。|
| [`find(self, what, previous_cell, find_options)`](/cells/python-net/zh/aspose.cells/cells/find/#any-aspose.cells.cell-aspose.cells.findoptions) |查找包含输入对象的单元格。|
| [`end_cell_in_row(self, row_index)`](/cells/python-net/zh/aspose.cells/cells/end_cell_in_row/#int) |获取此行的最后一个单元格。|
| [`end_cell_in_row(self, start_row, end_row, start_column, end_column)`](/cells/python-net/zh/aspose.cells/cells/end_cell_in_row/#int-int-int-int) |获取此范围内具有最大行索引的最后一个单元格。|
| [`end_cell_in_column(self, column_index)`](/cells/python-net/zh/aspose.cells/cells/end_cell_in_column/#int) |获取此列的最后一个单元格。|
| [`end_cell_in_column(self, start_row, end_row, start_column, end_column)`](/cells/python-net/zh/aspose.cells/cells/end_cell_in_column/#int-int-int-int) |获取此范围内具有最大列索引的最后一个单元格。|
| [`insert_range(self, area, shift_number, shift_type, update_reference)`](/cells/python-net/zh/aspose.cells/cells/insert_range/#aspose.cells.cellarea-int-aspose.cells.shifttype-bool) |插入单元格区域并根据移位选项移动单元格。|
| [`insert_range(self, area, shift_type)`](/cells/python-net/zh/aspose.cells/cells/insert_range/#aspose.cells.cellarea-aspose.cells.shifttype) |插入单元格区域并根据移位选项移动单元格。|
| [`insert_range(self, area, shift_number, shift_type)`](/cells/python-net/zh/aspose.cells/cells/insert_range/#aspose.cells.cellarea-int-aspose.cells.shifttype) |插入单元格区域并根据移位选项移动单元格。|
| [`subtotal(self, ca, group_by, function, total_list)`](/cells/python-net/zh/aspose.cells/cells/subtotal/#aspose.cells.cellarea-int-aspose.cells.consolidationfunction-list) |为该范围创建小计。|
| [`subtotal(self, ca, group_by, function, total_list, replace, page_breaks, summary_below_data)`](/cells/python-net/zh/aspose.cells/cells/subtotal/#aspose.cells.cellarea-int-aspose.cells.consolidationfunction-list-bool-bool-bool) |为该范围创建小计。|
| [`remove_duplicates(self)`](/cells/python-net/zh/aspose.cells/cells/remove_duplicates/#) |删除工作表中的重复行。|
| [`remove_duplicates(self, start_row, start_column, end_row, end_column)`](/cells/python-net/zh/aspose.cells/cells/remove_duplicates/#int-int-int-int) |删除范围内的重复值。|
| [`remove_duplicates(self, start_row, start_column, end_row, end_column, has_headers, column_offsets)`](/cells/python-net/zh/aspose.cells/cells/remove_duplicates/#int-int-int-int-bool-list) |删除范围内的重复数据。|
| [`get_cell_display_style(self, row, column)`](/cells/python-net/zh/aspose.cells/cells/get_cell_display_style/#int-int) |获取给定单元格的显示样式。|
| [`get_cell_display_style(self, row, column, adjacent_borders)`](/cells/python-net/zh/aspose.cells/cells/get_cell_display_style/#int-int-aspose.cells.bordertype) |获取给定单元格的显示样式。|
| [`get_row_enumerator(self)`](/cells/python-net/zh/aspose.cells/cells/get_row_enumerator/#) |获取行枚举器。|
| [`get_merged_areas(self)`](/cells/python-net/zh/aspose.cells/cells/get_merged_areas/#) |获取所有合并的单元格。|
| [`get_cell(self, row, column)`](/cells/python-net/zh/aspose.cells/cells/get_cell/#int-int) |获取指定单元格行索引和列索引处的 [`Cell`](/cells/python-net/zh/aspose.cells/cell) 元素或 null。|
| [`get_row(self, row)`](/cells/python-net/zh/aspose.cells/cells/get_row/#int) |获取指定单元格行索引处的 [`Row`](/cells/python-net/zh/aspose.cells/row) 元素。|
| [`check_cell(self, row, column)`](/cells/python-net/zh/aspose.cells/cells/check_cell/#int-int) |获取指定单元格行索引和列索引处的 [`Cell`](/cells/python-net/zh/aspose.cells/cell) 元素或 null。|
| [`check_row(self, row)`](/cells/python-net/zh/aspose.cells/cells/check_row/#int) |获取指定单元格行索引处的 [`Row`](/cells/python-net/zh/aspose.cells/row) 元素或 null。|
| [`check_column(self, column_index)`](/cells/python-net/zh/aspose.cells/cells/check_column/#int) |获取指定列索引处的 [`Column`](/cells/python-net/zh/aspose.cells/column) 元素或 null。|
| [`is_row_hidden(self, row_index)`](/cells/python-net/zh/aspose.cells/cells/is_row_hidden/#int) |检查给定索引处的行是否被隐藏。|
| [`is_column_hidden(self, column_index)`](/cells/python-net/zh/aspose.cells/cells/is_column_hidden/#int) |检查给定索引处的列是否被隐藏。|
| [`add_range(self, range_object)`](/cells/python-net/zh/aspose.cells/cells/add_range/#aspose.cells.range) |向单元格添加范围对象引用|
| [`clear(self)`](/cells/python-net/zh/aspose.cells/cells/clear/#) |清除工作表的所有数据。|
| [`import_array_list(self, array_list, first_row, first_column, is_vertical)`](/cells/python-net/zh/aspose.cells/cells/import_array_list/#list-int-int-bool) |将数据数组列表导入工作表。|
| [`import_formula_array(self, string_array, first_row, first_column, is_vertical)`](/cells/python-net/zh/aspose.cells/cells/import_formula_array/#list-int-int-bool) |将公式数组导入工作表。|
| [`text_to_columns(self, row, column, total_rows, options)`](/cells/python-net/zh/aspose.cells/cells/text_to_columns/#int-int-int-aspose.cells.txtloadoptions) |将指定列中的内容拆分为多列。|
| [`un_merge(self, first_row, first_column, total_rows, total_columns)`](/cells/python-net/zh/aspose.cells/cells/un_merge/#int-int-int-int) |取消合并指定范围的合并单元格。|
| [`clear_merged_cells(self)`](/cells/python-net/zh/aspose.cells/cells/clear_merged_cells/#) |清除所有合并范围。|
| [`hide_row(self, row)`](/cells/python-net/zh/aspose.cells/cells/hide_row/#int) |隐藏一行。|
| [`unhide_row(self, row, height)`](/cells/python-net/zh/aspose.cells/cells/unhide_row/#int-float) |取消隐藏行。|
| [`hide_rows(self, row, total_rows)`](/cells/python-net/zh/aspose.cells/cells/hide_rows/#int-int) |隐藏多行。|
| [`unhide_rows(self, row, total_rows, height)`](/cells/python-net/zh/aspose.cells/cells/unhide_rows/#int-int-float) |取消隐藏隐藏的行。|
| [`set_row_height_pixel(self, row, pixels)`](/cells/python-net/zh/aspose.cells/cells/set_row_height_pixel/#int-int) |以像素为单位设置行高。|
| [`set_row_height_inch(self, row, inches)`](/cells/python-net/zh/aspose.cells/cells/set_row_height_inch/#int-float) |以英寸为单位设置行高。|
| [`set_row_height(self, row, height)`](/cells/python-net/zh/aspose.cells/cells/set_row_height/#int-float) |设置指定行的高度。|
| [`get_row_original_height_point(self, row)`](/cells/python-net/zh/aspose.cells/cells/get_row_original_height_point/#int) |如果行被隐藏，则获取原始行的高度（以点为单位）|
| [`get_column_original_width_point(self, column)`](/cells/python-net/zh/aspose.cells/cells/get_column_original_width_point/#int) |如果列被隐藏，则获取原始列的高度（以点为单位）|
| [`hide_column(self, column)`](/cells/python-net/zh/aspose.cells/cells/hide_column/#int) |隐藏一列。|
| [`unhide_column(self, column, width)`](/cells/python-net/zh/aspose.cells/cells/unhide_column/#int-float) |取消隐藏列|
| [`hide_columns(self, column, total_columns)`](/cells/python-net/zh/aspose.cells/cells/hide_columns/#int-int) |隐藏多列。|
| [`unhide_columns(self, column, total_columns, width)`](/cells/python-net/zh/aspose.cells/cells/unhide_columns/#int-int-float) |取消隐藏多列。|
| [`get_view_row_height(self, row)`](/cells/python-net/zh/aspose.cells/cells/get_view_row_height/#int) |获取指定行的高度。|
| [`get_row_height_inch(self, row)`](/cells/python-net/zh/aspose.cells/cells/get_row_height_inch/#int) |获取指定行的高度（以英寸为单位）。|
| [`get_view_row_height_inch(self, row)`](/cells/python-net/zh/aspose.cells/cells/get_view_row_height_inch/#int) |获取指定行的高度（以英寸为单位）。|
| [`get_row_height_pixel(self, row)`](/cells/python-net/zh/aspose.cells/cells/get_row_height_pixel/#int) |以像素为单位获取指定行的高度。|
| [`set_column_width_pixel(self, column, pixels)`](/cells/python-net/zh/aspose.cells/cells/set_column_width_pixel/#int-int) |在普通视图中以像素为单位设置列宽。|
| [`set_column_width_inch(self, column, inches)`](/cells/python-net/zh/aspose.cells/cells/set_column_width_inch/#int-float) |在普通视图中以英寸为单位设置列宽。|
| [`set_column_width(self, column, width)`](/cells/python-net/zh/aspose.cells/cells/set_column_width/#int-float) |设置普通视图中指定列的宽度。|
| [`get_column_width_inch(self, column)`](/cells/python-net/zh/aspose.cells/cells/get_column_width_inch/#int) |获取普通视图中指定列的宽度，以英寸为单位。|
| [`get_view_column_width_pixel(self, column)`](/cells/python-net/zh/aspose.cells/cells/get_view_column_width_pixel/#int) |获取不同视图类型中的宽度。|
| [`set_view_column_width_pixel(self, column, pixels)`](/cells/python-net/zh/aspose.cells/cells/set_view_column_width_pixel/#int-int) |设置不同视图中的列宽。|
| [`get_last_data_row(self, column)`](/cells/python-net/zh/aspose.cells/cells/get_last_data_row/#int) |获取包含指定列数据单元格的最后一行索引。|
| [`get_first_data_row(self, column)`](/cells/python-net/zh/aspose.cells/cells/get_first_data_row/#int) |获取包含指定列数据的单元格的第一行索引。|
| [`apply_column_style(self, column, style, flag)`](/cells/python-net/zh/aspose.cells/cells/apply_column_style/#int-aspose.cells.style-aspose.cells.styleflag) |将格式应用于整列。|
| [`apply_row_style(self, row, style, flag)`](/cells/python-net/zh/aspose.cells/cells/apply_row_style/#int-aspose.cells.style-aspose.cells.styleflag) |将格式应用于整行。|
| [`apply_style(self, style, flag)`](/cells/python-net/zh/aspose.cells/cells/apply_style/#aspose.cells.style-aspose.cells.styleflag) |将格式应用于整个工作表。|
| [`copy_column(self, source_cells, source_column_index, destination_column_index)`](/cells/python-net/zh/aspose.cells/cells/copy_column/#aspose.cells.cells-int-int) |复制整列的数据和格式。|
| [`copy_row(self, source_cells, source_row_index, destination_row_index)`](/cells/python-net/zh/aspose.cells/cells/copy_row/#aspose.cells.cells-int-int) |复制整行的数据和格式。|
| [`get_grouped_row_outline_level(self, row_index)`](/cells/python-net/zh/aspose.cells/cells/get_grouped_row_outline_level/#int) |获取行的大纲级别（从零开始）。|
| [`get_grouped_column_outline_level(self, column_index)`](/cells/python-net/zh/aspose.cells/cells/get_grouped_column_outline_level/#int) |获取列的大纲级别（从零开始）。|
| [`get_max_grouped_column_outline_level(self)`](/cells/python-net/zh/aspose.cells/cells/get_max_grouped_column_outline_level/#) |获取最大分组列大纲级别（从零开始）。|
| [`get_max_grouped_row_outline_level(self)`](/cells/python-net/zh/aspose.cells/cells/get_max_grouped_row_outline_level/#) |获取最大分组行大纲级别（从零开始）。|
| [`show_group_detail(self, is_vertical, index)`](/cells/python-net/zh/aspose.cells/cells/show_group_detail/#bool-int) |扩展分组的行/列。|
| [`hide_group_detail(self, is_vertical, index)`](/cells/python-net/zh/aspose.cells/cells/hide_group_detail/#bool-int) |折叠分组的行/列。|
| [`ungroup_columns(self, first_index, last_index)`](/cells/python-net/zh/aspose.cells/cells/ungroup_columns/#int-int) |取消列分组。|
| [`is_deleting_range_enabled(self, start_row, start_column, total_rows, total_columns)`](/cells/python-net/zh/aspose.cells/cells/is_deleting_range_enabled/#int-int-int-int) |检查该范围是否可以删除。|
| [`is_blank_column(self, column_index)`](/cells/python-net/zh/aspose.cells/cells/is_blank_column/#int) |检查给定列是否为空（不包含任何数据）。|
| [`insert_row(self, row_index)`](/cells/python-net/zh/aspose.cells/cells/insert_row/#int) |在工作表中插入新行。|
| [`link_to_xml_map(self, map_name, row, column, path)`](/cells/python-net/zh/aspose.cells/cells/link_to_xml_map/#str-int-int-str) |链接到 xml 地图。|
| [`move_range(self, source_area, dest_row, dest_column)`](/cells/python-net/zh/aspose.cells/cells/move_range/#aspose.cells.cellarea-int-int) |移动范围。|
| [`insert_cut_cells(self, cut_range, row, column, shift_type)`](/cells/python-net/zh/aspose.cells/cells/insert_cut_cells/#aspose.cells.range-int-int-aspose.cells.shifttype) |插入切割范围。|
| [`delete_range(self, start_row, start_column, end_row, end_column, shift_type)`](/cells/python-net/zh/aspose.cells/cells/delete_range/#int-int-int-int-aspose.cells.shifttype) |删除一定范围的单元格并根据移位选项移动单元格。|
| [`retrieve_subtotal_setting(self, ca)`](/cells/python-net/zh/aspose.cells/cells/retrieve_subtotal_setting/#aspose.cells.cellarea) |检索范围的小计设置。|
| [`remove_formulas(self)`](/cells/python-net/zh/aspose.cells/cells/remove_formulas/#) |删除所有公式并替换为公式的值。|
| [`convert_string_to_numeric_value(self)`](/cells/python-net/zh/aspose.cells/cells/convert_string_to_numeric_value/#) |如果可能，将工作表中的所有字符串数据转换为数值。|
| [`get_dependents(self, is_all, row, column)`](/cells/python-net/zh/aspose.cells/cells/get_dependents/#bool-int-int) |获取引用特定单元格的所有单元格。|
| [`get_dependents_in_calculation(self, row, column, recursive)`](/cells/python-net/zh/aspose.cells/cells/get_dependents_in_calculation/#int-int-bool) |获取计算结果依赖于特定单元格的所有单元格。|
| [`get_cells_with_place_in_cell_picture(self)`](/cells/python-net/zh/aspose.cells/cells/get_cells_with_place_in_cell_picture/#) |获取包含嵌入图片的所有单元格。|
| [`get_cell_style(self, row, column)`](/cells/python-net/zh/aspose.cells/cells/get_cell_style/#int-int) |获取给定单元格的样式。|



### 注意事项



### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`Cell`](/cells/python-net/zh/aspose.cells/cell)
* 类 [`Column`](/cells/python-net/zh/aspose.cells/column)
* 类 [`Range`](/cells/python-net/zh/aspose.cells/range)
* 类 [`Row`](/cells/python-net/zh/aspose.cells/row)
