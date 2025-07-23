---
title: set_desired_size方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells.rendering/svgimageoptions/set_desired_size/
is_root: false
---
##  set_desired_size(self, desired_width, desired_height) {#int-int}
设置所需的图像宽度和高度。



```python

def set_desired_size(self, desired_width, desired_height):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| desired_width | int |所需宽度（以像素为单位）|
| desired_height | int |所需高度（以像素为单位）|
### 注意事项

注意：此成员现已过时。相反，
请通过将参数 keepAspectRatio 设置为 false 来使用 [`ImageOrPrintOptions.set_desired_size`](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions/set_desired_size)。
该房产将于 2023 年 5 月起 12 个月后拆除。
Aspose 对于您所遇到的不便深表歉意。

##  set_desired_size(self, desired_width, desired_height, keep_aspect_ratio) {#int-int-bool}
设置所需的图像宽度和高度。



```python

def set_desired_size(self, desired_width, desired_height, keep_aspect_ratio):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| desired_width | int |所需宽度（以像素为单位）|
| desired_height | int |所需高度（以像素为单位）|
| keep_aspect_ratio | bool |是否保持原始图像的宽高比|
### 注意事项

输出图像的宽度和高度（以像素为单位）仅基于
设置所需的宽度和高度。


[`ImageOrPrintOptions.horizontal_resolution`](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions#horizontal_resolution) 和 [`ImageOrPrintOptions.vertical_resolution`](/cells/python-net/zh/aspose.cells.rendering/imageorprintoptions#vertical_resolution) 
在这种情况下不会影响输出图像的宽度和高度。


### 也可以看看
* 模块[`aspose.cells.rendering`](../../)
* 类 [`SvgImageOptions`](/cells/python-net/zh/aspose.cells.rendering/svgimageoptions)
