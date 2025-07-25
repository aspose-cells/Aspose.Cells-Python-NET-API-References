---
title: VbaModuleCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells.vba/vbamodulecollection/
is_root: false
---
## VbaModuleCollection类
代表 [`VbaModule`](/cells/python-net/zh/aspose.cells.vba/vbamodule) 的列表



VbaModuleCollection 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells.vba/vbamodulecollection/capacity) |获取或设置数组列表可包含的元素数量。|


### 方法
|方法|描述|
| :- | :- |
| [`add(self, sheet)`](/cells/python-net/zh/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.worksheet) |为工作表添加模块。|
| [`add(self, type, name)`](/cells/python-net/zh/aspose.cells.vba/vbamodulecollection/add/#aspose.cells.vba.vbamoduletype-str) |添加模块。|
| [`get(self, index)`](/cells/python-net/zh/aspose.cells.vba/vbamodulecollection/get/#int) |通过索引获取列表中的[`VbaModule`](/cells/python-net/zh/aspose.cells.vba/vbamodule)。|
| [`get(self, name)`](/cells/python-net/zh/aspose.cells.vba/vbamodulecollection/get/#str) |根据名称在列表中获取 [`VbaModule`](/cells/python-net/zh/aspose.cells.vba/vbamodule)。|
| [`copy_to(self, array)`](/cells/python-net/zh/aspose.cells.vba/vbamodulecollection/copy_to/#list) |将整个数组列表复制到兼容的一维数组列表，从目标数组列表的开头开始。|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/zh/aspose.cells.vba/vbamodulecollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表中。|
| [`index_of(self, item, index)`](/cells/python-net/zh/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.vbamodule-int) |搜索指定的对象并返回从指定索引延伸到最后一个元素的数组列表中元素范围内第一个出现的从零开始的索引。|
| [`index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells.vba/vbamodulecollection/index_of/#aspose.cells.vba.vbamodule-int-int) |搜索指定的对象并返回从指定索引开始并包含指定数量元素的数组列表中元素范围内第一次出现的从零开始的索引。|
| [`last_index_of(self, item)`](/cells/python-net/zh/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule) |搜索指定的对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [`last_index_of(self, item, index)`](/cells/python-net/zh/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule-int) |搜索指定的对象并返回从第一个元素延伸到指定索引的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`last_index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells.vba/vbamodulecollection/last_index_of/#aspose.cells.vba.vbamodule-int-int) |搜索指定的对象并返回包含指定数量的元素并以指定索引结束的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`add_designer_storage(self, name, data)`](/cells/python-net/zh/aspose.cells.vba/vbamodulecollection/add_designer_storage/#str-bytes) |  |
| [`get_designer_storage(self, name)`](/cells/python-net/zh/aspose.cells.vba/vbamodulecollection/get_designer_storage/#str) |代表设计师的数据。|
| [`add_user_form(self, name, codes, designer_storage)`](/cells/python-net/zh/aspose.cells.vba/vbamodulecollection/add_user_form/#str-str-bytes) |将用户表单插入 VBA 项目。|
| [`remove_by_worksheet(self, sheet)`](/cells/python-net/zh/aspose.cells.vba/vbamodulecollection/remove_by_worksheet/#aspose.cells.worksheet) |删除工作表的模块。|
| [`remove_by_name(self, name)`](/cells/python-net/zh/aspose.cells.vba/vbamodulecollection/remove_by_name/#str) |按名称删除模块|
| [`binary_search(self, item)`](/cells/python-net/zh/aspose.cells.vba/vbamodulecollection/binary_search/#aspose.cells.vba.vbamodule) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



### 例子

```python
from aspose.cells import Workbook
from aspose.cells.vba import VbaModuleType

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
#  Add a new module.
vbaProject.modules.add(VbaModuleType.CLASS, "test")
# Saving the Excel file
workbook.save("book1.xlsm")

```

### 也可以看看
* 模块[`aspose.cells.vba`](..)
* 类 [`VbaModule`](/cells/python-net/zh/aspose.cells.vba/vbamodule)
