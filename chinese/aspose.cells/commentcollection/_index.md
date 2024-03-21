---
title: CommentCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 300
url: /zh/aspose.cells/commentcollection/
is_root: false
---
## CommentCollection类
封装了 [`Comment`](/cells/python-net/zh/aspose.cells/comment) 对象的集合。



CommentCollection 类型公开以下成员：

### 特性
|属性|描述|
| :- | :- |
| [capacity](/cells/python-net/zh/aspose.cells/commentcollection/capacity) |获取或设置数组列表可以包含的元素数。|


### 方法
|方法|描述|
| :- | :- |
| [add_threaded_comment](/cells/python-net/zh/aspose.cells/commentcollection/add_threaded_comment/#int-int-str-aspose.cells.ThreadedCommentAuthor) |添加线索评论。|
| [add_threaded_comment](/cells/python-net/zh/aspose.cells/commentcollection/add_threaded_comment/#str-str-aspose.cells.ThreadedCommentAuthor) |添加线索评论。|
| [get_threaded_comments](/cells/python-net/zh/aspose.cells/commentcollection/get_threaded_comments/#int-int) |按行和列索引获取线索注释。|
| [get_threaded_comments](/cells/python-net/zh/aspose.cells/commentcollection/get_threaded_comments/#str) |按单元名称获取线程注释。|
| [add](/cells/python-net/zh/aspose.cells/commentcollection/add/#int-int) |向集合添加评论。|
| [add](/cells/python-net/zh/aspose.cells/commentcollection/add/#str) |向集合添加评论。|
| [remove_at](/cells/python-net/zh/aspose.cells/commentcollection/remove_at/#str) |删除特定单元格的注释。|
| [remove_at](/cells/python-net/zh/aspose.cells/commentcollection/remove_at/#int-int) |删除特定单元格的注释。|
| [copy_to](/cells/python-net/zh/aspose.cells/commentcollection/copy_to/#list) |从目标数组列表的开头开始，将整个数组列表复制到兼容的一维数组列表。|
| [copy_to](/cells/python-net/zh/aspose.cells/commentcollection/copy_to/#int-list-int-int) |从目标数组列表的指定索引开始，将数组列表中的一系列元素复制到兼容的一维数组列表。|
| [index_of](/cells/python-net/zh/aspose.cells/commentcollection/index_of/#aspose.cells.Comment-int) |搜索指定对象并返回数组列表中从指定索引延伸到最后一个元素的元素范围内第一个匹配项的从零开始的索引。|
| [index_of](/cells/python-net/zh/aspose.cells/commentcollection/index_of/#aspose.cells.Comment-int-int) |搜索指定对象并返回数组列表中从指定索引开始并包含指定数量元素的元素范围内第一个匹配项的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment) |搜索指定对象并返回整个数组列表中最后一次出现的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment-int) |搜索指定对象并返回数组列表中从第一个元素延伸到指定索引的元素范围内最后一次出现的从零开始的索引。|
| [last_index_of](/cells/python-net/zh/aspose.cells/commentcollection/last_index_of/#aspose.cells.Comment-int-int) |搜索指定的对象，并返回数组列表中包含指定数量的元素并以指定索引结束的元素范围内最后一个匹配项的从零开始的索引。|
| [binary_search](/cells/python-net/zh/aspose.cells/commentcollection/binary_search/#aspose.cells.Comment) |使用默认比较器在整个排序数组列表中搜索元素，并返回该元素从零开始的索引。|



### 例子

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments

```

### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`Comment`](/cells/python-net/zh/aspose.cells/comment)
