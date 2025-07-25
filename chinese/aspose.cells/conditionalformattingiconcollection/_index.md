---
title: ConditionalFormattingIconCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 300
url: /zh/aspose.cells/conditionalformattingiconcollection/
is_root: false
---
## ConditionalFormattingIconCollection类
表示 [`ConditionalFormattingIcon`](/cells/python-net/zh/aspose.cells/conditionalformattingicon) 个对象的集合。



ConditionalFormattingIconCollection 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells/conditionalformattingiconcollection/capacity) |获取或设置数组列表可包含的元素数量。|


### 方法
|方法|描述|
| :- | :- |
| [`add(self, type, index)`](/cells/python-net/zh/aspose.cells/conditionalformattingiconcollection/add/#aspose.cells.iconsettype-int) |添加 [`ConditionalFormattingIcon`](/cells/python-net/zh/aspose.cells/conditionalformattingicon) 对象。|
| [`add(self, cficon)`](/cells/python-net/zh/aspose.cells/conditionalformattingiconcollection/add/#aspose.cells.conditionalformattingicon) |添加 [`ConditionalFormattingIcon`](/cells/python-net/zh/aspose.cells/conditionalformattingicon) 对象。|
| [`copy_to(self, array)`](/cells/python-net/zh/aspose.cells/conditionalformattingiconcollection/copy_to/#list) |将整个数组列表复制到兼容的一维数组列表，从目标数组列表的开头开始。|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/zh/aspose.cells/conditionalformattingiconcollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表中。|
| [`index_of(self, item, index)`](/cells/python-net/zh/aspose.cells/conditionalformattingiconcollection/index_of/#aspose.cells.conditionalformattingicon-int) |搜索指定的对象并返回从指定索引延伸到最后一个元素的数组列表中元素范围内第一个出现的从零开始的索引。|
| [`index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells/conditionalformattingiconcollection/index_of/#aspose.cells.conditionalformattingicon-int-int) |搜索指定的对象并返回从指定索引开始并包含指定数量元素的数组列表中元素范围内第一次出现的从零开始的索引。|
| [`last_index_of(self, item)`](/cells/python-net/zh/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.conditionalformattingicon) |搜索指定的对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [`last_index_of(self, item, index)`](/cells/python-net/zh/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.conditionalformattingicon-int) |搜索指定的对象并返回从第一个元素延伸到指定索引的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`last_index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.conditionalformattingicon-int-int) |搜索指定的对象并返回包含指定数量的元素并以指定索引结束的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`binary_search(self, item)`](/cells/python-net/zh/aspose.cells/conditionalformattingiconcollection/binary_search/#aspose.cells.conditionalformattingicon) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



### 例子

```python
from aspose.cells import CellArea, FormatConditionType, IconSetType, Workbook

# Instantiating a Workbook object
workbook = Workbook()
sheet = workbook.worksheets[0]
# Get Conditional Formatting
cformattings = sheet.conditional_formattings
# Adds an empty conditional formatting
index = cformattings.add()
# Get newly added Conditional formatting
fcs = cformattings[index]
# Sets the conditional format range.
ca = CellArea()
ca.start_row = 0
ca.end_row = 0
ca.start_column = 0
ca.end_column = 0
fcs.add_area(ca)
ca = CellArea()
ca.start_row = 1
ca.end_row = 1
ca.start_column = 1
ca.end_column = 1
fcs.add_area(ca)
# Sets condition
idx = fcs.add_condition(FormatConditionType.ICON_SET)
cond = fcs[idx]
# Sets condition's type
cond.icon_set.type = IconSetType.ARROWS_GRAY3
# Add custom iconset condition.
cfIcon = cond.icon_set.cf_icons[0]
cfIcon.type = IconSetType.ARROWS3
cfIcon.index = 0
cfIcon1 = cond.icon_set.cf_icons[1]
cfIcon1.type = IconSetType.ARROWS_GRAY3
cfIcon1.index = 1
cfIcon2 = cond.icon_set.cf_icons[2]
cfIcon2.type = IconSetType.BOXES5
cfIcon2.index = 2
# Saving the Excel file
workbook.save("output.xls")

```

### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`ConditionalFormattingIcon`](/cells/python-net/zh/aspose.cells/conditionalformattingicon)
