---
title: is_locked属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 620
url: /zh/aspose.cells.drawing/label/is_locked/
is_root: false
---
## is_locked属性

 True 表示当工作表受到保护时，对象不能被修改。
请注意，仅当工作表或工作表中的对象受到保护时，此值才有意义。

### 例子

```python

# Sets the specified shape to unlocked state
if shape.worksheet.is_protected and shape.is_locked:
    shape.is_locked = False
# Sets the specified shape to a locked state
if shape.worksheet.is_protected and notshape.is_locked:
    shape.is_locked = True

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
* 类 [`Label`](/cells/python-net/zh/aspose.cells.drawing/label)
