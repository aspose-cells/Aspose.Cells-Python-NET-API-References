---
title: is_locked属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 740
url: /zh/aspose.cells.drawing/oleobject/is_locked/
is_root: false
---
## is_locked属性

如果对象被锁定，则为 True；如果在工作表受保护时可以修改对象，则为 False。

### 例子

```python

if shape.is_locked:
    shape.is_locked = False

```
### 定义：
```python
@property
def is_locked(self):
    ...
@is_locked.setter
def is_locked(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`OleObject`](/cells/python-net/zh/aspose.cells.drawing/oleobject)
