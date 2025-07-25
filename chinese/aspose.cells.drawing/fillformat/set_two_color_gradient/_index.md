---
title: set_two_color_gradient方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 40
url: /zh/aspose.cells.drawing/fillformat/set_two_color_gradient/
is_root: false
---
##  set_two_color_gradient(self, color1, color2, style, variant) {#aspose.pydrawing.Color-aspose.pydrawing.Color-aspose.cells.drawing.GradientStyleType-int}
将指定的填充设置为双色渐变。
仅适用于 Excel 2007。



```python

def set_two_color_gradient(self, color1, color2, style, variant):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| color1 | aspose.pydrawing.Color |一种渐变色。|
| color2 | aspose.pydrawing.Color |两种渐变色。|
| style | [`GradientStyleType`](/cells/python-net/zh/aspose.cells.drawing/gradientstyletype) |渐变阴影样式。|
| variant | int |渐变变量。可以是 1 到 4 之间的值，分别对应于“填充效果”对话框中“渐变”选项卡上的四个变量之一。如果 style 为 GradientStyle.FromCenter，则 Variant 参数只能为 1 或 2。|


##  set_two_color_gradient(self, color1, transparency1, color2, transparency2, style, variant) {#aspose.pydrawing.Color-float-aspose.pydrawing.Color-float-aspose.cells.drawing.GradientStyleType-int}
将指定的填充设置为双色渐变。
仅适用于 Excel 2007。



```python

def set_two_color_gradient(self, color1, transparency1, color2, transparency2, style, variant):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| color1 | aspose.pydrawing.Color |一种渐变色。|
| transparency1 | float |颜色 1 的透明度，值范围是从 0.0（不透明）到 1.0（透明）。|
| color2 | aspose.pydrawing.Color |两种渐变色。|
| transparency2 | float |颜色 2 的透明度，值范围是从 0.0（不透明）到 1.0（透明）。|
| style | [`GradientStyleType`](/cells/python-net/zh/aspose.cells.drawing/gradientstyletype) |渐变阴影样式。|
| variant | int |渐变变量。可以是 1 到 4 之间的值，分别对应于“填充效果”对话框中“渐变”选项卡上的四个变量之一。如果 style 为 GradientStyle.FromCenter，则 Variant 参数只能为 1 或 2。|



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`FillFormat`](/cells/python-net/zh/aspose.cells.drawing/fillformat)
