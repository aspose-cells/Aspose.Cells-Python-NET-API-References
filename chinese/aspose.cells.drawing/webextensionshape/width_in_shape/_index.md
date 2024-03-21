---
title: width_in_shape属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1190
url: /zh/aspose.cells.drawing/webextensionshape/width_in_shape/
is_root: false
---
## width_in_shape属性

表示形状的宽度，单位为父形状的 1/4000。

### 评论

仅当此形状位于组或图表中时适用。

### 例子

```python

if shape.is_in_group and shape.width_in_shape == 2000:
    shape.width_in_shape = 4000

```
### 定义：
```python
@property
def width_in_shape(self):
    ...
@width_in_shape.setter
def width_in_shape(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`WebExtensionShape`](/cells/python-net/zh/aspose.cells.drawing/webextensionshape)
