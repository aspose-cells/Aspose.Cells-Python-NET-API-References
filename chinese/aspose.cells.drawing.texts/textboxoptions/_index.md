---
title: TextBoxOptions类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 80
url: /zh/aspose.cells.drawing.texts/textboxoptions/
is_root: false
---
## TextBoxOptions类
表示形状的文本选项



TextBoxOptions 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [shape_text_vertical_alignment](/cells/python-net/zh/aspose.cells.drawing.texts/textboxoptions/shape_text_vertical_alignment) |它对应于Excel中的“格式化形状-文本选项-文本框-垂直对齐方式”。|
| [resize_to_fit_text](/cells/python-net/zh/aspose.cells.drawing.texts/textboxoptions/resize_to_fit_text) |指示是否调整形状大小以适合文本|
| [shape_text_direction](/cells/python-net/zh/aspose.cells.drawing.texts/textboxoptions/shape_text_direction) |获取或设置给定文本主体内的文本显示方向。<br/>对应Excel中的“设置形状格式-文本选项-文本框-文本方向”|
| [left_margin_pt](/cells/python-net/zh/aspose.cells.drawing.texts/textboxoptions/left_margin_pt) |获取并设置左边距（以点为单位）。|
| [right_margin_pt](/cells/python-net/zh/aspose.cells.drawing.texts/textboxoptions/right_margin_pt) |获取并设置右边距（以点为单位）。|
| [top_margin_pt](/cells/python-net/zh/aspose.cells.drawing.texts/textboxoptions/top_margin_pt) |获取并设置以点为单位的上边距。|
| [bottom_margin_pt](/cells/python-net/zh/aspose.cells.drawing.texts/textboxoptions/bottom_margin_pt) |返回以点为单位的底部边距|
| [allow_text_to_overflow](/cells/python-net/zh/aspose.cells.drawing.texts/textboxoptions/allow_text_to_overflow) |是否允许文本溢出形状。|
| [wrap_text_in_shape](/cells/python-net/zh/aspose.cells.drawing.texts/textboxoptions/wrap_text_in_shape) |指定形状内的文本换行。<br/> False — 文本主体不会换行。<br/>真 - 文本主体将换行。|



### 例子

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
index = workbook.worksheets[0].text_boxes.add(0, 0, 350, 350)
shape = workbook.worksheets[0].text_boxes[index]
shape.text = "This is test."
# do your business
# Save the excel file.
workbook.save("exmaple.xlsx")

```

### 也可以看看
* 模块[`aspose.cells.drawing.texts`](..)
