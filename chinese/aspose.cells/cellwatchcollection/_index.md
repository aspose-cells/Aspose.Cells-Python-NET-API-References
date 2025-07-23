---
title: CellWatchCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 150
url: /zh/aspose.cells/cellwatchcollection/
is_root: false
---
## CellWatchCollection类
表示在“监视窗口”中监视的此工作表上的单元格集合。



CellWatchCollection 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells/cellwatchcollection/__init__/#) |构造一个新的 CellWatchCollection 实例|


### 属性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells/cellwatchcollection/capacity) |获取或设置数组列表可包含的元素数量。|


### 方法
|方法|描述|
| :- | :- |
| [`add(self, row, column)`](/cells/python-net/zh/aspose.cells/cellwatchcollection/add/#int-int) |将 [`CellWatch`](/cells/python-net/zh/aspose.cells/cellwatch) 与行和列相加。|
| [`add(self, cell_name)`](/cells/python-net/zh/aspose.cells/cellwatchcollection/add/#str) |添加单元格名称为 [`CellWatch`](/cells/python-net/zh/aspose.cells/cellwatch)。|
| [`copy_to(self, array)`](/cells/python-net/zh/aspose.cells/cellwatchcollection/copy_to/#list) |将整个数组列表复制到兼容的一维数组列表，从目标数组列表的开头开始。|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/zh/aspose.cells/cellwatchcollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表中。|
| [`index_of(self, item, index)`](/cells/python-net/zh/aspose.cells/cellwatchcollection/index_of/#aspose.cells.cellwatch-int) |搜索指定的对象并返回从指定索引延伸到最后一个元素的数组列表中元素范围内第一个出现的从零开始的索引。|
| [`index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells/cellwatchcollection/index_of/#aspose.cells.cellwatch-int-int) |搜索指定的对象并返回从指定索引开始并包含指定数量元素的数组列表中元素范围内第一次出现的从零开始的索引。|
| [`last_index_of(self, item)`](/cells/python-net/zh/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch) |搜索指定的对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [`last_index_of(self, item, index)`](/cells/python-net/zh/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch-int) |搜索指定的对象并返回从第一个元素延伸到指定索引的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`last_index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells/cellwatchcollection/last_index_of/#aspose.cells.cellwatch-int-int) |搜索指定的对象并返回包含指定数量的元素并以指定索引结束的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`get(self, cell_name)`](/cells/python-net/zh/aspose.cells/cellwatchcollection/get/#str) |通过单元格名称获取并设置 [`CellWatch`](/cells/python-net/zh/aspose.cells/cellwatch)。|
| [`binary_search(self, item)`](/cells/python-net/zh/aspose.cells/cellwatchcollection/binary_search/#aspose.cells.cellwatch) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



### 例子

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet.
sheet = workbook.worksheets[0]
#  Add Cell Watch Item into the watch window
sheet.cell_watches.add("B2")

```

### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`CellWatch`](/cells/python-net/zh/aspose.cells/cellwatch)
