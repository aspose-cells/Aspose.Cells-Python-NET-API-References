---
title: UnionRange类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1510
url: /zh/aspose.cells/unionrange/
is_root: false
---
## UnionRange类
表示联合范围。



UnionRange 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [first_row](/cells/python-net/zh/aspose.cells/unionrange/first_row) |获取范围第一行的索引。|
| [first_column](/cells/python-net/zh/aspose.cells/unionrange/first_column) |获取范围第一列的索引。|
| [row_count](/cells/python-net/zh/aspose.cells/unionrange/row_count) |获取范围内的行数。|
| [column_count](/cells/python-net/zh/aspose.cells/unionrange/column_count) |获取范围内的行数。|
| [value](/cells/python-net/zh/aspose.cells/unionrange/value) |获取并设置范围的值。|
| [name](/cells/python-net/zh/aspose.cells/unionrange/name) |获取或设置范围的名称。|
| [refers_to](/cells/python-net/zh/aspose.cells/unionrange/refers_to) |获取范围的引用。|
| [has_range](/cells/python-net/zh/aspose.cells/unionrange/has_range) |表示其是否有范围。|
| [hyperlinks](/cells/python-net/zh/aspose.cells/unionrange/hyperlinks) |获取范围内的所有超链接。|
| [cell_count](/cells/python-net/zh/aspose.cells/unionrange/cell_count) |获取范围内的所有单元格数量。|
| [range_count](/cells/python-net/zh/aspose.cells/unionrange/range_count) |获取范围的数量。|
| [ranges](/cells/python-net/zh/aspose.cells/unionrange/ranges) |获取所有联合范围。|


### 方法
|方法|描述|
| :- | :- |
| [`set_outline_borders(self, border_styles, border_colors)`](/cells/python-net/zh/aspose.cells/unionrange/set_outline_borders/#list-aspose.pydrawing.color[]) |设置单元格区域周围的线边框。|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/zh/aspose.cells/unionrange/set_outline_borders/#aspose.cells.cellbordertype-aspose.pydrawing.color) |设置具有相同边框样式和颜色的单元格区域周围的轮廓边框。|
| [`intersect(self, range)`](/cells/python-net/zh/aspose.cells/unionrange/intersect/#str) |与另一个范围相交。|
| [`intersect(self, union_range)`](/cells/python-net/zh/aspose.cells/unionrange/intersect/#aspose.cells.unionrange) |与另一个范围相交。|
| [`intersect(self, ranges)`](/cells/python-net/zh/aspose.cells/unionrange/intersect/#list) |与另一个范围相交。|
| [`union(self, range)`](/cells/python-net/zh/aspose.cells/unionrange/union/#str) |聯合另一個范围。|
| [`union(self, union_range)`](/cells/python-net/zh/aspose.cells/unionrange/union/#aspose.cells.unionrange) |聯合另一個范围。|
| [`union(self, ranges)`](/cells/python-net/zh/aspose.cells/unionrange/union/#list) |合并范围。|
| [`merge(self)`](/cells/python-net/zh/aspose.cells/unionrange/merge/#) |将一系列单元格合并为一个单元格。|
| [`un_merge(self)`](/cells/python-net/zh/aspose.cells/unionrange/un_merge/#) |取消合并此范围的单元格。|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/zh/aspose.cells/unionrange/put_value/#str-bool-bool) |将一个值放入范围内，如果合适，该值将转换为其他数据类型，并且单元格的数字格式将被重置。|
| [`set_style(self, style)`](/cells/python-net/zh/aspose.cells/unionrange/set_style/#aspose.cells.style) |设置范围的样式。|
| [`apply_style(self, style, flag)`](/cells/python-net/zh/aspose.cells/unionrange/apply_style/#aspose.cells.style-aspose.cells.styleflag) |将格式应用于整个范围。|
| [`copy(self, range, options)`](/cells/python-net/zh/aspose.cells/unionrange/copy/#aspose.cells.unionrange-aspose.cells.pasteoptions) |使用选择性粘贴选项复制范围。|



### 也可以看看
* 模块[`aspose.cells`](..)
