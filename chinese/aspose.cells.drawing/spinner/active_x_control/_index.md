---
title: active_x_control属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 270
url: /zh/aspose.cells.drawing/spinner/active_x_control/
is_root: false
---
## active_x_control属性

获取 ActiveX 控件。

### 例子

```python
from aspose import pycore
from aspose.cells.drawing.activexcontrols import CheckBoxActiveXControl

if shape.active_x_control != None:
    checkBox1 = pycore.cast(CheckBoxActiveXControl, shape.active_x_control)
    # The font name of CheckBox
    fontName = checkBox1.font.name

```
### 定义：
```python
@property
def active_x_control(self):
    ...
```

### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`Spinner`](/cells/python-net/zh/aspose.cells.drawing/spinner)
