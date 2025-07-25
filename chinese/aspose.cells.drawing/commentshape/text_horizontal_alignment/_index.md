---
title: text_horizontal_alignment属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 990
url: /zh/aspose.cells.drawing/commentshape/text_horizontal_alignment/
is_root: false
---
## text_horizontal_alignment属性

获取并设置形状的文本水平对齐类型。

### 例子

```python
from aspose.cells import TextAlignmentType

if shape.text_horizontal_alignment == TextAlignmentType.BOTTOM:
    shape.text_horizontal_alignment = TextAlignmentType.CENTER

```
### 定义：
```python
@property
def text_horizontal_alignment(self):
    ...
@text_horizontal_alignment.setter
def text_horizontal_alignment(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`CommentShape`](/cells/python-net/zh/aspose.cells.drawing/commentshape)
* 类 [`TextAlignmentType`](/cells/python-net/zh/aspose.cells/textalignmenttype)
