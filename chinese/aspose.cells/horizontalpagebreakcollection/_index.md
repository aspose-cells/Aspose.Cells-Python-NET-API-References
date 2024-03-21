---
title: HorizontalPageBreakCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 790
url: /zh/aspose.cells/horizontalpagebreakcollection/
is_root: false
---
## HorizontalPageBreakCollection类
封装了 [`HorizontalPageBreak`](/cells/python-net/zh/aspose.cells/horizontalpagebreak) 对象的集合。



HorizontalPageBreakCollection 类型公开以下成员：

### 特性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells/horizontalpagebreakcollection/capacity) |获取或设置数组列表可以包含的元素数。|


### 方法
|方法|描述|
| :- | :- |
| [add](/cells/python-net/zh/aspose.cells/horizontalpagebreakcollection/add/#int-int-int) |向集合添加水平分页符。|
| [add](/cells/python-net/zh/aspose.cells/horizontalpagebreakcollection/add/#int) |向集合添加水平分页符。|
| [add](/cells/python-net/zh/aspose.cells/horizontalpagebreakcollection/add/#int-int) |向集合添加水平分页符。|
| [add](/cells/python-net/zh/aspose.cells/horizontalpagebreakcollection/add/#str) |向集合添加水平分页符。|
| [copy_to](/cells/python-net/zh/aspose.cells/horizontalpagebreakcollection/copy_to/#list) |从目标数组列表的开头开始，将整个数组列表复制到兼容的一维数组列表。|
| [copy_to](/cells/python-net/zh/aspose.cells/horizontalpagebreakcollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表。|
| [index_of](/cells/python-net/zh/aspose.cells/horizontalpagebreakcollection/index_of/#aspose.cells.HorizontalPageBreak-int) |搜索指定对象并返回数组列表中从指定索引延伸到最后一个元素的元素范围内第一个匹配项的从零开始的索引。|
| [index_of](/cells/python-net/zh/aspose.cells/horizontalpagebreakcollection/index_of/#aspose.cells.HorizontalPageBreak-int-int) |搜索指定对象并返回数组列表中从指定索引开始并包含指定数量元素的元素范围内第一个匹配项的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.HorizontalPageBreak) |搜索指定对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.HorizontalPageBreak-int) |搜索指定对象并返回数组列表中从第一个元素延伸到指定索引的元素范围内最后一次出现的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells/horizontalpagebreakcollection/last_index_of/#aspose.cells.HorizontalPageBreak-int-int) |搜索指定的对象，并返回数组列表中包含指定数量的元素并以指定索引结束的元素范围内最后一个匹配项的从零开始的索引。|
| [binary_search](/cells/python-net/zh/aspose.cells/horizontalpagebreakcollection/binary_search/#aspose.cells.HorizontalPageBreak) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



### 例子

```python
from aspose.cells import Workbook

excel = Workbook()
# Add a pagebreak at G5
excel.worksheets[0].horizontal_page_breaks.add("G5")
excel.worksheets[0].vertical_page_breaks.add("G5")

```

### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`HorizontalPageBreak`](/cells/python-net/zh/aspose.cells/horizontalpagebreak)
