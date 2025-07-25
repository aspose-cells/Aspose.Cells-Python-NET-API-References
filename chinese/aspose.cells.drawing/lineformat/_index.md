---
title: LineFormat类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 280
url: /zh/aspose.cells.drawing/lineformat/
is_root: false
---
## LineFormat类
代表线路的所有设置。



**继承：** [`LineFormat`](/cells/python-net/aspose.cells.drawing/lineformat) → 
[`FillFormat`](/cells/python-net/zh/aspose.cells.drawing/fillformat)



LineFormat 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [type](/cells/python-net/zh/aspose.cells.drawing/lineformat/type) |获取并设置填充类型。|
| [fill_type](/cells/python-net/zh/aspose.cells.drawing/lineformat/fill_type) |获取并设置填充类型|
| [transparency](/cells/python-net/zh/aspose.cells.drawing/lineformat/transparency) |返回或设置该区域的透明度，范围是 0.0（不透明）到 1.0（透明）。|
| [set_type](/cells/python-net/zh/aspose.cells.drawing/lineformat/set_type) |获取填充格式集类型。|
| [gradient_fill](/cells/python-net/zh/aspose.cells.drawing/lineformat/gradient_fill) |获取 [`FillFormat.gradient_fill`](/cells/python-net/zh/aspose.cells.drawing/fillformat#gradient_fill) 对象。|
| [texture_fill](/cells/python-net/zh/aspose.cells.drawing/lineformat/texture_fill) |获取 [`FillFormat.texture_fill`](/cells/python-net/zh/aspose.cells.drawing/fillformat#texture_fill) 对象。|
| [solid_fill](/cells/python-net/zh/aspose.cells.drawing/lineformat/solid_fill) |获取 [`FillFormat.solid_fill`](/cells/python-net/zh/aspose.cells.drawing/fillformat#solid_fill) 对象。|
| [pattern_fill](/cells/python-net/zh/aspose.cells.drawing/lineformat/pattern_fill) |获取 [`FillFormat.pattern_fill`](/cells/python-net/zh/aspose.cells.drawing/fillformat#pattern_fill) 对象。|
| [gradient_color_type](/cells/python-net/zh/aspose.cells.drawing/lineformat/gradient_color_type) |返回指定填充的渐变颜色类型。|
| [gradient_style](/cells/python-net/zh/aspose.cells.drawing/lineformat/gradient_style) |返回指定填充的渐变样式。|
| [gradient_color1](/cells/python-net/zh/aspose.cells.drawing/lineformat/gradient_color1) |返回指定填充的渐变颜色 1。|
| [gradient_color2](/cells/python-net/zh/aspose.cells.drawing/lineformat/gradient_color2) |返回指定填充的渐变颜色 2。|
| [gradient_degree](/cells/python-net/zh/aspose.cells.drawing/lineformat/gradient_degree) |返回指定填充的渐变度。<br/>仅适用于 Excel 2007。|
| [gradient_variant](/cells/python-net/zh/aspose.cells.drawing/lineformat/gradient_variant) |返回指定填充的渐变变体。<br/>仅适用于 Excel 2007。|
| [preset_color](/cells/python-net/zh/aspose.cells.drawing/lineformat/preset_color) |返回指定填充的渐变预设颜色。|
| [texture](/cells/python-net/zh/aspose.cells.drawing/lineformat/texture) |表示指定填充的纹理类型。|
| [pattern](/cells/python-net/zh/aspose.cells.drawing/lineformat/pattern) |表示某个区域的显示模式。|
| [picture_format_type](/cells/python-net/zh/aspose.cells.drawing/lineformat/picture_format_type) |获取和设置图片格式类型。|
| [scale](/cells/python-net/zh/aspose.cells.drawing/lineformat/scale) |获取和设置图片格式比例。|
| [image_data](/cells/python-net/zh/aspose.cells.drawing/lineformat/image_data) |获取和设置图片图像数据。|
| [compound_type](/cells/python-net/zh/aspose.cells.drawing/lineformat/compound_type) |指定线复合类型。|
| [dash_style](/cells/python-net/zh/aspose.cells.drawing/lineformat/dash_style) |指定线虚线类型。|
| [cap_type](/cells/python-net/zh/aspose.cells.drawing/lineformat/cap_type) |指定结束大写。|
| [join_type](/cells/python-net/zh/aspose.cells.drawing/lineformat/join_type) |指定线连接类型。|
| [begin_arrowhead_style](/cells/python-net/zh/aspose.cells.drawing/lineformat/begin_arrowhead_style) |获取并设置线的开始箭头类型。|
| [begin_arrowhead_width](/cells/python-net/zh/aspose.cells.drawing/lineformat/begin_arrowhead_width) |获取并设置线的起始箭头宽度类型。|
| [begin_arrowhead_length](/cells/python-net/zh/aspose.cells.drawing/lineformat/begin_arrowhead_length) |获取并设置线的起始箭头长度类型。|
| [end_arrowhead_style](/cells/python-net/zh/aspose.cells.drawing/lineformat/end_arrowhead_style) |获取并设置线的终止箭头类型。|
| [end_arrowhead_width](/cells/python-net/zh/aspose.cells.drawing/lineformat/end_arrowhead_width) |获取并设置线的末端箭头宽度类型。|
| [end_arrowhead_length](/cells/python-net/zh/aspose.cells.drawing/lineformat/end_arrowhead_length) |获取并设置线的末端箭头长度类型。|
| [weight](/cells/python-net/zh/aspose.cells.drawing/lineformat/weight) |获取或设置线的粗细（以点为单位）。|


### 方法
|方法|描述|
| :- | :- |
| [`set_two_color_gradient(self, color1, color2, style, variant)`](/cells/python-net/zh/aspose.cells.drawing/lineformat/set_two_color_gradient/#aspose.pydrawing.color-aspose.pydrawing.color-aspose.cells.drawing.gradientstyletype-int) |将指定的填充设置为双色渐变。<br/>仅适用于 Excel 2007。|
| [`set_two_color_gradient(self, color1, transparency1, color2, transparency2, style, variant)`](/cells/python-net/zh/aspose.cells.drawing/lineformat/set_two_color_gradient/#aspose.pydrawing.color-float-aspose.pydrawing.color-float-aspose.cells.drawing.gradientstyletype-int) |将指定的填充设置为双色渐变。<br/>仅适用于 Excel 2007。|
| [`set_one_color_gradient(self, color, degree, style, variant)`](/cells/python-net/zh/aspose.cells.drawing/lineformat/set_one_color_gradient/#aspose.pydrawing.color-float-aspose.cells.drawing.gradientstyletype-int) |将指定的填充设置为单色渐变。<br/>仅适用于 Excel 2007。|
| [`set_preset_color_gradient(self, preset_color, style, variant)`](/cells/python-net/zh/aspose.cells.drawing/lineformat/set_preset_color_gradient/#aspose.cells.drawing.gradientpresettype-aspose.cells.drawing.gradientstyletype-int) |将指定的填充设置为预设颜色渐变。<br/>仅适用于 Excel 2007。|



### 例子

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
shapes = workbook.worksheets[0].shapes
shape = shapes.add_rectangle(1, 0, 1, 0, 50, 100)
lineFmt = shape.line

```

### 也可以看看
* 模块[`aspose.cells.drawing`](..)
* 类 [`FillFormat`](/cells/python-net/zh/aspose.cells.drawing/fillformat)
* 类 [`LineFormat`](/cells/python-net/zh/aspose.cells.drawing/lineformat)
