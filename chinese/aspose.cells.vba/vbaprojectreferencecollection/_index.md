---
title: VbaProjectReferenceCollection类
second_title: Aspose.Cells for Python via .NET API 参考资料
description:
type: docs
weight: 50
url: /zh/aspose.cells.vba/vbaprojectreferencecollection/
is_root: false
---
## VbaProjectReferenceCollection类
表示 VBA 项目的所有引用。



VbaProjectReferenceCollection 类型公开了以下成员：

### 特性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells.vba/vbaprojectreferencecollection/capacity) |获取或设置数组列表可以包含的元素数。|


### 方法
|方法|描述|
| :- | :- |
| [copy_to(array)](/cells/python-net/zh/aspose.cells.vba/vbaprojectreferencecollection/copy_to/#list) |将整个数组列表复制到兼容的一维数组列表，从目标数组列表的开头开始。|
| [copy_to(index, array, array_index, count)](/cells/python-net/zh/aspose.cells.vba/vbaprojectreferencecollection/copy_to/#int-list-int-int) |将数组列表中的一系列元素复制到兼容的一维数组列表，从目标数组列表的指定索引开始。|
| [index_of(item, index)](/cells/python-net/zh/aspose.cells.vba/vbaprojectreferencecollection/index_of/#VbaProjectReference-int) |搜索指定的对象并返回数组列表中从指定索引延伸到最后一个元素的元素范围内第一次出现的从零开始的索引。|
| [index_of(item, index, count)](/cells/python-net/zh/aspose.cells.vba/vbaprojectreferencecollection/index_of/#VbaProjectReference-int-int) |搜索指定的对象并返回数组列表中从指定索引开始并包含指定数量的元素的元素范围内第一次出现的从零开始的索引。|
| [last_index_of(item)](/cells/python-net/zh/aspose.cells.vba/vbaprojectreferencecollection/last_index_of/#VbaProjectReference) |搜索指定的对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [last_index_of(item, index)](/cells/python-net/zh/aspose.cells.vba/vbaprojectreferencecollection/last_index_of/#VbaProjectReference-int) |搜索指定的对象并返回数组列表中从第一个元素到指定索引的元素范围内最后一次出现的从零开始的索引。|
| [last_index_of(item, index, count)](/cells/python-net/zh/aspose.cells.vba/vbaprojectreferencecollection/last_index_of/#VbaProjectReference-int-int) |搜索指定的对象并返回数组列表中包含指定数量的元素并以指定索引结束的元素范围内最后一次出现的从零开始的索引。|
| [add_registered_reference(name, libid)](/cells/python-net/zh/aspose.cells.vba/vbaprojectreferencecollection/add_registered_reference/#str-str) |添加对自动化类型库的引用。|
| [add_control_refrernce(name, libid, twiddledlibid, extended_libid)](/cells/python-net/zh/aspose.cells.vba/vbaprojectreferencecollection/add_control_refrernce/#str-str-str-str) |添加对旋转类型库及其扩展类型库的引用。|
| [add_project_refrernce(name, absolute_libid, relative_libid)](/cells/python-net/zh/aspose.cells.vba/vbaprojectreferencecollection/add_project_refrernce/#str-str-str) |添加对外部 VBA 项目的引用。|
| [binary_search(item)](/cells/python-net/zh/aspose.cells.vba/vbaprojectreferencecollection/binary_search/#VbaProjectReference) |使用默认比较器在整个排序数组列表中搜索元素，并返回元素的从零开始的索引。|



### 例子

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
#  Add vba project reference
vbaProject.references.add_registered_reference("stdole", "*\\G{00020430-0000-0000-C000-000000000046}#2.0#0#C:\\Windows\\system32\\stdole2.tlb#OLE Automation")
# Saving the Excel file
workbook.save("book1.xlsm")

```

### 也可以看看
* 模块 [aspose.cells.vba](..)
