---
title: TimelineCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells.timelines/timelinecollection/
is_root: false
---
## TimelineCollection类
指定指定工作表上所有时间线对象的集合。
由于 MS Excel，Excel 2003 不支持时间线。



TimelineCollection 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells.timelines/timelinecollection/capacity) |获取或设置数组列表可包含的元素数量。|


### 方法
|方法|描述|
| :- | :- |
| [`add(self, pivot, row, column, base_field_name)`](/cells/python-net/zh/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-int-int-str) |使用数据透视表作为数据源添加新的时间线|
| [`add(self, pivot, dest_cell_name, base_field_name)`](/cells/python-net/zh/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-str-str) |使用数据透视表作为数据源添加新的时间线|
| [`add(self, pivot, row, column, base_field_index)`](/cells/python-net/zh/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-int-int-int) |使用数据透视表作为数据源添加新的时间线|
| [`add(self, pivot, dest_cell_name, base_field_index)`](/cells/python-net/zh/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-str-int) |使用数据透视表作为数据源添加新的时间线|
| [`add(self, pivot, row, column, base_field)`](/cells/python-net/zh/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-int-int-aspose.cells.pivot.pivotfield) |使用数据透视表作为数据源添加新的时间线|
| [`add(self, pivot, dest_cell_name, base_field)`](/cells/python-net/zh/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-str-aspose.cells.pivot.pivotfield) |使用数据透视表作为数据源添加新的时间线|
| [`copy_to(self, array)`](/cells/python-net/zh/aspose.cells.timelines/timelinecollection/copy_to/#list) |将整个数组列表复制到兼容的一维数组列表，从目标数组列表的开头开始。|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/zh/aspose.cells.timelines/timelinecollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表中。|
| [`index_of(self, item, index)`](/cells/python-net/zh/aspose.cells.timelines/timelinecollection/index_of/#aspose.cells.timelines.timeline-int) |搜索指定的对象并返回从指定索引延伸到最后一个元素的数组列表中元素范围内第一个出现的从零开始的索引。|
| [`index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells.timelines/timelinecollection/index_of/#aspose.cells.timelines.timeline-int-int) |搜索指定的对象并返回从指定索引开始并包含指定数量元素的数组列表中元素范围内第一次出现的从零开始的索引。|
| [`last_index_of(self, item)`](/cells/python-net/zh/aspose.cells.timelines/timelinecollection/last_index_of/#aspose.cells.timelines.timeline) |搜索指定的对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [`last_index_of(self, item, index)`](/cells/python-net/zh/aspose.cells.timelines/timelinecollection/last_index_of/#aspose.cells.timelines.timeline-int) |搜索指定的对象并返回从第一个元素延伸到指定索引的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`last_index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells.timelines/timelinecollection/last_index_of/#aspose.cells.timelines.timeline-int-int) |搜索指定的对象并返回包含指定数量的元素并以指定索引结束的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`get(self, name)`](/cells/python-net/zh/aspose.cells.timelines/timelinecollection/get/#str) |通过时间线的名称获取时间线。|
| [`binary_search(self, item)`](/cells/python-net/zh/aspose.cells.timelines/timelinecollection/binary_search/#aspose.cells.timelines.timeline) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



### 例子

```python
from aspose.cells import CellsFactory, Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType
from datetime import datetime

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
# Create date style
dateStyle = CellsFactory().create_style()
dateStyle.custom = "m/d/yyyy"
cells.get(0, 1).value = "date"
cells.get(1, 1).value = datetime(2021, 2, 5)
cells.get(2, 1).value = datetime(2022, 3, 8)
cells.get(3, 1).value = datetime(2023, 4, 10)
cells.get(4, 1).value = datetime(2024, 5, 16)
# Set date style
cells.get(1, 1).set_style(dateStyle)
cells.get(2, 1).set_style(dateStyle)
cells.get(3, 1).set_style(dateStyle)
cells.get(4, 1).set_style(dateStyle)
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
pivots = sheet.pivot_tables
# Add a PivotTable
pivotIndex = pivots.add("=Sheet1!A1:C5", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "date")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Refresh PivotTable data
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

### 也可以看看
* 模块[`aspose.cells.timelines`](..)
