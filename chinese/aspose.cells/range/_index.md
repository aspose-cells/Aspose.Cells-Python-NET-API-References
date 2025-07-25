---
title: Range类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1180
url: /zh/aspose.cells/range/
is_root: false
---
## Range类
封装代表电子表格中单元格范围的对象。



Range 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [current_region](/cells/python-net/zh/aspose.cells/range/current_region) |返回代表当前区域的 Range 对象。<br/>当前区域是由任意空白行和空白列组合而成的范围。|
| [hyperlinks](/cells/python-net/zh/aspose.cells/range/hyperlinks) |获取范围内的所有超链接。|
| [row_count](/cells/python-net/zh/aspose.cells/range/row_count) |获取范围内的行数。|
| [column_count](/cells/python-net/zh/aspose.cells/range/column_count) |获取范围内的列数。|
| [name](/cells/python-net/zh/aspose.cells/range/name) |获取或设置范围的名称。|
| [refers_to](/cells/python-net/zh/aspose.cells/range/refers_to) |获取范围的引用。|
| [address](/cells/python-net/zh/aspose.cells/range/address) |获取范围的地址。|
| [left](/cells/python-net/zh/aspose.cells/range/left) |获取从 A 列左边缘到范围左边缘的距离（以磅为单位）。|
| [top](/cells/python-net/zh/aspose.cells/range/top) |获取从第 1 行顶部边缘到范围顶部边缘的距离（以磅为单位）。|
| [width](/cells/python-net/zh/aspose.cells/range/width) |获取范围的宽度（以点为单位）。|
| [height](/cells/python-net/zh/aspose.cells/range/height) |获取范围的宽度（以点为单位）。|
| [first_row](/cells/python-net/zh/aspose.cells/range/first_row) |获取范围第一行的索引。|
| [first_column](/cells/python-net/zh/aspose.cells/range/first_column) |获取范围第一列的索引。|
| [value](/cells/python-net/zh/aspose.cells/range/value) |获取并设置范围的值。|
| [column_width](/cells/python-net/zh/aspose.cells/range/column_width) |设置或获取此范围的列宽|
| [row_height](/cells/python-net/zh/aspose.cells/range/row_height) |设置或获取此范围内的行高|
| [entire_column](/cells/python-net/zh/aspose.cells/range/entire_column) |获取一个 Range 对象，该对象表示包含指定范围的整个列（或多列）。|
| [entire_row](/cells/python-net/zh/aspose.cells/range/entire_row) |获取一个 Range 对象，该对象表示包含指定范围的整行（或多行）。|
| [worksheet](/cells/python-net/zh/aspose.cells/range/worksheet) |获取包含此范围的 [`Range.worksheet`](/cells/python-net/zh/aspose.cells/range#worksheet) 对象。|


### 方法
|方法|描述|
| :- | :- |
| [`auto_fill(self, target)`](/cells/python-net/zh/aspose.cells/range/auto_fill/#aspose.cells.range) |自动填充目标范围。|
| [`auto_fill(self, target, auto_fill_type)`](/cells/python-net/zh/aspose.cells/range/auto_fill/#aspose.cells.range-aspose.cells.autofilltype) |自动填充目标范围。|
| [`set_style(self, style, explicit_flag)`](/cells/python-net/zh/aspose.cells/range/set_style/#aspose.cells.style-bool) |应用单元格样式。|
| [`set_style(self, style)`](/cells/python-net/zh/aspose.cells/range/set_style/#aspose.cells.style) |设置范围的样式。|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/zh/aspose.cells/range/set_outline_borders/#aspose.cells.cellbordertype-aspose.cells.cellscolor) |设置具有相同边框样式和颜色的单元格区域周围的轮廓边框。|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/zh/aspose.cells/range/set_outline_borders/#aspose.cells.cellbordertype-aspose.pydrawing.color) |设置具有相同边框样式和颜色的单元格区域周围的轮廓边框。|
| [`set_outline_borders(self, border_styles, border_colors)`](/cells/python-net/zh/aspose.cells/range/set_outline_borders/#list-aspose.pydrawing.color[]) |设置单元格区域周围的线边框。|
| [`set_outline_border(self, border_edge, border_style, border_color)`](/cells/python-net/zh/aspose.cells/range/set_outline_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) |设置单元格区域周围的轮廓边框。|
| [`set_outline_border(self, border_edge, border_style, border_color)`](/cells/python-net/zh/aspose.cells/range/set_outline_border/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.pydrawing.color) |设置单元格区域周围的轮廓边框。|
| [`copy(self, range, options)`](/cells/python-net/zh/aspose.cells/range/copy/#aspose.cells.range-aspose.cells.pasteoptions) |使用选择性粘贴选项复制范围。|
| [`copy(self, range)`](/cells/python-net/zh/aspose.cells/range/copy/#aspose.cells.range) |从源范围复制数据（包括公式）、格式、绘图对象等。|
| [`add_hyperlink(self, address, text_to_display, screen_tip)`](/cells/python-net/zh/aspose.cells/range/add_hyperlink/#str-str-str) |将超链接添加到指定单元格或单元格区域。|
| [`is_intersect(self, range)`](/cells/python-net/zh/aspose.cells/range/is_intersect/#aspose.cells.range) |表示范围是否相交。|
| [`intersect(self, range)`](/cells/python-net/zh/aspose.cells/range/intersect/#aspose.cells.range) |返回一个 [`Range`](/cells/python-net/zh/aspose.cells/range) 对象，该对象表示两个范围的矩形交集。|
| [`union_rang(self, range)`](/cells/python-net/zh/aspose.cells/range/union_rang/#aspose.cells.range) |返回两个范围的并集结果。|
| [`union_ranges(self, ranges)`](/cells/python-net/zh/aspose.cells/range/union_ranges/#list) |返回两个范围的并集结果。|
| [`union(self, range)`](/cells/python-net/zh/aspose.cells/range/union/#aspose.cells.range) |返回两个范围的并集。|
| [`is_blank(self)`](/cells/python-net/zh/aspose.cells/range/is_blank/#) |指示范围是否包含值。|
| [`merge(self)`](/cells/python-net/zh/aspose.cells/range/merge/#) |将一系列单元格合并为一个单元格。|
| [`un_merge(self)`](/cells/python-net/zh/aspose.cells/range/un_merge/#) |取消合并此范围的单元格。|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/zh/aspose.cells/range/put_value/#str-bool-bool) |将一个值放入范围内，如果合适，该值将转换为其他数据类型，并且单元格的数字格式将被重置。|
| [`apply_style(self, style, flag)`](/cells/python-net/zh/aspose.cells/range/apply_style/#aspose.cells.style-aspose.cells.styleflag) |将格式应用于整个范围。|
| [`set_inside_borders(self, border_edge, line_style, border_color)`](/cells/python-net/zh/aspose.cells/range/set_inside_borders/#aspose.cells.bordertype-aspose.cells.cellbordertype-aspose.cells.cellscolor) |设置范围的内部边界。|
| [`move_to(self, dest_row, dest_column)`](/cells/python-net/zh/aspose.cells/range/move_to/#int-int) |将当前范围移动到目标范围。|
| [`copy_data(self, range)`](/cells/python-net/zh/aspose.cells/range/copy_data/#aspose.cells.range) |从源区域复制单元格数据（包括公式）。|
| [`copy_value(self, range)`](/cells/python-net/zh/aspose.cells/range/copy_value/#aspose.cells.range) |从源范围复制单元格值。|
| [`copy_style(self, range)`](/cells/python-net/zh/aspose.cells/range/copy_style/#aspose.cells.range) |从源范围复制样式设置。|
| [`transpose(self)`](/cells/python-net/zh/aspose.cells/range/transpose/#) |将数据从行转置（旋转）到列，反之亦然。|
| [`get(self, row_offset, column_offset)`](/cells/python-net/zh/aspose.cells/range/get/#int-int) |通过 .Net 添加 API for Python，因为 this[int, int] 不受支持|
| [`get_cell_or_null(self, row_offset, column_offset)`](/cells/python-net/zh/aspose.cells/range/get_cell_or_null/#int-int) |获取 [`Cell`](/cells/python-net/zh/aspose.cells/cell) 对象或此范围内的 null。|
| [`get_offset(self, row_offset, column_offset)`](/cells/python-net/zh/aspose.cells/range/get_offset/#int-int) |通过偏移量获取 [`Range`](/cells/python-net/zh/aspose.cells/range) 范围。|
| [`to_image(self, options)`](/cells/python-net/zh/aspose.cells/range/to_image/#aspose.cells.rendering.imageorprintoptions) |将范围转换为图像。|
| [`to_json(self, options)`](/cells/python-net/zh/aspose.cells/range/to_json/#aspose.cells.jsonsaveoptions) |将范围转换为 JSON 值。|
| [`to_html(self, save_options)`](/cells/python-net/zh/aspose.cells/range/to_html/#aspose.cells.htmlsaveoptions) |将范围转换为 html 。|
| [`clear(self)`](/cells/python-net/zh/aspose.cells/range/clear/#) |清除此范围。|
| [`clear_contents(self)`](/cells/python-net/zh/aspose.cells/range/clear_contents/#) |清除此范围的内容。|
| [`clear_formats(self)`](/cells/python-net/zh/aspose.cells/range/clear_formats/#) |清除此范围的格式。|
| [`clear_comments(self)`](/cells/python-net/zh/aspose.cells/range/clear_comments/#) |清除此范围的注意事项。|
| [`clear_hyperlinks(self, clear_format)`](/cells/python-net/zh/aspose.cells/range/clear_hyperlinks/#bool) |仅删除超链接。|



### 注意事项

Range 类表示 Excel 电子表格的一个区域。
通过它，您可以格式化并设置范围的值。
您也可以简单地复制 Excel 的范围。

### 例子

下面的示例显示如何创建范围并设置 Excel 范围的值。

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
#  Create a range (A1:D3).
range = cells.create_range("A1", "D3")
#  Set value to the range.
range.value = "Hello"
# Save the Excel file
workbook.save("book1.xlsm")

```

### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`Cell`](/cells/python-net/zh/aspose.cells/cell)
* 类 [`Range`](/cells/python-net/zh/aspose.cells/range)
