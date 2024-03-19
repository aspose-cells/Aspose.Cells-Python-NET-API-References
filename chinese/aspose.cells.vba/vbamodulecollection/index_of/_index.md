---
title: index_of方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 80
url: /zh/aspose.cells.vba/vbamodulecollection/index_of/
is_root: false
---
##  index_of {#aspose.cells.vba.VbaModule-int}
搜索指定对象并返回数组列表中从指定索引延伸到最后一个元素的元素范围内第一个匹配项的从零开始的索引。


### 退货

数组列表中从 startIndex 延伸到最后一个元素的元素范围内 value 第一次出现的从零开始的索引（如果找到）；否则，-1。


```python
def index_of(self, item, index):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| item | [`VbaModule`](/cells/python-net/zh/aspose.cells.vba/vbamodule) |要在数组列表中定位的对象。该值可以为空。|
| index | int |搜索的从零开始的起始索引。 0（零）在空列表中有效。|


##  index_of {#aspose.cells.vba.VbaModule-int-int}
搜索指定对象并返回数组列表中从指定索引开始并包含指定数量元素的元素范围内第一个匹配项的从零开始的索引。


### 退货

数组列表中的元素范围内第一次出现的值的从零开始的索引，该索引从 startIndex 开始，包含 count 个元素（如果找到）；否则，-1。


```python
def index_of(self, item, index, count):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| item | [`VbaModule`](/cells/python-net/zh/aspose.cells.vba/vbamodule) |要在数组列表中定位的对象。该值可以为空。|
| index | int |搜索的从零开始的起始索引。 0（零）在空列表中有效。|
| count | int |要搜索的部分中的元素数量。|



### 也可以看看
* 模块[`aspose.cells.vba`](../../)
* 类 [`VbaModuleCollection`](/cells/python-net/zh/aspose.cells.vba/vbamodulecollection)
