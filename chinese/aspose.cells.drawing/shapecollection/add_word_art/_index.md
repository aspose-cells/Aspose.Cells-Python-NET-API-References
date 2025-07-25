---
title: add_word_art方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 380
url: /zh/aspose.cells.drawing/shapecollection/add_word_art/
is_root: false
---
##  add_word_art(self, style, text, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.PresetWordArtStyle-str-int-int-int-int-int-int}
自 Excel 2007 起添加预设艺术字。


### 返回




```python

def add_word_art(self, style, text, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| style | [`PresetWordArtStyle`](/cells/python-net/zh/aspose.cells.drawing/presetwordartstyle) |预设的艺术字样式。|
| text | str |正文。|
| upper_left_row | int |左上行索引。|
| top | int |表示形状与其左行垂直方向的偏移量，以像素为单位。|
| upper_left_column | int |左上角的列索引。|
| left | int |表示形状与其左列的水平偏移量，以像素为单位。|
| height | int |表示形状的高度，以像素为单位。|
| width | int |表示形状的宽度，以像素为单位。|

### 例子

```python
from aspose.cells.drawing import PresetWordArtStyle

# add a WordArt
wordArt2 = shapes.add_word_art(PresetWordArtStyle.WORD_ART_STYLE1, "WordArt", 3, 0, 3, 0, 50, 200)

```



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`ShapeCollection`](/cells/python-net/zh/aspose.cells.drawing/shapecollection)
