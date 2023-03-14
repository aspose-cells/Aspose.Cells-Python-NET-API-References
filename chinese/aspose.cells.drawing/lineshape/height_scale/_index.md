---
title: height_scale 属性
second_title: Aspose.Cells for Python via .NET API 参考资料
description:
type: docs
weight: 530
url: /zh/aspose.cells.drawing/lineshape/height_scale/
is_root: false
---
## height_scale 属性

获取和设置高度比例，单位为原始图片高度的百分比。
如果形状不是图片，HeightScale 属性只返回 100；

### 例子

```python

if shape.height_scale == 3:
    shape.height_scale = 1

```
### 定义：
```python
@property
def height_scale(self):
    ...
@height_scale.setter
def height_scale(self, value):
    ...
```

### 也可以看看
* 模块 [aspose.cells.drawing](../../)
* 类 [LineShape](/cells/python-net/zh/aspose.cells.drawing/lineshape)
