---
title: PivotTableCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 250
url: /zh/aspose.cells.pivot/pivottablecollection/
is_root: false
---
## PivotTableCollection类
代表指定工作表上所有数据透视表对象的集合。



PivotTableCollection 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/capacity) |获取或设置数组列表可包含的元素数量。|


### 方法
|方法|描述|
| :- | :- |
| [`add(self, source_data, dest_cell_name, table_name)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/add/#str-str-str) |添加一个新的数据透视表。|
| [`add(self, source_data, dest_cell_name, table_name, use_same_source)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/add/#str-str-str-bool) |添加一个新的数据透视表。|
| [`add(self, source_data, row, column, table_name)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str) |添加一个新的数据透视表。|
| [`add(self, source_data, row, column, table_name, use_same_source)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str-bool) |添加一个新的数据透视表。|
| [`add(self, source_data, row, column, table_name, use_same_source, is_xls_classic)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str-bool-bool) |添加一个新的数据透视表。|
| [`add(self, source_data, cell, table_name, use_same_source, is_xls_classic)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/add/#str-str-str-bool-bool) |添加一个新的数据透视表。|
| [`add(self, pivot_table, dest_cell_name, table_name)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/add/#aspose.cells.pivot.pivottable-str-str) |根据另一个数据透视表添加一个新的数据透视表。|
| [`add(self, pivot_table, row, column, table_name)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/add/#aspose.cells.pivot.pivottable-int-int-str) |根据另一个数据透视表添加一个新的数据透视表。|
| [`add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/add/#list-bool-aspose.cells.pivot.pivotpagefields-str-str) |将新的数据透视表对象添加到具有多个合并范围作为数据源的集合中。|
| [`add(self, source_data, is_auto_page, page_fields, row, column, table_name)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/add/#list-bool-aspose.cells.pivot.pivotpagefields-int-int-str) |将新的数据透视表对象添加到具有多个合并范围作为数据源的集合中。|
| [`copy_to(self, array)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/copy_to/#list) |将整个数组列表复制到兼容的一维数组列表，从目标数组列表的开头开始。|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表中。|
| [`index_of(self, item, index)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/index_of/#aspose.cells.pivot.pivottable-int) |搜索指定的对象并返回从指定索引延伸到最后一个元素的数组列表中元素范围内第一个出现的从零开始的索引。|
| [`index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/index_of/#aspose.cells.pivot.pivottable-int-int) |搜索指定的对象并返回从指定索引开始并包含指定数量元素的数组列表中元素范围内第一次出现的从零开始的索引。|
| [`last_index_of(self, item)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.pivottable) |搜索指定的对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [`last_index_of(self, item, index)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.pivottable-int) |搜索指定的对象并返回从第一个元素延伸到指定索引的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`last_index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.pivottable-int-int) |搜索指定的对象并返回包含指定数量的元素并以指定索引结束的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`get(self, name)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/get/#str) |通过数据透视表的名称获取数据透视表报告。|
| [`remove_pivot_table(self, pivot_table)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/remove_pivot_table/#aspose.cells.pivot.pivottable) |删除指定的数据透视表并删除数据透视表数据|
| [`remove_pivot_table_data(self, pivot_table, keep_data)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/remove_pivot_table_data/#aspose.cells.pivot.pivottable-bool) |删除指定的数据透视表|
| [`remove_by_index(self, index)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/remove_by_index/#int) |删除指定索引处的数据透视表并删除数据透视表数据|
| [`remove_at(self, index, keep_data)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/remove_at/#int-bool) |删除指定索引处的数据透视表|
| [`binary_search(self, item)`](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/binary_search/#aspose.cells.pivot.pivottable) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



### 例子

```python
from aspose.cells import FormatConditionType, OperatorType, Workbook
from aspose.cells.pivot import PivotFieldType, PivotFilterType, PivotTableStyleType
from aspose.pydrawing import Color

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
# Change PivotField's attributes
rowField = pivot.row_fields[0]
rowField.display_name = "custom display name"
# Add PivotFilter
index = pivot.pivot_filters.add(0, PivotFilterType.COUNT)
filter = pivot.pivot_filters[index]
filter.auto_filter.filter_top10(0, False, False, 2)
# Add PivotFormatCondition
formatIndex = pivot.pivot_format_conditions.add()
pfc = pivot.pivot_format_conditions[formatIndex]
fcc = pfc.format_conditions
fcc.add_area(pivot.data_body_range)
idx = fcc.add_condition(FormatConditionType.CELL_VALUE)
fc = fcc[idx]
fc.formula1 = "100"
fc.operator = OperatorType.GREATER_OR_EQUAL
fc.style.background_color = Color.red
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

### 也可以看看
* 模块[`aspose.cells.pivot`](..)
