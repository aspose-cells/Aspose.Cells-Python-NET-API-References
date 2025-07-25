---
title: horizontal_resolution属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 180
url: /zh/aspose.cells.rendering/svgimageoptions/horizontal_resolution/
is_root: false
---
## horizontal_resolution属性

获取或设置生成图像的水平分辨率（以每英寸点数为单位）。

### 注意事项

默认值为 96。


设置 [`ImageOrPrintOptions.horizontal_resolution`](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions#horizontal_resolution) 和 [`ImageOrPrintOptions.vertical_resolution`](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions#vertical_resolution) 
影响输出图像的宽度和高度（以像素为单位）。

### 例子

以下代码将分辨率设置为192，生成的图像的宽度和高度是
分辨率保留为默认值 96。

```python
from aspose.cells import Workbook
from aspose.cells.drawing import ImageType
from aspose.cells.rendering import ImageOrPrintOptions, SheetRender

wb = Workbook("Book1.xlsx")
opts = ImageOrPrintOptions()
# Set output image type: png.
opts.image_type = ImageType.PNG
# Set resolution to 192.
opts.horizontal_resolution = 192
opts.vertical_resolution = 192
# Render worksheet page to image.
sr = SheetRender(wb.worksheets[0], opts)
sr.to_image(0, "Sheet_Page1.png")

```
### 定义：
```python
@property
def horizontal_resolution(self):
    ...
@horizontal_resolution.setter
def horizontal_resolution(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.rendering`](../../)
* 类 [`SvgImageOptions`](/cells/python-net/zh/aspose.cells.rendering/svgimageoptions)
