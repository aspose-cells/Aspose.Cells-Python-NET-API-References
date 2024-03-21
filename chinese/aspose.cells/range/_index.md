---
title: Range类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1290
url: /zh/aspose.cells/range/
is_root: false
---
## Range类
封装代表电子表格中一系列单元格的对象。



Range 类型公开以下成员：

### 特性
|属性|描述|
| :- | :- |
| [current_region](/cells/python-net/zh/aspose.cells/range/current_region) |返回表示当前区域的 Range 对象。<br/>当前区域是由空白行和空白列的任意组合界定的范围。|
| [hyperlinks](/cells/python-net/zh/aspose.cells/range/hyperlinks) |获取范围内的所有超链接。|
| [row_count](/cells/python-net/zh/aspose.cells/range/row_count) |获取范围内的行数。|
| [column_count](/cells/python-net/zh/aspose.cells/range/column_count) |获取范围内的列数。|
| [name](/cells/python-net/zh/aspose.cells/range/name) |获取或设置范围的名称。|
| [refers_to](/cells/python-net/zh/aspose.cells/range/refers_to) |获取范围的引用。|
| [address](/cells/python-net/zh/aspose.cells/range/address) |获取范围的地址。|
| [left](/cells/python-net/zh/aspose.cells/range/left) |获取从 A 列左边缘到范围左边缘的距离（以磅为单位）。|
| [top](/cells/python-net/zh/aspose.cells/range/top) |获取从第 1 行的上边缘到范围的上边缘的距离（以磅为单位）。|
| [width](/cells/python-net/zh/aspose.cells/range/width) |获取范围的宽度（以磅为单位）。|
| [height](/cells/python-net/zh/aspose.cells/range/height) |获取范围的宽度（以磅为单位）。|
| [first_row](/cells/python-net/zh/aspose.cells/range/first_row) |获取范围第一行的索引。|
| [first_column](/cells/python-net/zh/aspose.cells/range/first_column) |获取范围第一列的索引。|
| [value](/cells/python-net/zh/aspose.cells/range/value) |获取和设置范围的值。|
| [column_width](/cells/python-net/zh/aspose.cells/range/column_width) |设置或获取此范围的列宽|
| [row_height](/cells/python-net/zh/aspose.cells/range/row_height) |设置或获取此范围内的行高|
| [entire_column](/cells/python-net/zh/aspose.cells/range/entire_column) |获取一个 Range 对象，该对象表示包含指定范围的整个列（或多列）。|
| [entire_row](/cells/python-net/zh/aspose.cells/range/entire_row) |获取一个 Range 对象，该对象表示包含指定范围的整行（或多行）。|
| [worksheet](/cells/python-net/zh/aspose.cells/range/worksheet) |获取包含此范围的 [`Range.worksheet`](/cells/python-net/zh/aspose.cells/range#worksheet) 对象。|


### 方法
|方法|描述|
| :- | :- |
| [auto_fill](/cells/python-net/zh/aspose.cells/range/auto_fill/#aspose.cells.Range) |自动填充目标范围。|
| [auto_fill](/cells/python-net/zh/aspose.cells/range/auto_fill/#aspose.cells.Range-aspose.cells.AutoFillType) |自动填充目标范围。|
| [set_style](/cells/python-net/zh/aspose.cells/range/set_style/#aspose.cells.Style-bool) |应用单元格样式。|
| [set_style](/cells/python-net/zh/aspose.cells/range/set_style/#aspose.cells.Style) |设置范围的样式。|
| [set_outline_borders](/cells/python-net/zh/aspose.cells/range/set_outline_borders/#aspose.cells.CellBorderType-aspose.cells.CellsColor) |设置具有相同边框样式和颜色的一系列单元格周围的轮廓边框。|
| [set_outline_borders](/cells/python-net/zh/aspose.cells/range/set_outline_borders/#aspose.cells.CellBorderType-aspose.pydrawing.Color) |设置具有相同边框样式和颜色的一系列单元格周围的轮廓边框。|
| [set_outline_borders](/cells/python-net/zh/aspose.cells/range/set_outline_borders/#list-aspose.pydrawing.Color[]) |设置一系列单元格周围的线条边框。|
| [set_outline_border](/cells/python-net/zh/aspose.cells/range/set_outline_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.cells.CellsColor) |设置一系列单元格周围的轮廓边框。|
| [set_outline_border](/cells/python-net/zh/aspose.cells/range/set_outline_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.pydrawing.Color) |设置一系列单元格周围的轮廓边框。|
| [copy](/cells/python-net/zh/aspose.cells/range/copy/#aspose.cells.Range-aspose.cells.PasteOptions) |使用粘贴特殊选项复制范围。|
| [copy](/cells/python-net/zh/aspose.cells/range/copy/#aspose.cells.Range) |从源范围复制数据（包括公式）、格式、绘图对象等。|
| [add_hyperlink](/cells/python-net/zh/aspose.cells/range/add_hyperlink/#str-str-str) |添加指向指定单元格或单元格区域的超链接。|
| [get_enumerator](/cells/python-net/zh/aspose.cells/range/get_enumerator/#) |获取此范围内的单元格的枚举数。|
| [is_intersect](/cells/python-net/zh/aspose.cells/range/is_intersect/#aspose.cells.Range) |指示范围是否相交。|
| [intersect](/cells/python-net/zh/aspose.cells/range/intersect/#aspose.cells.Range) |返回一个 [`Range`](/cells/python-net/zh/aspose.cells/range) 对象，该对象表示两个范围的矩形交集。|
| [union_rang](/cells/python-net/zh/aspose.cells/range/union_rang/#aspose.cells.Range) |返回两个范围的并集结果。|
| [union](/cells/python-net/zh/aspose.cells/range/union/#aspose.cells.Range) |返回两个范围的并集。|
| [is_blank](/cells/python-net/zh/aspose.cells/range/is_blank/#) |指示范围是否包含值。|
| [merge](/cells/python-net/zh/aspose.cells/range/merge/#) |将一系列单元格合并为一个单元格。|
| [un_merge](/cells/python-net/zh/aspose.cells/range/un_merge/#) |取消合并该范围的合并单元格。|
| [put_value](/cells/python-net/zh/aspose.cells/range/put_value/#str-bool-bool) |将一个值放入范围内，如果合适，该值将转换为其他数据类型，并且单元格的数字格式将被重置。|
| [apply_style](/cells/python-net/zh/aspose.cells/range/apply_style/#aspose.cells.Style-aspose.cells.StyleFlag) |应用整个范围的格式。|
| [set_inside_borders](/cells/python-net/zh/aspose.cells/range/set_inside_borders/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.cells.CellsColor) |设置范围内的边界。|
| [move_to](/cells/python-net/zh/aspose.cells/range/move_to/#int-int) |将当前范围移至目标范围。|
| [copy_data](/cells/python-net/zh/aspose.cells/range/copy_data/#aspose.cells.Range) |从源区域复制单元格数据（包括公式）。|
| [copy_value](/cells/python-net/zh/aspose.cells/range/copy_value/#aspose.cells.Range) |从源区域复制单元格值。|
| [copy_style](/cells/python-net/zh/aspose.cells/range/copy_style/#aspose.cells.Range) |从源范围复制样式设置。|
| [get_cell_or_null](/cells/python-net/zh/aspose.cells/range/get_cell_or_null/#int-int) |获取此范围内的 [`Cell`](/cells/python-net/zh/aspose.cells/cell) 对象或 null。|
| [get_offset](/cells/python-net/zh/aspose.cells/range/get_offset/#int-int) |通过偏移量获取 [`Range`](/cells/python-net/zh/aspose.cells/range) 范围。|



### 评论

Range 类表示 Excel 电子表格的一个区域。
这样，您可以格式化并设置范围的值。
您也可以简单地复制 Excel 的范围。

### 例子

以下示例展示了如何创建 Excel 范围并设置范围值。

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
