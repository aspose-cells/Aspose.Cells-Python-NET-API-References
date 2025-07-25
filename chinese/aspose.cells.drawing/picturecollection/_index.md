---
title: PictureCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 440
url: /zh/aspose.cells.drawing/picturecollection/
is_root: false
---
## PictureCollection类
封装 [`Picture`](/cells/python-net/zh/aspose.cells.drawing/picture) 个对象的集合。



PictureCollection 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells.drawing/picturecollection/capacity) |获取或设置数组列表可包含的元素数量。|


### 方法
|方法|描述|
| :- | :- |
| [`add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream)`](/cells/python-net/zh/aspose.cells.drawing/picturecollection/add/#int-int-int-int-io.rawiobase) |将图片添加到收藏夹。|
| [`add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name)`](/cells/python-net/zh/aspose.cells.drawing/picturecollection/add/#int-int-int-int-str) |将图片添加到收藏夹。|
| [`add(self, upper_left_row, upper_left_column, stream)`](/cells/python-net/zh/aspose.cells.drawing/picturecollection/add/#int-int-io.rawiobase) |将图片添加到收藏夹。|
| [`add(self, upper_left_row, upper_left_column, file_name)`](/cells/python-net/zh/aspose.cells.drawing/picturecollection/add/#int-int-str) |将图片添加到收藏夹。|
| [`add(self, upper_left_row, upper_left_column, stream, width_scale, height_scale)`](/cells/python-net/zh/aspose.cells.drawing/picturecollection/add/#int-int-io.rawiobase-int-int) |将图片添加到收藏夹。|
| [`add(self, upper_left_row, upper_left_column, file_name, width_scale, height_scale)`](/cells/python-net/zh/aspose.cells.drawing/picturecollection/add/#int-int-str-int-int) |将图片添加到收藏夹。|
| [`copy_to(self, array)`](/cells/python-net/zh/aspose.cells.drawing/picturecollection/copy_to/#list) |将整个数组列表复制到兼容的一维数组列表，从目标数组列表的开头开始。|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/zh/aspose.cells.drawing/picturecollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表中。|
| [`index_of(self, item, index)`](/cells/python-net/zh/aspose.cells.drawing/picturecollection/index_of/#aspose.cells.drawing.picture-int) |搜索指定的对象并返回从指定索引延伸到最后一个元素的数组列表中元素范围内第一个出现的从零开始的索引。|
| [`index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells.drawing/picturecollection/index_of/#aspose.cells.drawing.picture-int-int) |搜索指定的对象并返回从指定索引开始并包含指定数量元素的数组列表中元素范围内第一次出现的从零开始的索引。|
| [`last_index_of(self, item)`](/cells/python-net/zh/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture) |搜索指定的对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [`last_index_of(self, item, index)`](/cells/python-net/zh/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture-int) |搜索指定的对象并返回从第一个元素延伸到指定索引的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`last_index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells.drawing/picturecollection/last_index_of/#aspose.cells.drawing.picture-int-int) |搜索指定的对象并返回包含指定数量的元素并以指定索引结束的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`camera(self, row, column, range)`](/cells/python-net/zh/aspose.cells.drawing/picturecollection/camera/#int-int-str) |拍摄该范围的照片。|
| [`binary_search(self, item)`](/cells/python-net/zh/aspose.cells.drawing/picturecollection/binary_search/#aspose.cells.drawing.picture) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



### 例子

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# get PictureCollection
pictures = workbook.worksheets[0].pictures
# do your business
# Save the excel file.
workbook.save("result.xlsx")

```

### 也可以看看
* 模块[`aspose.cells.drawing`](..)
* 类 [`Picture`](/cells/python-net/zh/aspose.cells.drawing/picture)
