---
title: auto_size属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 80
url: /zh/aspose.cells/comment/auto_size/
is_root: false
---
## auto_size属性

指示注意事项的大小是否根据其内容自动调整。
注意：在某些特殊情况下（例如 Mac 环境），此设置可能不会生效。如果此设置不生效，请将其替换为 FitToTextSize()。

### 例子

```python

if notcomment1.auto_size:
    # The size of the comment varies with the content
    comment1.auto_size = True

```
### 定义：
```python
@property
def auto_size(self):
    ...
@auto_size.setter
def auto_size(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Comment`](/cells/python-net/zh/aspose.cells/comment)
