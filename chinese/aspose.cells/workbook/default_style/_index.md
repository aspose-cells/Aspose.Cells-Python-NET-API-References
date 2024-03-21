---
title: default_style属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 550
url: /zh/aspose.cells/workbook/default_style/
is_root: false
---
## default_style属性

获取或设置工作簿的默认 [`Style`](/cells/python-net/zh/aspose.cells/style) 对象。

### 评论

DefaultStyle 属性对于实现整个工作簿的样式非常有用。

### 例子

以下代码创建并实例化一个新的工作簿，并为其设置默认值 [`Style`](/cells/python-net/zh/aspose.cells/style)。

```python
from aspose.cells import Workbook

workbook = Workbook()
defaultStyle = workbook.default_style
defaultStyle.font.name = "Tahoma"
workbook.default_style = defaultStyle

```
### 定义：
```python
@property
def default_style(self):
    ...
@default_style.setter
def default_style(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Style`](/cells/python-net/zh/aspose.cells/style)
* 类 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook)
