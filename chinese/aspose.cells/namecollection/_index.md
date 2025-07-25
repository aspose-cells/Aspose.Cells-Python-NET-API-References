---
title: NameCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1010
url: /zh/aspose.cells/namecollection/
is_root: false
---
## NameCollection类
表示电子表格中所有 [`Name`](/cells/python-net/zh/aspose.cells/name) 对象的集合。



NameCollection 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells/namecollection/capacity) |获取或设置数组列表可包含的元素数量。|


### 方法
|方法|描述|
| :- | :- |
| [`get(self, index)`](/cells/python-net/zh/aspose.cells/namecollection/get/#int) |通过 .Net 添加 API for Python，因为不支持 this[int index]|
| [`get(self, text)`](/cells/python-net/zh/aspose.cells/namecollection/get/#str) |通过 .Net 添加 API for Python，因为此[字符串文本]不受支持|
| [`copy_to(self, array)`](/cells/python-net/zh/aspose.cells/namecollection/copy_to/#list) |将整个数组列表复制到兼容的一维数组列表，从目标数组列表的开头开始。|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/zh/aspose.cells/namecollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表中。|
| [`index_of(self, item, index)`](/cells/python-net/zh/aspose.cells/namecollection/index_of/#aspose.cells.name-int) |搜索指定的对象并返回从指定索引延伸到最后一个元素的数组列表中元素范围内第一个出现的从零开始的索引。|
| [`index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells/namecollection/index_of/#aspose.cells.name-int-int) |搜索指定的对象并返回从指定索引开始并包含指定数量元素的数组列表中元素范围内第一次出现的从零开始的索引。|
| [`last_index_of(self, item)`](/cells/python-net/zh/aspose.cells/namecollection/last_index_of/#aspose.cells.name) |搜索指定的对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [`last_index_of(self, item, index)`](/cells/python-net/zh/aspose.cells/namecollection/last_index_of/#aspose.cells.name-int) |搜索指定的对象并返回从第一个元素延伸到指定索引的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`last_index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells/namecollection/last_index_of/#aspose.cells.name-int-int) |搜索指定的对象并返回包含指定数量的元素并以指定索引结束的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`add(self, text)`](/cells/python-net/zh/aspose.cells/namecollection/add/#str) |定义一个新名称。|
| [`filter(self, type, sheet_index)`](/cells/python-net/zh/aspose.cells/namecollection/filter/#aspose.cells.namescopetype-int) |按范围获取所有定义的名称。|
| [`remove_a_name(self, text)`](/cells/python-net/zh/aspose.cells/namecollection/remove_a_name/#str) |删除名称。|
| [`remove_names_by_array(self, names)`](/cells/python-net/zh/aspose.cells/namecollection/remove_names_by_array/#list) |删除名称数组|
| [`remove_duplicate_names(self)`](/cells/python-net/zh/aspose.cells/namecollection/remove_duplicate_names/#) |删除重复的定义名称|
| [`binary_search(self, item)`](/cells/python-net/zh/aspose.cells/namecollection/binary_search/#aspose.cells.name) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`Name`](/cells/python-net/zh/aspose.cells/name)
