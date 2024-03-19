---
title: Style类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1460
url: /zh/aspose.cells/style/
is_root: false
---
## Style类
表示Excel文档的显示样式，如字体、颜色、对齐方式、边框等。
Style 对象包含所有样式属性（字体、数字格式、对齐方式等）作为属性。



Style 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [__init__](/cells/python-net/zh/aspose.cells/style/__init__/#) |初始化 [`Style`](/cells/python-net/zh/aspose.cells/style) 类的新实例。|


### 特性
|属性|描述|
| :- | :- |
| [background_theme_color](/cells/python-net/zh/aspose.cells/style/background_theme_color) |获取和设置背景主题颜色。|
| [foreground_theme_color](/cells/python-net/zh/aspose.cells/style/foreground_theme_color) |获取和设置前景主题颜色。|
| [name](/cells/python-net/zh/aspose.cells/style/name) |获取或设置样式的名称。|
| [pattern](/cells/python-net/zh/aspose.cells/style/pattern) |获取或设置单元格背景图案类型。|
| [borders](/cells/python-net/zh/aspose.cells/style/borders) |获取样式的[`BorderCollection`](/cells/python-net/zh/aspose.cells/bordercollection)。|
| [background_color](/cells/python-net/zh/aspose.cells/style/background_color) |获取或设置样式的背景颜色。|
| [background_argb_color](/cells/python-net/zh/aspose.cells/style/background_argb_color) |获取和设置具有 32 位 ARGB 值的背景颜色。|
| [foreground_color](/cells/python-net/zh/aspose.cells/style/foreground_color) |获取或设置样式的前景色。|
| [foreground_argb_color](/cells/python-net/zh/aspose.cells/style/foreground_argb_color) |获取和设置 32 位 ARGB 值的前景色。|
| [has_borders](/cells/python-net/zh/aspose.cells/style/has_borders) |检查样式是否设置了边框。|
| [parent_style](/cells/python-net/zh/aspose.cells/style/parent_style) |获取该样式的父样式。|
| [is_number_format_applied](/cells/python-net/zh/aspose.cells/style/is_number_format_applied) |指示是否应应用数字格式。|
| [is_font_applied](/cells/python-net/zh/aspose.cells/style/is_font_applied) |指示是否应应用字体格式。|
| [is_alignment_applied](/cells/python-net/zh/aspose.cells/style/is_alignment_applied) |指示是否应应用对齐格式。|
| [is_border_applied](/cells/python-net/zh/aspose.cells/style/is_border_applied) |指示是否应应用边框格式。|
| [is_fill_applied](/cells/python-net/zh/aspose.cells/style/is_fill_applied) |指示是否应应用填充格式。|
| [is_protection_applied](/cells/python-net/zh/aspose.cells/style/is_protection_applied) |指示是否应应用保护格式。|
| [indent_level](/cells/python-net/zh/aspose.cells/style/indent_level) |表示单元格或区域的缩进级别。只能是 0 到 250 之间的整数。|
| [font](/cells/python-net/zh/aspose.cells/style/font) |获取 [`Style.font`](/cells/python-net/zh/aspose.cells/style#font) 对象。|
| [rotation_angle](/cells/python-net/zh/aspose.cells/style/rotation_angle) |代表文本旋转角度。|
| [horizontal_alignment](/cells/python-net/zh/aspose.cells/style/horizontal_alignment) |获取或设置单元格中文本的水平对齐类型。|
| [vertical_alignment](/cells/python-net/zh/aspose.cells/style/vertical_alignment) |获取或设置单元格中文本的垂直对齐类型。|
| [is_text_wrapped](/cells/python-net/zh/aspose.cells/style/is_text_wrapped) |获取或设置一个值，该值指示单元格内的文本是否换行。|
| [number](/cells/python-net/zh/aspose.cells/style/number) |获取或设置数字和日期的显示格式。不同地区的格式化模式有所不同。|
| [is_locked](/cells/python-net/zh/aspose.cells/style/is_locked) |获取或设置一个值，该值指示单元格是否可以修改。|
| [custom](/cells/python-net/zh/aspose.cells/style/custom) |表示此样式对象的自定义数字格式字符串。<br/>如果未设置自定义数字格式（例如内置数字格式），将返回“”。|
| [culture_custom](/cells/python-net/zh/aspose.cells/style/culture_custom) |获取和设置数字格式的区域性相关模式字符串。<br/>如果该对象没有设置数字格式，则返回 null。<br/>如果是内置数字格式，则返回内置数字对应的模式字符串。|
| [invariant_custom](/cells/python-net/zh/aspose.cells/style/invariant_custom) |获取数字格式的与区域性无关的模式字符串。<br/>如果该对象没有设置数字格式，则返回 null。<br/>如果是内置数字格式，则返回内置数字对应的模式字符串。|
| [is_formula_hidden](/cells/python-net/zh/aspose.cells/style/is_formula_hidden) |表示当工作表受保护时是否隐藏公式。|
| [shrink_to_fit](/cells/python-net/zh/aspose.cells/style/shrink_to_fit) |表示文本是否自动缩小以适合可用的列宽。|
| [text_direction](/cells/python-net/zh/aspose.cells/style/text_direction) |代表文本阅读顺序。|
| [is_justify_distributed](/cells/python-net/zh/aspose.cells/style/is_justify_distributed) |指示是否应在文本的最后一行使用单元格对齐或分布式对齐。|
| [quote_prefix](/cells/python-net/zh/aspose.cells/style/quote_prefix) |指示单元格的值是否以单引号开头。|
| [is_gradient](/cells/python-net/zh/aspose.cells/style/is_gradient) |指示单元格底纹是否为渐变图案。|
| [is_percent](/cells/python-net/zh/aspose.cells/style/is_percent) |指示数字格式是否为百分比格式。|
| [is_date_time](/cells/python-net/zh/aspose.cells/style/is_date_time) |指示数字格式是否为日期格式。|


### 方法
|方法|描述|
| :- | :- |
| [set_border](/cells/python-net/zh/aspose.cells/style/set_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.pydrawing.Color) |设置样式的边框。|
| [set_border](/cells/python-net/zh/aspose.cells/style/set_border/#aspose.cells.BorderType-aspose.cells.CellBorderType-aspose.cells.CellsColor) |设置样式的边框。|
| [set_pattern_color](/cells/python-net/zh/aspose.cells/style/set_pattern_color/#aspose.cells.BackgroundType-aspose.pydrawing.Color-aspose.pydrawing.Color) |设置背景颜色。|
| [copy](/cells/python-net/zh/aspose.cells/style/copy/#aspose.cells.Style) |从另一个样式对象复制数据|
| [update](/cells/python-net/zh/aspose.cells/style/update/#) |将命名样式应用到使用该命名样式的单元格的样式。<br/>它的工作原理就像完成修改样式后单击“确定”按钮一样。<br/>仅适用于命名样式。|
| [is_modified](/cells/python-net/zh/aspose.cells/style/is_modified/#aspose.cells.StyleModifyFlag) |检查样式的指定属性是否已被修改。<br/>用于 ConditionalFormattings 的样式，以检查在单元格上应用 ConditionalFormattings 时是否应使用此样式的指定属性。|
| [set_custom](/cells/python-net/zh/aspose.cells/style/set_custom/#str-bool) |设置单元格的自定义数字格式字符串。|
| [set_two_color_gradient](/cells/python-net/zh/aspose.cells/style/set_two_color_gradient/#aspose.pydrawing.Color-aspose.pydrawing.Color-aspose.cells.drawing.GradientStyleType-int) |将指定的填充设置为双色渐变。|
| [get_two_color_gradient](/cells/python-net/zh/aspose.cells/style/get_two_color_gradient/#aspose.pydrawing.Color&-aspose.pydrawing.Color&-any-any) |获取双色渐变设置。|
| [get_two_color_gradient_setting](/cells/python-net/zh/aspose.cells/style/get_two_color_gradient_setting/#) |获取双色渐变设置。|
| [to_json](/cells/python-net/zh/aspose.cells/style/to_json/#) |将 [`Style`](/cells/python-net/zh/aspose.cells/style) 转换为 JSON 结构体数据。|



### 例子

```python
from aspose.cells import Workbook
from aspose.pydrawing import Color

workbook = Workbook()
sheets = workbook.worksheets
cell = sheets[0].cells.get("A1")
style = cell.get_style()
style.font.name = "Times New Roman"
style.font.color = Color.blue
cell.set_style(style)

```

### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`BorderCollection`](/cells/python-net/zh/aspose.cells/bordercollection)
* 类 [`Style`](/cells/python-net/zh/aspose.cells/style)
