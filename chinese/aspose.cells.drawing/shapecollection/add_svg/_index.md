---
title: add_svg方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 330
url: /zh/aspose.cells.drawing/shapecollection/add_svg/
is_root: false
---
##  add_svg(self, upper_left_row, top, upper_left_column, left, height, width, svg_data, compatible_image_data) {#int-int-int-int-int-int-bytes-bytes}
添加 svg 图像。


### 返回




```python

def add_svg(self, upper_left_row, top, upper_left_column, left, height, width, svg_data, compatible_image_data):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| upper_left_row | int |左上行索引。|
| top | int |表示形状与其左行垂直方向的偏移量，以像素为单位。|
| upper_left_column | int |左上角的列索引。|
| left | int |形状相对于其左列的水平偏移量，以像素为单位。|
| height | int |形状的高度，以像素为单位。|
| width | int |形状的宽度，以像素为单位。|
| svg_data | bytes | svg 图像数据。|
| compatible_image_data | bytes |从 svg 转换图像数据以便与 Excel 2016 或更低版本兼容。|

### 例子

```python
from aspose import pycore
import bytearray
import int

#  add a svg
with open("image.svg", "rb") as fs:
    len = pycore.cast(int, utils.filesize(fs))
    imageData = bytearray(len)
    fs.readinto(imageData)
    picture = shapes.add_svg(4, 0, 5, 0, -1, -1, imageData, None)

```



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`ShapeCollection`](/cells/python-net/zh/aspose.cells.drawing/shapecollection)
