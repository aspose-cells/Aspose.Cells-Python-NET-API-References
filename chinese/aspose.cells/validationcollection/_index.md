---
title: ValidationCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1530
url: /zh/aspose.cells/validationcollection/
is_root: false
---
## ValidationCollection类
表示数据验证集合。



ValidationCollection 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells/validationcollection/capacity) |获取或设置数组列表可包含的元素数量。|


### 方法
|方法|描述|
| :- | :- |
| [`add(self)`](/cells/python-net/zh/aspose.cells/validationcollection/add/#) |向集合添加数据验证。|
| [`add(self, ca)`](/cells/python-net/zh/aspose.cells/validationcollection/add/#aspose.cells.cellarea) |向集合添加数据验证。|
| [`copy_to(self, array)`](/cells/python-net/zh/aspose.cells/validationcollection/copy_to/#list) |将整个数组列表复制到兼容的一维数组列表，从目标数组列表的开头开始。|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/zh/aspose.cells/validationcollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表中。|
| [`index_of(self, item, index)`](/cells/python-net/zh/aspose.cells/validationcollection/index_of/#aspose.cells.validation-int) |搜索指定的对象并返回从指定索引延伸到最后一个元素的数组列表中元素范围内第一个出现的从零开始的索引。|
| [`index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells/validationcollection/index_of/#aspose.cells.validation-int-int) |搜索指定的对象并返回从指定索引开始并包含指定数量元素的数组列表中元素范围内第一次出现的从零开始的索引。|
| [`last_index_of(self, item)`](/cells/python-net/zh/aspose.cells/validationcollection/last_index_of/#aspose.cells.validation) |搜索指定的对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [`last_index_of(self, item, index)`](/cells/python-net/zh/aspose.cells/validationcollection/last_index_of/#aspose.cells.validation-int) |搜索指定的对象并返回从第一个元素延伸到指定索引的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`last_index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells/validationcollection/last_index_of/#aspose.cells.validation-int-int) |搜索指定的对象并返回包含指定数量的元素并以指定索引结束的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`remove_a_cell(self, row, column)`](/cells/python-net/zh/aspose.cells/validationcollection/remove_a_cell/#int-int) |删除单元格上的所有验证设置。|
| [`remove_area(self, ca)`](/cells/python-net/zh/aspose.cells/validationcollection/remove_area/#aspose.cells.cellarea) |删除范围内的所有验证设置。|
| [`get_validation_in_cell(self, row, column)`](/cells/python-net/zh/aspose.cells/validationcollection/get_validation_in_cell/#int-int) |获取应用于给定单元格的验证。|
| [`binary_search(self, item)`](/cells/python-net/zh/aspose.cells/validationcollection/binary_search/#aspose.cells.validation) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



### 例子

```python
from aspose.cells import CellArea, ValidationType, Workbook

workbook = Workbook()
validations = workbook.worksheets[0].validations
area = CellArea.create_cell_area(0, 0, 1, 1)
validation = validations[validations.add(area)]
validation.type = ValidationType.LIST
validation.formula1 = "a,b,c,d"

```

### 也可以看看
* 模块[`aspose.cells`](..)
