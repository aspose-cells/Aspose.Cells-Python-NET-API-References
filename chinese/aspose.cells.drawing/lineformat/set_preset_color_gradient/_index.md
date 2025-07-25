---
title: set_preset_color_gradient方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 30
url: /zh/aspose.cells.drawing/lineformat/set_preset_color_gradient/
is_root: false
---
##  set_preset_color_gradient(self, preset_color, style, variant) {#aspose.cells.drawing.GradientPresetType-aspose.cells.drawing.GradientStyleType-int}
将指定的填充设置为预设颜色渐变。
仅适用于 Excel 2007。



```python

def set_preset_color_gradient(self, preset_color, style, variant):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| preset_color | [`GradientPresetType`](/cells/python-net/zh/aspose.cells.drawing/gradientpresettype) |预设颜色类型|
| style | [`GradientStyleType`](/cells/python-net/zh/aspose.cells.drawing/gradientstyletype) |渐变阴影样式。|
| variant | int |渐变变量。可以是 1 到 4 之间的值，分别对应于“填充效果”对话框中“渐变”选项卡上的四个变量之一。如果 style 为 GradientStyle.FromCenter，则 Variant 参数只能为 1 或 2。|



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`LineFormat`](/cells/python-net/zh/aspose.cells.drawing/lineformat)
