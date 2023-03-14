---
title: text_horizontal_overflow 属性
second_title: Aspose.Cells for Python via .NET API 参考资料
description:
type: docs
weight: 980
url: /zh/aspose.cells.drawing/groupbox/text_horizontal_overflow/
is_root: false
---
## text_horizontal_overflow 属性

获取和设置包含文本的形状的文本水平溢出类型。

### 例子

```python
from aspose.cells.drawing import TextOverflowType

if shape.text_horizontal_overflow == TextOverflowType.CLIP:
    shape.text_horizontal_overflow = TextOverflowType.OVERFLOW

```
### 定义：
```python
@property
def text_horizontal_overflow(self):
    ...
@text_horizontal_overflow.setter
def text_horizontal_overflow(self, value):
    ...
```

### 也可以看看
* 模块 [aspose.cells.drawing](../../)
* 类 [GroupBox](/cells/python-net/zh/aspose.cells.drawing/groupbox)
* 类 [TextOverflowType](/cells/python-net/zh/aspose.cells.drawing/textoverflowtype)
