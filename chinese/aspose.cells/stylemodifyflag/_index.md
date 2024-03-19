---
title: StyleModifyFlag枚举
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 2590
url: /zh/aspose.cells/stylemodifyflag/
is_root: false
---
## StyleModifyFlag枚举
样式修改了标志。



StyleModifyFlag 类型公开以下成员：

### 领域
|场地|描述|
| :- | :- |
| LEFT_BORDER |指示样式的左边框是否已修改。|
| RIGHT_BORDER |指示是否已修改样式的右边框。|
| TOP_BORDER |指示样式的上边框是否已修改。|
| BOTTOM_BORDER |指示样式的底部边框是否已修改。|
| DIAGONAL_DOWN_BORDER |指示是否已修改样式的对角向下边框。|
| DIAGONAL_UP_BORDER |指示是否已修改样式的对角向上边框。|
| DIAGONAL |指示是否有一个或多个对角边框([`StyleModifyFlag.DIAGONAL_DOWN_BORDER`](/cells/python-net/zh/aspose.cells/stylemodifyflag#DIAGONAL_DOWN_BORDER),<br/> [`StyleModifyFlag.DIAGONAL_UP_BORDER`](/cells/python-net/zh/aspose.cells/stylemodifyflag#DIAGONAL_UP_BORDER)）已针对样式进行了修改。|
| HORIZONTAL_BORDER |指示样式的水平边框是否已修改。<br/>仅适用于动态样式，例如条件格式。|
| VERTICAL_BORDER |指示样式的垂直边框是否已修改。<br/>仅适用于动态样式，例如条件格式。|
| BORDERS |指示是否有一个或多个边框([`StyleModifyFlag.LEFT_BORDER`](/cells/python-net/zh/aspose.cells/stylemodifyflag#LEFT_BORDER),<br/>[`StyleModifyFlag.RIGHT_BORDER`](/cells/python-net/aspose.cells/stylemodifyflag#RIGHT_BORDER), [`StyleModifyFlag.TOP_BORDER`](/cells/python-net/aspose.cells/stylemodifyflag#TOP_BORDER), [`StyleModifyFlag.BOTTOM_BORDER`](/cells/python-net/aspose.cells/stylemodifyflag#BOTTOM_BORDER),<br/>[`StyleModifyFlag.DIAGONAL`](/cells/python-net/aspose.cells/stylemodifyflag#DIAGONAL), [`StyleModifyFlag.HORIZONTAL_BORDER`](/cells/python-net/aspose.cells/stylemodifyflag#HORIZONTAL_BORDER), [`StyleModifyFlag.VERTICAL_BORDER`](/cells/python-net/aspose.cells/stylemodifyflag#VERTICAL_BORDER))<br/>已针对样式进行了修改。|
| NUMBER_FORMAT |指示数字格式是否已修改。|
| HORIZONTAL_ALIGNMENT |指示水平对齐方式是否已修改。|
| VERTICAL_ALIGNMENT |指示垂直对齐方式是否已修改。|
| INDENT |指示缩进属性是否已被修改。|
| ROTATION |指示旋转属性是否已被修改。|
| WRAP_TEXT |指示换行文本属性是否已被修改。|
| SHRINK_TO_FIT |指示收缩以适合属性是否已被修改。|
| TEXT_DIRECTION |指示文本方向属性是否已修改。|
| RELATIVE_INDENT |指示样式的相对缩进属性是否已修改。<br/>仅适用于动态样式，例如条件格式。|
| ALIGNMENT_SETTINGS |指示是否有一个或多个与对齐相关的属性([`StyleModifyFlag.HORIZONTAL_ALIGNMENT`](/cells/python-net/zh/aspose.cells/stylemodifyflag#HORIZONTAL_ALIGNMENT),<br/>[`StyleModifyFlag.VERTICAL_ALIGNMENT`](/cells/python-net/aspose.cells/stylemodifyflag#VERTICAL_ALIGNMENT), [`StyleModifyFlag.ROTATION`](/cells/python-net/aspose.cells/stylemodifyflag#ROTATION), [`StyleModifyFlag.WRAP_TEXT`](/cells/python-net/aspose.cells/stylemodifyflag#WRAP_TEXT),<br/>[`StyleModifyFlag.WRAP_TEXT`](/cells/python-net/aspose.cells/stylemodifyflag#WRAP_TEXT), [`StyleModifyFlag.INDENT`](/cells/python-net/aspose.cells/stylemodifyflag#INDENT), [`StyleModifyFlag.SHRINK_TO_FIT`](/cells/python-net/aspose.cells/stylemodifyflag#SHRINK_TO_FIT), [`StyleModifyFlag.TEXT_DIRECTION`](/cells/python-net/aspose.cells/stylemodifyflag#TEXT_DIRECTION),<br/> [`StyleModifyFlag.RELATIVE_INDENT`](/cells/python-net/zh/aspose.cells/stylemodifyflag#RELATIVE_INDENT)）已修改。|
| PATTERN |指示阴影图案是否已修改。|
| FOREGROUND_COLOR |指示前景色是否已修改。|
| BACKGROUND_COLOR |指示背景颜色是否已修改。|
| CELL_SHADING |指示是否有一个或多个与着色相关的属性([`StyleModifyFlag.PATTERN`](/cells/python-net/zh/aspose.cells/stylemodifyflag#PATTERN),<br/> [`StyleModifyFlag.FOREGROUND_COLOR`](/cells/python-net/zh/aspose.cells/stylemodifyflag#FOREGROUND_COLOR)、[`StyleModifyFlag.BACKGROUND_COLOR`](/cells/python-net/zh/aspose.cells/stylemodifyflag#BACKGROUND_COLOR)）已修改。|
| LOCKED |指示锁定的属性是否已被修改。|
| HIDE_FORMULA |指示隐藏公式是否已修改。|
| PROTECTION_SETTINGS |指示是否有一个或多个与保护相关的属性([`StyleModifyFlag.LOCKED`](/cells/python-net/zh/aspose.cells/stylemodifyflag#LOCKED),<br/> [`StyleModifyFlag.HIDE_FORMULA`](/cells/python-net/zh/aspose.cells/stylemodifyflag#HIDE_FORMULA)）已修改。|
| FONT_SIZE |指示字体大小是否已修改。|
| FONT_NAME |指示字体名称是否已修改。|
| FONT_COLOR |指示字体颜色是否已修改。|
| FONT_WEIGHT |指示字体粗细是否已修改。|
| FONT_ITALIC |指示字体的斜体属性是否已修改。|
| FONT_UNDERLINE |指示字体的下划线属性是否被修改。|
| FONT_STRIKE |指示strike属性字体是否已修改。|
| FONT_SCRIPT |指示字体的下标或上标属性是否已修改。|
| FONT_FAMILY |指示字体系列是否已修改。|
| FONT_CHARSET |指示字体的字符集是否已修改。|
| FONT_SCHEME |没用过。|
| FONT_DIRTY |没用过。|
| FONT_SPELLING_ERROR |没用过。|
| FONT_U_FILL_TX |没用过。|
| FONT_SPACING |没用过。|
| FONT_KERNING |没用过。|
| FONT_EQUALIZE |没用过。|
| FONT_CAP |没用过。|
| FONT_VERTICAL_TEXT |  |
| FONT |指示是否已修改样式字体的一个或多个属性。|
| ALL |指示是否已修改该样式的一个或多个属性。|



### 也可以看看
* 模块[`aspose.cells`](..)
