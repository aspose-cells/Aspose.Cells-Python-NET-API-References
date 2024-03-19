---
title: last_index_of方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 90
url: /zh/aspose.cells.vba/vbamodulecollection/last_index_of/
is_root: false
---
##  last_index_of {#aspose.cells.vba.VbaModule}
搜索指定对象并返回整个数组列表中最后一次出现的从零开始的索引。


### 退货

整个数组列表中最后一次出现的值的从零开始的索引（如果找到）；否则，-1。


```python
def last_index_of(self, item):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| item | [`VbaModule`](/cells/python-net/zh/aspose.cells.vba/vbamodule) |要在数组列表中定位的对象。该值可以为空。|


##  last_index_of {#aspose.cells.vba.VbaModule-int}
搜索指定对象并返回数组列表中从第一个元素延伸到指定索引的元素范围内最后一次出现的从零开始的索引。


### 退货

数组列表中从第一个元素延伸到 startIndex 的元素范围内最后一次出现的值的从零开始的索引（如果找到）；否则，-1。


```python
def last_index_of(self, item, index):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| item | [`VbaModule`](/cells/python-net/zh/aspose.cells.vba/vbamodule) |要在数组列表中定位的对象。该值可以为空。|
| index | int |向后搜索的从零开始的起始索引。|


##  last_index_of {#aspose.cells.vba.VbaModule-int-int}
搜索指定的对象，并返回数组列表中包含指定数量的元素并以指定索引结束的元素范围内最后一个匹配项的从零开始的索引。


### 退货

System.Collections 中元素范围内最后一次出现的值的从零开始的索引。包含 count 个元素并以 startIndex 结束（如果找到）的数组列表；否则，-1。


```python
def last_index_of(self, item, index, count):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| item | [`VbaModule`](/cells/python-net/zh/aspose.cells.vba/vbamodule) |要在数组列表中定位的对象。该值可以为空。|
| index | int |向后搜索的从零开始的起始索引。|
| count | int |要搜索的部分中的元素数量。|



### 也可以看看
* 模块[`aspose.cells.vba`](../../)
* 类 [`VbaModuleCollection`](/cells/python-net/zh/aspose.cells.vba/vbamodulecollection)
