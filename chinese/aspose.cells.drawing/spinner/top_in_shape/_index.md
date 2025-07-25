---
title: top_in_shape属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1150
url: /zh/aspose.cells.drawing/spinner/top_in_shape/
is_root: false
---
## top_in_shape属性

表示形状与父形状顶部边框的垂直偏移量，
以父图形高度的 1/4000 为单位。

### 注意事项

仅当此形状位于组或图表中时适用。

### 例子

```python

if shape.is_in_group and shape.top_in_shape == 8000:
    shape.top_in_shape = 4000

```
### 定义：
```python
@property
def top_in_shape(self):
    ...
@top_in_shape.setter
def top_in_shape(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`Spinner`](/cells/python-net/zh/aspose.cells.drawing/spinner)
