---
title: ConditionalFormattingIconCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 330
url: /zh/aspose.cells/conditionalformattingiconcollection/
is_root: false
---
## ConditionalFormattingIconCollection类
表示 [`ConditionalFormattingIcon`](/cells/python-net/zh/aspose.cells/conditionalformattingicon) 个对象的集合。



ConditionalFormattingIconCollection 类型公开以下成员：

### 特性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells/conditionalformattingiconcollection/capacity) |获取或设置数组列表可以包含的元素数。|


### 方法
|方法|描述|
| :- | :- |
| [add](/cells/python-net/zh/aspose.cells/conditionalformattingiconcollection/add/#aspose.cells.IconSetType-int) |添加 [`ConditionalFormattingIcon`](/cells/python-net/zh/aspose.cells/conditionalformattingicon) 对象。|
| [add](/cells/python-net/zh/aspose.cells/conditionalformattingiconcollection/add/#aspose.cells.ConditionalFormattingIcon) |添加 [`ConditionalFormattingIcon`](/cells/python-net/zh/aspose.cells/conditionalformattingicon) 对象。|
| [copy_to](/cells/python-net/zh/aspose.cells/conditionalformattingiconcollection/copy_to/#list) |从目标数组列表的开头开始，将整个数组列表复制到兼容的一维数组列表。|
| [copy_to](/cells/python-net/zh/aspose.cells/conditionalformattingiconcollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表。|
| [index_of](/cells/python-net/zh/aspose.cells/conditionalformattingiconcollection/index_of/#aspose.cells.ConditionalFormattingIcon-int) |搜索指定对象并返回数组列表中从指定索引延伸到最后一个元素的元素范围内第一个匹配项的从零开始的索引。|
| [index_of](/cells/python-net/zh/aspose.cells/conditionalformattingiconcollection/index_of/#aspose.cells.ConditionalFormattingIcon-int-int) |搜索指定对象并返回数组列表中从指定索引开始并包含指定数量元素的元素范围内第一个匹配项的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.ConditionalFormattingIcon) |搜索指定对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.ConditionalFormattingIcon-int) |搜索指定对象并返回数组列表中从第一个元素延伸到指定索引的元素范围内最后一次出现的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.ConditionalFormattingIcon-int-int) |搜索指定的对象，并返回数组列表中包含指定数量的元素并以指定索引结束的元素范围内最后一个匹配项的从零开始的索引。|
| [binary_search](/cells/python-net/zh/aspose.cells/conditionalformattingiconcollection/binary_search/#aspose.cells.ConditionalFormattingIcon) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



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
