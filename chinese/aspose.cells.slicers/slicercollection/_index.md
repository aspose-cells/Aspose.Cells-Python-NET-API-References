---
title: SlicerCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 50
url: /zh/aspose.cells.slicers/slicercollection/
is_root: false
---
## SlicerCollection类
指定指定工作表上所有 Slicer 对象的集合。



SlicerCollection 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells.slicers/slicercollection/capacity) |获取或设置数组列表可包含的元素数量。|


### 方法
|方法|描述|
| :- | :- |
| [`add(self, pivot, dest_cell_name, base_field_name)`](/cells/python-net/zh/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-str-str) |使用数据透视表作为数据源添加新的切片器|
| [`add(self, pivot, row, column, base_field_name)`](/cells/python-net/zh/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-int-int-str) |使用数据透视表作为数据源添加新的切片器|
| [`add(self, pivot, row, column, base_field_index)`](/cells/python-net/zh/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-int-int-int) |使用数据透视表作为数据源添加新的切片器|
| [`add(self, pivot, dest_cell_name, base_field_index)`](/cells/python-net/zh/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-str-int) |使用数据透视表作为数据源添加新的切片器|
| [`add(self, pivot, row, column, base_field)`](/cells/python-net/zh/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-int-int-aspose.cells.pivot.pivotfield) |使用数据透视表作为数据源添加新的切片器|
| [`add(self, pivot, dest_cell_name, base_field)`](/cells/python-net/zh/aspose.cells.slicers/slicercollection/add/#aspose.cells.pivot.pivottable-str-aspose.cells.pivot.pivotfield) |使用数据透视表作为数据源添加新的切片器|
| [`add(self, table, index, dest_cell_name)`](/cells/python-net/zh/aspose.cells.slicers/slicercollection/add/#aspose.cells.tables.listobject-int-str) |使用 ListObjet 作为数据源添加新的切片器|
| [`add(self, table, list_column, dest_cell_name)`](/cells/python-net/zh/aspose.cells.slicers/slicercollection/add/#aspose.cells.tables.listobject-aspose.cells.tables.listcolumn-str) |使用 ListObjet 作为数据源添加新的切片器|
| [`add(self, table, list_column, row, column)`](/cells/python-net/zh/aspose.cells.slicers/slicercollection/add/#aspose.cells.tables.listobject-aspose.cells.tables.listcolumn-int-int) |使用 ListObjet 作为数据源添加新的切片器|
| [`copy_to(self, array)`](/cells/python-net/zh/aspose.cells.slicers/slicercollection/copy_to/#list) |将整个数组列表复制到兼容的一维数组列表，从目标数组列表的开头开始。|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/zh/aspose.cells.slicers/slicercollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表中。|
| [`index_of(self, item, index)`](/cells/python-net/zh/aspose.cells.slicers/slicercollection/index_of/#aspose.cells.slicers.slicer-int) |搜索指定的对象并返回从指定索引延伸到最后一个元素的数组列表中元素范围内第一个出现的从零开始的索引。|
| [`index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells.slicers/slicercollection/index_of/#aspose.cells.slicers.slicer-int-int) |搜索指定的对象并返回从指定索引开始并包含指定数量元素的数组列表中元素范围内第一次出现的从零开始的索引。|
| [`last_index_of(self, item)`](/cells/python-net/zh/aspose.cells.slicers/slicercollection/last_index_of/#aspose.cells.slicers.slicer) |搜索指定的对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [`last_index_of(self, item, index)`](/cells/python-net/zh/aspose.cells.slicers/slicercollection/last_index_of/#aspose.cells.slicers.slicer-int) |搜索指定的对象并返回从第一个元素延伸到指定索引的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`last_index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells.slicers/slicercollection/last_index_of/#aspose.cells.slicers.slicer-int-int) |搜索指定的对象并返回包含指定数量的元素并以指定索引结束的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`get(self, name)`](/cells/python-net/zh/aspose.cells.slicers/slicercollection/get/#str) |通过切片器的名称获取切片器。|
| [`binary_search(self, item)`](/cells/python-net/zh/aspose.cells.slicers/slicercollection/binary_search/#aspose.cells.slicers.slicer) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



### 例子

```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
pivot.refresh_data()
pivot.calculate_data()
slicers = sheet.slicers
tableIndex = sheet.list_objects.add("A1", "C9", True)
table = sheet.list_objects[tableIndex]
# do your business
book.save("out.xlsx")

```

### 也可以看看
* 模块[`aspose.cells.slicers`](..)
