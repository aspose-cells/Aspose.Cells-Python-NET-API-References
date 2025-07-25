---
title: tiff_color_depth属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 370
url: /zh/aspose.cells.rendering/imageorprintoptions/tiff_color_depth/
is_root: false
---
## tiff_color_depth属性

获取或设置仅在将页面保存为 `Tiff` 格式时应用的位深度。

### 注意事项

仅当保存为 TIFF 时才有效。
如果 TiffCompression 设置为 CCITT3、CCITT4，则此项不会生效，生成的 tiff 图像的位深度将始终为 1。
### 定义：
```python
@property
def tiff_color_depth(self):
    ...
@tiff_color_depth.setter
def tiff_color_depth(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.rendering`](../../)
* 类 [`ColorDepth`](/cells/python-net/zh/aspose.cells.rendering/colordepth)
* 类 [`ImageOrPrintOptions`](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions)
