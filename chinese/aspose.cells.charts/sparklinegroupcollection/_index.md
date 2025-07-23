---
title: SparklineGroupCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 300
url: /zh/aspose.cells.charts/sparklinegroupcollection/
is_root: false
---
## SparklineGroupCollection类
封装 [`SparklineGroup`](/cells/python-net/zh/aspose.cells.charts/sparklinegroup) 个对象的集合。



SparklineGroupCollection 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells.charts/sparklinegroupcollection/capacity) |获取或设置数组列表可包含的元素数量。|


### 方法
|方法|描述|
| :- | :- |
| [`add(self, type)`](/cells/python-net/zh/aspose.cells.charts/sparklinegroupcollection/add/#aspose.cells.charts.sparklinetype) |将 [`SparklineGroup`](/cells/python-net/zh/aspose.cells.charts/sparklinegroup) 和 [`Sparkline`](/cells/python-net/zh/aspose.cells.charts/sparkline) 添加到集合中。|
| [`add(self, type, data_range, is_vertical, location_range)`](/cells/python-net/zh/aspose.cells.charts/sparklinegroupcollection/add/#aspose.cells.charts.sparklinetype-str-bool-aspose.cells.cellarea) |将 [`SparklineGroup`](/cells/python-net/zh/aspose.cells.charts/sparklinegroup) 和 [`Sparkline`](/cells/python-net/zh/aspose.cells.charts/sparkline) 添加到集合中。|
| [`copy_to(self, array)`](/cells/python-net/zh/aspose.cells.charts/sparklinegroupcollection/copy_to/#list) |将整个数组列表复制到兼容的一维数组列表，从目标数组列表的开头开始。|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/zh/aspose.cells.charts/sparklinegroupcollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表中。|
| [`index_of(self, item, index)`](/cells/python-net/zh/aspose.cells.charts/sparklinegroupcollection/index_of/#aspose.cells.charts.sparklinegroup-int) |搜索指定的对象并返回从指定索引延伸到最后一个元素的数组列表中元素范围内第一个出现的从零开始的索引。|
| [`index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells.charts/sparklinegroupcollection/index_of/#aspose.cells.charts.sparklinegroup-int-int) |搜索指定的对象并返回从指定索引开始并包含指定数量元素的数组列表中元素范围内第一次出现的从零开始的索引。|
| [`last_index_of(self, item)`](/cells/python-net/zh/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup) |搜索指定的对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [`last_index_of(self, item, index)`](/cells/python-net/zh/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup-int) |搜索指定的对象并返回从第一个元素延伸到指定索引的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`last_index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup-int-int) |搜索指定的对象并返回包含指定数量的元素并以指定索引结束的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`clear_sparklines(self, cell_area)`](/cells/python-net/zh/aspose.cells.charts/sparklinegroupcollection/clear_sparklines/#aspose.cells.cellarea) |清除单元格区域内的迷你图。|
| [`clear_sparkline_groups(self, cell_area)`](/cells/python-net/zh/aspose.cells.charts/sparklinegroupcollection/clear_sparkline_groups/#aspose.cells.cellarea) |清除与单元格区域重叠的迷你图组。|
| [`binary_search(self, item)`](/cells/python-net/zh/aspose.cells.charts/sparklinegroupcollection/binary_search/#aspose.cells.charts.sparklinegroup) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



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
idx = sheet.sparkline_groups.add(SparklineType.LINE, "A1:D1", False, ca)
group = sheet.sparkline_groups[idx]
group.sparklines.add(sheet.name + "!A1:D1", 0, 4)
book.save("output.xlsx", SaveFormat.XLSX)

```

### 也可以看看
* 模块[`aspose.cells.charts`](..)
* 类 [`Sparkline`](/cells/python-net/zh/aspose.cells.charts/sparkline)
* 类 [`SparklineGroup`](/cells/python-net/zh/aspose.cells.charts/sparklinegroup)
