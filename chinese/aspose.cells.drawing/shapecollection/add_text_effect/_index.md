---
title: add_text_effect方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 360
url: /zh/aspose.cells.drawing/shapecollection/add_text_effect/
is_root: false
---
##  add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.MsoPresetTextEffect-str-str-int-bool-bool-int-int-int-int-int-int}
插入艺术字对象。


### 返回

返回代表新艺术字对象的 Shape 对象。


```python

def add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| effect | [`MsoPresetTextEffect`](/cells/python-net/zh/aspose.cells.drawing/msopresettexteffect) | Mso 预设的文本效果类型。|
| text | str |艺术字文本。|
| font_name | str |字体名称。|
| size | int |字体大小|
| font_bold | bool |指示字体是否为粗体。|
| font_italic | bool |指示字体是否为斜体。|
| upper_left_row | int |左上行索引。|
| top | int |表示形状与其左行垂直方向的偏移量，以像素为单位。|
| upper_left_column | int |左上角的列索引。|
| left | int |表示形状与其左列的水平偏移量，以像素为单位。|
| height | int |表示形状的高度，以像素为单位。|
| width | int |表示形状的宽度，以像素为单位。|

### 例子

```python
from aspose.cells.drawing import MsoPresetTextEffect

# add a WordArt
wordArt1 = shapes.add_text_effect(MsoPresetTextEffect.TEXT_EFFECT10, "WordArt", "arial", 18, False, False, 3, 0, 3, 0, 200, 50)

```



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`ShapeCollection`](/cells/python-net/zh/aspose.cells.drawing/shapecollection)
