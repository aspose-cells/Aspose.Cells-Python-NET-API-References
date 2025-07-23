---
title: TextBoxCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 670
url: /zh/aspose.cells.drawing/textboxcollection/
is_root: false
---
## TextBoxCollection类
封装 [`TextBox`](/cells/python-net/zh/aspose.cells.drawing/textbox) 个对象的集合。



TextBoxCollection 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells.drawing/textboxcollection/capacity) |获取或设置数组列表可包含的元素数量。|


### 方法
|方法|描述|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/zh/aspose.cells.drawing/textboxcollection/copy_to/#list) |将整个数组列表复制到兼容的一维数组列表，从目标数组列表的开头开始。|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/zh/aspose.cells.drawing/textboxcollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表中。|
| [`index_of(self, item, index)`](/cells/python-net/zh/aspose.cells.drawing/textboxcollection/index_of/#aspose.cells.drawing.textbox-int) |搜索指定的对象并返回从指定索引延伸到最后一个元素的数组列表中元素范围内第一个出现的从零开始的索引。|
| [`index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells.drawing/textboxcollection/index_of/#aspose.cells.drawing.textbox-int-int) |搜索指定的对象并返回从指定索引开始并包含指定数量元素的数组列表中元素范围内第一次出现的从零开始的索引。|
| [`last_index_of(self, item)`](/cells/python-net/zh/aspose.cells.drawing/textboxcollection/last_index_of/#aspose.cells.drawing.textbox) |搜索指定的对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [`last_index_of(self, item, index)`](/cells/python-net/zh/aspose.cells.drawing/textboxcollection/last_index_of/#aspose.cells.drawing.textbox-int) |搜索指定的对象并返回从第一个元素延伸到指定索引的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`last_index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells.drawing/textboxcollection/last_index_of/#aspose.cells.drawing.textbox-int-int) |搜索指定的对象并返回包含指定数量的元素并以指定索引结束的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`get(self, name)`](/cells/python-net/zh/aspose.cells.drawing/textboxcollection/get/#str) |通过名称获取 [`TextBox`](/cells/python-net/zh/aspose.cells.drawing/textbox) 元素。|
| [`add(self, upper_left_row, upper_left_column, height, width)`](/cells/python-net/zh/aspose.cells.drawing/textboxcollection/add/#int-int-int-int) |将文本框添加到集合中。|
| [`binary_search(self, item)`](/cells/python-net/zh/aspose.cells.drawing/textboxcollection/binary_search/#aspose.cells.drawing.textbox) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



### 例子

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# get collection object
textBoxCollection = workbook.worksheets[0].text_boxes
# add a textbox
textBoxCollection.add(1, 1, 50, 100)
for tbox in textBoxCollection:
    pass

```

### 也可以看看
* 模块[`aspose.cells.drawing`](..)
* 类 [`TextBox`](/cells/python-net/zh/aspose.cells.drawing/textbox)
