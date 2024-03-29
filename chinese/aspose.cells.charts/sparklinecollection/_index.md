---
title: SparklineCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 280
url: /zh/aspose.cells.charts/sparklinecollection/
is_root: false
---
## SparklineCollection类
封装了 [`Sparkline`](/cells/python-net/zh/aspose.cells.charts/sparkline) 对象的集合。



SparklineCollection 类型公开以下成员：

### 特性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells.charts/sparklinecollection/capacity) |获取或设置数组列表可以包含的元素数。|


### 方法
|方法|描述|
| :- | :- |
| [copy_to](/cells/python-net/zh/aspose.cells.charts/sparklinecollection/copy_to/#list) |从目标数组列表的开头开始，将整个数组列表复制到兼容的一维数组列表。|
| [copy_to](/cells/python-net/zh/aspose.cells.charts/sparklinecollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表。|
| [index_of](/cells/python-net/zh/aspose.cells.charts/sparklinecollection/index_of/#aspose.cells.charts.Sparkline-int) |搜索指定对象并返回数组列表中从指定索引延伸到最后一个元素的元素范围内第一个匹配项的从零开始的索引。|
| [index_of](/cells/python-net/zh/aspose.cells.charts/sparklinecollection/index_of/#aspose.cells.charts.Sparkline-int-int) |搜索指定对象并返回数组列表中从指定索引开始并包含指定数量元素的元素范围内第一个匹配项的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells.charts/sparklinecollection/last_index_of/#aspose.cells.charts.Sparkline) |搜索指定对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells.charts/sparklinecollection/last_index_of/#aspose.cells.charts.Sparkline-int) |搜索指定对象并返回数组列表中从第一个元素延伸到指定索引的元素范围内最后一次出现的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells.charts/sparklinecollection/last_index_of/#aspose.cells.charts.Sparkline-int-int) |搜索指定的对象，并返回数组列表中包含指定数量的元素并以指定索引结束的元素范围内最后一个匹配项的从零开始的索引。|
| [add](/cells/python-net/zh/aspose.cells.charts/sparklinecollection/add/#str-int-int) |添加迷你图。|
| [binary_search](/cells/python-net/zh/aspose.cells.charts/sparklinecollection/binary_search/#aspose.cells.charts.Sparkline) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



### 例子

```python
from aspose.cells import CellArea, SaveFormat, Workbook
from aspose.cells.charts import SparklineType

book = Workbook()
sheet = book.worksheets[0]
sheet.cells.get("A1").put_value(5)
sheet.cells.get("B1").put_value(2)
sheet.cells.get("C1").put_value(1)
sheet.cells.get("D1").put_value(3)
#  Define the CellArea
ca = CellArea()
ca.start_column = 4
ca.end_column = 4
ca.start_row = 0
ca.end_row = 0
idx = sheet.sparkline_group_collection.add(SparklineType.LINE, sheet.name + "!A1:D1", False, ca)
group = sheet.sparkline_group_collection[idx]
group.sparkline_collection.add(sheet.name + "!A1:D1", 0, 4)
book.save("output.xlsx", SaveFormat.XLSX)

```

### 也可以看看
* 模块[`aspose.cells.charts`](..)
* 类 [`Sparkline`](/cells/python-net/zh/aspose.cells.charts/sparkline)
