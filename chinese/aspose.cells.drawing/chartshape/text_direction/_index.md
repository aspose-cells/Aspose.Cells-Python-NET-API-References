---
title: text_direction 属性
second_title: Aspose.Cells for Python via .NET API 参考资料
description:
type: docs
weight: 940
url: /zh/aspose.cells.drawing/chartshape/text_direction/
is_root: false
---
## text_direction 属性

获取/设置此对象的文本流方向。

### 例子

```python
from aspose.cells import TextDirectionType

if shape.text_direction == TextDirectionType.CONTEXT:
    shape.text_direction = TextDirectionType.LEFT_TO_RIGHT

```
### 定义：
```python
@property
def text_direction(self):
    ...
@text_direction.setter
def text_direction(self, value):
    ...
```

### 也可以看看
* 模块 [aspose.cells.drawing](../../)
* 类 [ChartShape](/cells/python-net/zh/aspose.cells.drawing/chartshape)
* 类 [TextDirectionType](/cells/python-net/zh/aspose.cells/textdirectiontype)
