---
title: HyperlinkCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 850
url: /zh/aspose.cells/hyperlinkcollection/
is_root: false
---
## HyperlinkCollection类
封装了 [`Hyperlink`](/cells/python-net/zh/aspose.cells/hyperlink) 对象的集合。



HyperlinkCollection 类型公开以下成员：

### 特性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells/hyperlinkcollection/capacity) |获取或设置数组列表可以包含的元素数。|


### 方法
|方法|描述|
| :- | :- |
| [add](/cells/python-net/zh/aspose.cells/hyperlinkcollection/add/#int-int-int-int-str) |添加指向指定单元格或单元格区域的超链接。|
| [add](/cells/python-net/zh/aspose.cells/hyperlinkcollection/add/#str-int-int-str) |添加指向指定单元格或单元格区域的超链接。|
| [add](/cells/python-net/zh/aspose.cells/hyperlinkcollection/add/#str-str-str-str-str) |添加指向指定单元格或单元格区域的超链接。|
| [copy_to](/cells/python-net/zh/aspose.cells/hyperlinkcollection/copy_to/#list) |从目标数组列表的开头开始，将整个数组列表复制到兼容的一维数组列表。|
| [copy_to](/cells/python-net/zh/aspose.cells/hyperlinkcollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表。|
| [index_of](/cells/python-net/zh/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.Hyperlink-int) |搜索指定对象并返回数组列表中从指定索引延伸到最后一个元素的元素范围内第一个匹配项的从零开始的索引。|
| [index_of](/cells/python-net/zh/aspose.cells/hyperlinkcollection/index_of/#aspose.cells.Hyperlink-int-int) |搜索指定对象并返回数组列表中从指定索引开始并包含指定数量元素的元素范围内第一个匹配项的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink) |搜索指定对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink-int) |搜索指定对象并返回数组列表中从第一个元素延伸到指定索引的元素范围内最后一次出现的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells/hyperlinkcollection/last_index_of/#aspose.cells.Hyperlink-int-int) |搜索指定的对象，并返回数组列表中包含指定数量的元素并以指定索引结束的元素范围内最后一个匹配项的从零开始的索引。|
| [binary_search](/cells/python-net/zh/aspose.cells/hyperlinkcollection/binary_search/#aspose.cells.Hyperlink) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



### 例子

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Get Hyperlinks Collection
hyperlinks = worksheet.hyperlinks
# Adding a hyperlink to a URL at "A1" cell
hyperlinks.add("A1", 1, 1, "http://www.aspose.com")
# Saving the Excel file
workbook.save("book1.xls")

```

### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`Hyperlink`](/cells/python-net/zh/aspose.cells/hyperlink)
