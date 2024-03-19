---
title: text_vertical_alignment属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 220
url: /zh/aspose.cells/comment/text_vertical_alignment/
is_root: false
---
## text_vertical_alignment属性

获取和设置注释的文本垂直对齐类型。

### 例子

```python
from aspose.cells import TextAlignmentType

if comment1.text_vertical_alignment == TextAlignmentType.FILL:
    comment1.text_vertical_alignment = TextAlignmentType.CENTER

```
### 定义：
```python
@property
def text_vertical_alignment(self):
    ...
@text_vertical_alignment.setter
def text_vertical_alignment(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Comment`](/cells/python-net/zh/aspose.cells/comment)
* 类 [`TextAlignmentType`](/cells/python-net/zh/aspose.cells/textalignmenttype)
