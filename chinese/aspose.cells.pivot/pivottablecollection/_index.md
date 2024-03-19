---
title: PivotTableCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 190
url: /zh/aspose.cells.pivot/pivottablecollection/
is_root: false
---
## PivotTableCollection类
表示指定工作表上所有数据透视表对象的集合。



PivotTableCollection 类型公开以下成员：

### 特性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/capacity) |获取或设置数组列表可以包含的元素数。|


### 方法
|方法|描述|
| :- | :- |
| [add](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/add/#str-str-str) |将新的数据透视表缓存添加到 PivotCaches 集合中。|
| [add](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/add/#str-str-str-bool) |将新的数据透视表缓存添加到 PivotCaches 集合中。|
| [add](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str) |将新的数据透视表缓存添加到 PivotCaches 集合中。|
| [add](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/add/#str-int-int-str-bool) |将新的数据透视表缓存添加到 PivotCaches 集合中。|
| [add](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/add/#aspose.cells.pivot.PivotTable-str-str) |将新的数据透视表对象从另一个数据透视表添加到集合中。|
| [add](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/add/#aspose.cells.pivot.PivotTable-int-int-str) |将新的数据透视表对象从另一个数据透视表添加到集合中。|
| [add](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/add/#list-bool-aspose.cells.pivot.PivotPageFields-str-str) |将新的数据透视表对象添加到集合中，并将多个合并范围作为数据源。|
| [add](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/add/#list-bool-aspose.cells.pivot.PivotPageFields-int-int-str) |将新的数据透视表对象添加到集合中，并将多个合并范围作为数据源。|
| [copy_to](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/copy_to/#list) |从目标数组列表的开头开始，将整个数组列表复制到兼容的一维数组列表。|
| [copy_to](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表。|
| [index_of](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/index_of/#aspose.cells.pivot.PivotTable-int) |搜索指定对象并返回数组列表中从指定索引延伸到最后一个元素的元素范围内第一个匹配项的从零开始的索引。|
| [index_of](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/index_of/#aspose.cells.pivot.PivotTable-int-int) |搜索指定对象并返回数组列表中从指定索引开始并包含指定数量元素的元素范围内第一个匹配项的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.PivotTable) |搜索指定对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.PivotTable-int) |搜索指定对象并返回数组列表中从第一个元素延伸到指定索引的元素范围内最后一次出现的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/last_index_of/#aspose.cells.pivot.PivotTable-int-int) |搜索指定的对象，并返回数组列表中包含指定数量的元素并以指定索引结束的元素范围内最后一个匹配项的从零开始的索引。|
| [remove_at](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/remove_at/#int-bool) |删除指定索引处的数据透视表|
| [binary_search](/cells/python-net/zh/aspose.cells.pivot/pivottablecollection/binary_search/#aspose.cells.pivot.PivotTable) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



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
