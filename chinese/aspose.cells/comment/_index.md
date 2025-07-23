---
title: Comment类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 260
url: /zh/aspose.cells/comment/
is_root: false
---
## Comment类
封装代表单元格注释的对象。



Comment 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [author](/cells/python-net/zh/aspose.cells/comment/author) |获取并设置原始注意事项作者的名称|
| [comment_shape](/cells/python-net/zh/aspose.cells/comment/comment_shape) |获取表示附加到指定注意事项的形状的 Shape 对象。|
| [row](/cells/python-net/zh/aspose.cells/comment/row) |获取注意事项的行索引。|
| [column](/cells/python-net/zh/aspose.cells/comment/column) |获取注意事项的列索引。|
| [is_threaded_comment](/cells/python-net/zh/aspose.cells/comment/is_threaded_comment) |指示此注意事项是否为线索注意事项。|
| [threaded_comments](/cells/python-net/zh/aspose.cells/comment/threaded_comments) |获取主题注意事项列表；|
| [note](/cells/python-net/zh/aspose.cells/comment/note) |代表注意事项的内容。|
| [html_note](/cells/python-net/zh/aspose.cells/comment/html_note) |获取并设置该注意事项中包含数据和一些格式的html字符串。|
| [font](/cells/python-net/zh/aspose.cells/comment/font) |获取注意事项的字体。|
| [is_visible](/cells/python-net/zh/aspose.cells/comment/is_visible) |表示注意事项是否可见。|
| [text_orientation_type](/cells/python-net/zh/aspose.cells/comment/text_orientation_type) |获取并设置注意事项的文本方向类型。|
| [text_horizontal_alignment](/cells/python-net/zh/aspose.cells/comment/text_horizontal_alignment) |获取和设置注意事项的文本水平对齐类型。|
| [text_vertical_alignment](/cells/python-net/zh/aspose.cells/comment/text_vertical_alignment) |获取和设置注意事项的文本垂直对齐类型。|
| [auto_size](/cells/python-net/zh/aspose.cells/comment/auto_size) |指示注意事项的大小是否根据其内容自动调整。<br/>注意：在某些特殊情况下（例如 Mac 环境），此设置可能不会生效。如果此设置不生效，请将其替换为 FitToTextSize()。|
| [height_cm](/cells/python-net/zh/aspose.cells/comment/height_cm) |表示注意事项的高度，单位为厘米。|
| [width_cm](/cells/python-net/zh/aspose.cells/comment/width_cm) |表示注意事项的宽度，单位为厘米。|
| [width](/cells/python-net/zh/aspose.cells/comment/width) |表示注意事项的宽度，以像素为单位。|
| [height](/cells/python-net/zh/aspose.cells/comment/height) |表示注意事项的高度，以像素为单位。|
| [width_inch](/cells/python-net/zh/aspose.cells/comment/width_inch) |表示注释的宽度，单位为英寸。|
| [height_inch](/cells/python-net/zh/aspose.cells/comment/height_inch) |表示注意事项的高度，以英寸为单位。|


### 方法
|方法|描述|
| :- | :- |
| [`format_characters(self, start_index, length, font, flag)`](/cells/python-net/zh/aspose.cells/comment/format_characters/#int-int-aspose.cells.font-aspose.cells.styleflag) |使用字体设置来格式化一些字符。|
| [`characters(self, start_index, length)`](/cells/python-net/zh/aspose.cells/comment/characters/#int-int) |返回一个 Characters 对象，该对象代表注释文本内的字符范围。|
| [`get_characters(self)`](/cells/python-net/zh/aspose.cells/comment/get_characters/#) |返回所有 Characters 对象<br/>代表注释文本内的字符范围。|
| [`get_rich_formattings(self)`](/cells/python-net/zh/aspose.cells/comment/get_rich_formattings/#) |返回所有 Characters 对象<br/>代表注释文本内的字符范围。|



### 例子

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments
# Add comment to cell A1
commentIndex1 = comments.add(0, 0)
comment1 = comments[commentIndex1]
comment1.note = "First note."
comment1.font.name = "Times New Roman"
# Add comment to cell B2
comments.add("B2")
comment2 = comments.get("B2")
comment2.note = "Second note."
# do your business
# Save the excel file.
workbook.save("exmaple.xlsx")

```

### 也可以看看
* 模块[`aspose.cells`](..)
