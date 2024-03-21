---
title: height_in_shape属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 450
url: /zh/aspose.cells.drawing/cellsdrawing/height_in_shape/
is_root: false
---
## height_in_shape属性

表示形状相对于父形状上边框的垂直偏移量，单位为父形状高度的1/4000。

### 评论

仅当此形状位于组或图表中时适用。

### 例子

```python

if shape.is_in_group and shape.height_in_shape == 4000:
    shape.height_in_shape = 2000

```
### 定义：
```python
@property
def height_in_shape(self):
    ...
@height_in_shape.setter
def height_in_shape(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`CellsDrawing`](/cells/python-net/zh/aspose.cells.drawing/cellsdrawing)
