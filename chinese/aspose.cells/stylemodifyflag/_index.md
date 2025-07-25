---
title: StyleModifyFlag枚举
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 2560
url: /zh/aspose.cells/stylemodifyflag/
is_root: false
---
## StyleModifyFlag枚举
风格修改了标志。



StyleModifyFlag 类型公开以下成员：

### 字段
|字段|描述|
| :- | :- |
| LEFT_BORDER |指示左边框是否已修改样式。|
| RIGHT_BORDER |指示右边框是否已根据样式进行修改。|
| TOP_BORDER |指示顶部边框是否已根据样式进行修改。|
| BOTTOM_BORDER |指示底部边框是否已修改样式。|
| DIAGONAL_DOWN_BORDER |指示对角线下边框的样式是否已修改。|
| DIAGONAL_UP_BORDER |指示对角向上边框的样式是否已修改。|
| HORIZONTAL_BORDER |指示水平边框是否已针对样式进行修改。<br/>仅适用于动态样式，例如条件格式。|
| VERTICAL_BORDER |指示垂直边框是否已针对样式进行修改。<br/>仅适用于动态样式，例如条件格式。|
| SIDE_BORDERS |表示四个边线：[`StyleModifyFlag.LEFT_BORDER`](/cells/python-net/zh/aspose.cells/stylemodifyflag#LEFT_BORDER)，<br/> [`StyleModifyFlag.RIGHT_BORDER`](/cells/python-net/zh/aspose.cells/stylemodifyflag#RIGHT_BORDER)、[`StyleModifyFlag.TOP_BORDER`](/cells/python-net/zh/aspose.cells/stylemodifyflag#TOP_BORDER) 和 [`StyleModifyFlag.BOTTOM_BORDER`](/cells/python-net/zh/aspose.cells/stylemodifyflag#BOTTOM_BORDER)。|
| DIAGONAL |表示对角线边界：[`StyleModifyFlag.DIAGONAL_DOWN_BORDER`](/cells/python-net/zh/aspose.cells/stylemodifyflag#DIAGONAL_DOWN_BORDER) 和 [`StyleModifyFlag.DIAGONAL_UP_BORDER`](/cells/python-net/zh/aspose.cells/stylemodifyflag#DIAGONAL_UP_BORDER)。|
| DYNAMIC_STYLE_BORDERS |表示动态样式的边框：[`StyleModifyFlag.HORIZONTAL_BORDER`](/cells/python-net/zh/aspose.cells/stylemodifyflag#HORIZONTAL_BORDER) 和 [`StyleModifyFlag.VERTICAL_BORDER`](/cells/python-net/zh/aspose.cells/stylemodifyflag#VERTICAL_BORDER)。|
| BORDERS |指示是否有一个或多个边框（[`StyleModifyFlag.LEFT_BORDER`](/cells/python-net/zh/aspose.cells/stylemodifyflag#LEFT_BORDER)，<br/>[`StyleModifyFlag.RIGHT_BORDER`](/cells/python-net/aspose.cells/stylemodifyflag#RIGHT_BORDER), [`StyleModifyFlag.TOP_BORDER`](/cells/python-net/aspose.cells/stylemodifyflag#TOP_BORDER), [`StyleModifyFlag.BOTTOM_BORDER`](/cells/python-net/aspose.cells/stylemodifyflag#BOTTOM_BORDER),<br/>[`StyleModifyFlag.DIAGONAL`](/cells/python-net/aspose.cells/stylemodifyflag#DIAGONAL), [`StyleModifyFlag.HORIZONTAL_BORDER`](/cells/python-net/aspose.cells/stylemodifyflag#HORIZONTAL_BORDER), [`StyleModifyFlag.VERTICAL_BORDER`](/cells/python-net/aspose.cells/stylemodifyflag#VERTICAL_BORDER))<br/>已针对风格进行了修改。|
| NUMBER_FORMAT |指示数字格式是否已被修改。|
| HORIZONTAL_ALIGNMENT |指示水平对齐是否已被修改。|
| VERTICAL_ALIGNMENT |指示垂直对齐是否已被修改。|
| INDENT |指示缩进属性是否已被修改。|
| ROTATION |指示旋转属性是否已被修改。|
| WRAP_TEXT |指示换行文本属性是否已被修改。|
| SHRINK_TO_FIT |指示“缩小以适应”属性是否已被修改。|
| TEXT_DIRECTION |指示文本方向属性是否已被修改。|
| RELATIVE_INDENT |指示样式的相对缩进属性是否已被修改。<br/>仅适用于动态样式，例如条件格式。|
| ALIGNMENT_SETTINGS |指示一个或多个与对齐相关的属性（[`StyleModifyFlag.HORIZONTAL_ALIGNMENT`](/cells/python-net/zh/aspose.cells/stylemodifyflag#HORIZONTAL_ALIGNMENT)，<br/>[`StyleModifyFlag.VERTICAL_ALIGNMENT`](/cells/python-net/aspose.cells/stylemodifyflag#VERTICAL_ALIGNMENT), [`StyleModifyFlag.ROTATION`](/cells/python-net/aspose.cells/stylemodifyflag#ROTATION), [`StyleModifyFlag.WRAP_TEXT`](/cells/python-net/aspose.cells/stylemodifyflag#WRAP_TEXT),<br/>[`StyleModifyFlag.WRAP_TEXT`](/cells/python-net/aspose.cells/stylemodifyflag#WRAP_TEXT), [`StyleModifyFlag.INDENT`](/cells/python-net/aspose.cells/stylemodifyflag#INDENT), [`StyleModifyFlag.SHRINK_TO_FIT`](/cells/python-net/aspose.cells/stylemodifyflag#SHRINK_TO_FIT), [`StyleModifyFlag.TEXT_DIRECTION`](/cells/python-net/aspose.cells/stylemodifyflag#TEXT_DIRECTION),<br/> [`StyleModifyFlag.RELATIVE_INDENT`](/cells/python-net/zh/aspose.cells/stylemodifyflag#RELATIVE_INDENT)）已被修改。|
| PATTERN |指示阴影图案是否已被修改。|
| FOREGROUND_COLOR |指示前景色是否已被修改。|
| BACKGROUND_COLOR |指示背景颜色是否已被修改。|
| CELL_SHADING |指示一个或多个与阴影相关的属性（[`StyleModifyFlag.PATTERN`](/cells/python-net/zh/aspose.cells/stylemodifyflag#PATTERN)，<br/> [`StyleModifyFlag.FOREGROUND_COLOR`](/cells/python-net/zh/aspose.cells/stylemodifyflag#FOREGROUND_COLOR)、[`StyleModifyFlag.BACKGROUND_COLOR`](/cells/python-net/zh/aspose.cells/stylemodifyflag#BACKGROUND_COLOR)）已被修改。|
| LOCKED |指示锁定的属性是否已被修改。|
| HIDE_FORMULA |指示隐藏公式是否已被修改。|
| PROTECTION_SETTINGS |指示一个或多个与保护相关的属性（[`StyleModifyFlag.LOCKED`](/cells/python-net/zh/aspose.cells/stylemodifyflag#LOCKED)，<br/> [`StyleModifyFlag.HIDE_FORMULA`](/cells/python-net/zh/aspose.cells/stylemodifyflag#HIDE_FORMULA)）已被修改。|
| FONT_SIZE |指示字体大小是否已修改。|
| FONT_NAME |指示字体名称是否已被修改。|
| FONT_COLOR |指示字体颜色是否已修改。|
| FONT_WEIGHT |指示字体粗细是否已被修改。|
| FONT_ITALIC |指示字体的斜体属性是否已被修改。|
| FONT_UNDERLINE |字体下划线属性是否被修改。|
| FONT_STRIKE |表示字体的strike属性是否被修改。|
| FONT_SCRIPT |指示字体的下标或上标属性是否已被修改。|
| FONT_FAMILY |指示字体系列是否已被修改。|
| FONT_CHARSET |指示字体的字符集是否已被修改。|
| FONT_SCHEME |未使用。|
| FONT_DIRTY |未使用。|
| FONT_SPELLING_ERROR |未使用。|
| FONT_U_FILL_TX |未使用。|
| FONT_SPACING |未使用。|
| FONT_KERNING |未使用。|
| FONT_EQUALIZE |未使用。|
| FONT_CAP |未使用。|
| FONT_VERTICAL_TEXT |  |
| FONT |指示是否已修改该样式的字体的一个或多个属性。|
| ALL |该样式的所有可修改的属性。|
| NONE |未指定任何属性。|



### 注意事项

为了方便用户，定义了多个属性的组合。
当检查它们是否针对一种风格进行了修改时，返回的值表示
组合中的一个或多个属性是否已被修改。

### 也可以看看
* 模块[`aspose.cells`](..)
