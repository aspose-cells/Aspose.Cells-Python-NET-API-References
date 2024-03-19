---
title: width_scale属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1400
url: /zh/aspose.cells.drawing/picture/width_scale/
is_root: false
---
## width_scale属性

获取和设置宽度比例，以原始图片宽度的百分比为单位。
如果形状不是图片，则WidthScale属性仅返回100；

### 例子

```python

if shape.width_scale == 3:
    shape.width_scale = 1

```
### 定义：
```python
@property
def width_scale(self):
    ...
@width_scale.setter
def width_scale(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`Picture`](/cells/python-net/zh/aspose.cells.drawing/picture)
