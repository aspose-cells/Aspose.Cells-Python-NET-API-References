---
title: ContentTypePropertyCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 30
url: /zh/aspose.cells.properties/contenttypepropertycollection/
is_root: false
---
## ContentTypePropertyCollection类
代表附加信息的 [`ContentTypeProperty`](/cells/python-net/zh/aspose.cells.properties/contenttypeproperty) 个对象的集合。



ContentTypePropertyCollection 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells.properties/contenttypepropertycollection/capacity) |获取或设置数组列表可包含的元素数量。|


### 方法
|方法|描述|
| :- | :- |
| [`add(self, name, value)`](/cells/python-net/zh/aspose.cells.properties/contenttypepropertycollection/add/#str-str) |添加内容类型属性信息。|
| [`add(self, name, value, type)`](/cells/python-net/zh/aspose.cells.properties/contenttypepropertycollection/add/#str-str-str) |添加内容类型属性信息。|
| [`copy_to(self, array)`](/cells/python-net/zh/aspose.cells.properties/contenttypepropertycollection/copy_to/#list) |将整个数组列表复制到兼容的一维数组列表，从目标数组列表的开头开始。|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/zh/aspose.cells.properties/contenttypepropertycollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表中。|
| [`index_of(self, item, index)`](/cells/python-net/zh/aspose.cells.properties/contenttypepropertycollection/index_of/#aspose.cells.properties.contenttypeproperty-int) |搜索指定的对象并返回从指定索引延伸到最后一个元素的数组列表中元素范围内第一个出现的从零开始的索引。|
| [`index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells.properties/contenttypepropertycollection/index_of/#aspose.cells.properties.contenttypeproperty-int-int) |搜索指定的对象并返回从指定索引开始并包含指定数量元素的数组列表中元素范围内第一次出现的从零开始的索引。|
| [`last_index_of(self, item)`](/cells/python-net/zh/aspose.cells.properties/contenttypepropertycollection/last_index_of/#aspose.cells.properties.contenttypeproperty) |搜索指定的对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [`last_index_of(self, item, index)`](/cells/python-net/zh/aspose.cells.properties/contenttypepropertycollection/last_index_of/#aspose.cells.properties.contenttypeproperty-int) |搜索指定的对象并返回从第一个元素延伸到指定索引的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`last_index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells.properties/contenttypepropertycollection/last_index_of/#aspose.cells.properties.contenttypeproperty-int-int) |搜索指定的对象并返回包含指定数量的元素并以指定索引结束的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`get(self, name)`](/cells/python-net/zh/aspose.cells.properties/contenttypepropertycollection/get/#str) |通过属性名称获取内容类型属性。|
| [`binary_search(self, item)`](/cells/python-net/zh/aspose.cells.properties/contenttypepropertycollection/binary_search/#aspose.cells.properties.contenttypeproperty) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



### 例子

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Add a new property.
workbook.content_type_properties.add("Admin", "Aspose", "text")
# Save the Excel file
workbook.save("book1.xlsm")

```

### 也可以看看
* 模块[`aspose.cells.properties`](..)
* 类 [`ContentTypeProperty`](/cells/python-net/zh/aspose.cells.properties/contenttypeproperty)
