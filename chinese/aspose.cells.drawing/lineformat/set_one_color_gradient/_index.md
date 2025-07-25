---
title: set_one_color_gradient方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells.drawing/lineformat/set_one_color_gradient/
is_root: false
---
##  set_one_color_gradient(self, color, degree, style, variant) {#aspose.pydrawing.Color-float-aspose.cells.drawing.GradientStyleType-int}
将指定的填充设置为单色渐变。
仅适用于 Excel 2007。



```python

def set_one_color_gradient(self, color, degree, style, variant):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| color | aspose.pydrawing.Color |一种渐变色。|
| degree | float |渐变程度。取值范围为 0.0（暗）到 1.0（亮）。|
| style | [`GradientStyleType`](/cells/python-net/zh/aspose.cells.drawing/gradientstyletype) |渐变阴影样式。|
| variant | int |渐变变量。可以是 1 到 4 之间的值，分别对应于“填充效果”对话框中“渐变”选项卡上的四个变量之一。如果 style 为 GradientStyle.FromCenter，则 Variant 参数只能为 1 或 2。|



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`LineFormat`](/cells/python-net/zh/aspose.cells.drawing/lineformat)
