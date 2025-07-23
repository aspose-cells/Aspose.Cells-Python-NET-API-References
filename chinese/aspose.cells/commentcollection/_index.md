---
title: CommentCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 270
url: /zh/aspose.cells/commentcollection/
is_root: false
---
## CommentCollection类
封装 [`Comment`](/cells/python-net/zh/aspose.cells/comment) 个对象的集合。



CommentCollection 类型公开以下成员：

### 属性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells/commentcollection/capacity) |获取或设置数组列表可包含的元素数量。|


### 方法
|方法|描述|
| :- | :- |
| [`add_threaded_comment(self, row, column, text, author)`](/cells/python-net/zh/aspose.cells/commentcollection/add_threaded_comment/#int-int-str-aspose.cells.threadedcommentauthor) |添加线索注意事项。|
| [`add_threaded_comment(self, cell_name, text, author)`](/cells/python-net/zh/aspose.cells/commentcollection/add_threaded_comment/#str-str-aspose.cells.threadedcommentauthor) |添加线索注意事项。|
| [`get_threaded_comments(self, row, column)`](/cells/python-net/zh/aspose.cells/commentcollection/get_threaded_comments/#int-int) |按行和列索引获取线程注意事项。|
| [`get_threaded_comments(self, cell_name)`](/cells/python-net/zh/aspose.cells/commentcollection/get_threaded_comments/#str) |根据单元格名称获取线程注意事项。|
| [`add(self, row, column)`](/cells/python-net/zh/aspose.cells/commentcollection/add/#int-int) |向集合中添加注意事项。|
| [`add(self, cell_name)`](/cells/python-net/zh/aspose.cells/commentcollection/add/#str) |向集合中添加注意事项。|
| [`get(self, row, column)`](/cells/python-net/zh/aspose.cells/commentcollection/get/#int-int) |通过 .Net 添加 API for Python，因为 this[int, int] 不受支持|
| [`get(self, index)`](/cells/python-net/zh/aspose.cells/commentcollection/get/#int) |获取指定索引处的 [`Comment`](/cells/python-net/zh/aspose.cells/comment) 元素。|
| [`get(self, cell_name)`](/cells/python-net/zh/aspose.cells/commentcollection/get/#str) |获取指定单元格处的 [`Comment`](/cells/python-net/zh/aspose.cells/comment) 元素。|
| [`remove_at(self, cell_name)`](/cells/python-net/zh/aspose.cells/commentcollection/remove_at/#str) |删除特定单元格的注释。|
| [`remove_at(self, row, column)`](/cells/python-net/zh/aspose.cells/commentcollection/remove_at/#int-int) |删除特定单元格的注释。|
| [`copy_to(self, array)`](/cells/python-net/zh/aspose.cells/commentcollection/copy_to/#list) |将整个数组列表复制到兼容的一维数组列表，从目标数组列表的开头开始。|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/zh/aspose.cells/commentcollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表中。|
| [`index_of(self, item, index)`](/cells/python-net/zh/aspose.cells/commentcollection/index_of/#aspose.cells.comment-int) |搜索指定的对象并返回从指定索引延伸到最后一个元素的数组列表中元素范围内第一个出现的从零开始的索引。|
| [`index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells/commentcollection/index_of/#aspose.cells.comment-int-int) |搜索指定的对象并返回从指定索引开始并包含指定数量元素的数组列表中元素范围内第一次出现的从零开始的索引。|
| [`last_index_of(self, item)`](/cells/python-net/zh/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment) |搜索指定的对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [`last_index_of(self, item, index)`](/cells/python-net/zh/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment-int) |搜索指定的对象并返回从第一个元素延伸到指定索引的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`last_index_of(self, item, index, count)`](/cells/python-net/zh/aspose.cells/commentcollection/last_index_of/#aspose.cells.comment-int-int) |搜索指定的对象并返回包含指定数量的元素并以指定索引结束的数组列表中元素范围内的最后一个出现的从零开始的索引。|
| [`binary_search(self, item)`](/cells/python-net/zh/aspose.cells/commentcollection/binary_search/#aspose.cells.comment) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



### 例子

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments

```

### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`Comment`](/cells/python-net/zh/aspose.cells/comment)
