---
title: ChartCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 60
url: /zh/aspose.cells.charts/chartcollection/
is_root: false
---
## ChartCollection类
封装了 [`Chart`](/cells/python-net/zh/aspose.cells.charts/chart) 对象的集合。



ChartCollection 类型公开以下成员：

### 特性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells.charts/chartcollection/capacity) |获取或设置数组列表可以包含的元素数。|


### 方法
|方法|描述|
| :- | :- |
| [add](/cells/python-net/zh/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.ChartType-int-int-int-int) |将图表添加到集合中。|
| [add](/cells/python-net/zh/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.ChartType-str-int-int-int-int) |将图表添加到集合中。|
| [add](/cells/python-net/zh/aspose.cells.charts/chartcollection/add/#bytes-str-bool-int-int-int-int) |添加带有预设模板的图表。|
| [add](/cells/python-net/zh/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.ChartType-str-bool-int-int-int-int) |将图表添加到集合中。|
| [get](/cells/python-net/zh/aspose.cells.charts/chartcollection/get/#int) |通过 .Net 添加 API for Python，因为不支持此[int index]|
| [get](/cells/python-net/zh/aspose.cells.charts/chartcollection/get/#str) |通过 .Net 添加 API for Python，因为不支持此[字符串图表]|
| [copy_to](/cells/python-net/zh/aspose.cells.charts/chartcollection/copy_to/#list) |从目标数组列表的开头开始，将整个数组列表复制到兼容的一维数组列表。|
| [copy_to](/cells/python-net/zh/aspose.cells.charts/chartcollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表。|
| [index_of](/cells/python-net/zh/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.Chart-int) |搜索指定对象并返回数组列表中从指定索引延伸到最后一个元素的元素范围内第一个匹配项的从零开始的索引。|
| [index_of](/cells/python-net/zh/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.Chart-int-int) |搜索指定对象并返回数组列表中从指定索引开始并包含指定数量元素的元素范围内第一个匹配项的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.Chart) |搜索指定对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.Chart-int) |搜索指定对象并返回数组列表中从第一个元素延伸到指定索引的元素范围内最后一次出现的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.Chart-int-int) |搜索指定的对象，并返回数组列表中包含指定数量的元素并以指定索引结束的元素范围内最后一个匹配项的从零开始的索引。|
| [add_floating_chart](/cells/python-net/zh/aspose.cells.charts/chartcollection/add_floating_chart/#aspose.cells.charts.ChartType-int-int-int-int) |将图表添加到集合中。|
| [binary_search](/cells/python-net/zh/aspose.cells.charts/chartcollection/binary_search/#aspose.cells.charts.Chart) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



### 例子

```python
from aspose.cells import Workbook

workbook = Workbook()
charts = workbook.worksheets[0].charts

```

### 也可以看看
* 模块[`aspose.cells.charts`](..)
* 类 [`Chart`](/cells/python-net/zh/aspose.cells.charts/chart)
