---
title: text_orientation_type属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 210
url: /zh/aspose.cells/comment/text_orientation_type/
is_root: false
---
## text_orientation_type属性

获取和设置注释的文本方向类型。

### 例子

```python
from aspose.cells import TextOrientationType

if comment1.text_orientation_type == TextOrientationType.NO_ROTATION:
    comment1.text_orientation_type = TextOrientationType.TOP_TO_BOTTOM

```
### 定义：
```python
@property
def text_orientation_type(self):
    ...
@text_orientation_type.setter
def text_orientation_type(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Comment`](/cells/python-net/zh/aspose.cells/comment)
* 类 [`TextOrientationType`](/cells/python-net/zh/aspose.cells/textorientationtype)
