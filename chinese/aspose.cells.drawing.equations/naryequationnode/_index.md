---
title: NaryEquationNode类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 150
url: /zh/aspose.cells.drawing.equations/naryequationnode/
is_root: false
---
## NaryEquationNode类
此类指定一个 n 元运算符方程，由一个 n 元运算符、一个基数（或操作数）以及可选的上限和下限组成。



**继承：** [`NaryEquationNode`](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode)



NaryEquationNode 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [type](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/type) |  |
| [start_index](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/start_index) |  |
| [length](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/length) |  |
| [font](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/font) |  |
| [text_options](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/text_options) |  |
| [equation_type](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/equation_type) |  |
| [is_hide_subscript](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/is_hide_subscript) |是否显示下限|
| [is_hide_superscript](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/is_hide_superscript) |是否显示上限|
| [limit_location](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/limit_location) |此属性指定 n 元运算符中界限的位置。界限可以位于 n 元运算符的上下中心，也可以位于运算符的右侧。|
| [nary_operator](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/nary_operator) |一个 n 元运算符，例如“∑”。<br/>强烈建议使用属性 NaryOperatorType 来设置 n 元运算符。<br/>如果在已知类型中找不到所需的字符，请使用此属性设置。|
| [nary_operator_type](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/nary_operator_type) |一个 n 元运算符，例如“∑”|
| [nary_grow](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/nary_grow) |此属性指定文档级别的 n 元运算符的增长属性。禁用时，n 元运算符（例如积分和求和）不会增长以匹配其操作数的高度。启用时，n 元运算符会垂直增长以匹配其操作数的高度。|


### 方法
|方法|描述|
| :- | :- |
| [`add_child(self, equation_type)`](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/add_child/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`add_child(self, node)`](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/add_child/#equationnode) |  |
| [`remove_child(self, node)`](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/remove_child/#equationnode) |  |
| [`remove_child(self, index)`](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/remove_child/#int) |  |
| [`set_word_art_style(self, style)`](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/set_word_art_style/#aspose.cells.drawing.presetwordartstyle) |  |
| [`to_la_te_x(self)`](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/to_la_te_x/#) |  |
| [`to_math_ml(self)`](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/to_math_ml/#) |  |
| [`insert_child(self, index, equation_type)`](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/insert_child/#int-aspose.cells.drawing.equations.equationnodetype) |  |
| [`insert_after(self, equation_type)`](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/insert_after/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`insert_before(self, equation_type)`](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/insert_before/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`get_child(self, index)`](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/get_child/#int) |  |
| [`remove(self)`](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/remove/#) |  |
| [`remove_all_children(self)`](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/remove_all_children/#) |  |
| [`create_node(, equation_type, workbook, parent)`](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode/create_node/#aspose.cells.drawing.equations.equationnodetype-aspose.cells.workbook-equationnode) |  |



### 也可以看看
* 模块[`aspose.cells.drawing.equations`](..)
* 类 [`NaryEquationNode`](/cells/python-net/zh/aspose.cells.drawing.equations/naryequationnode)
