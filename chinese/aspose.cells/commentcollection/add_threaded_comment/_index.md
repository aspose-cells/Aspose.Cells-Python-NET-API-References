---
title: add_threaded_comment方法
second_title: Aspose.Cells for Python via .NET API 参考资料
description:
type: docs
weight: 30
url: /zh/aspose.cells/commentcollection/add_threaded_comment/
is_root: false
---
##  add_threaded_comment(cell_name, text, author) {#str-str-ThreadedCommentAuthor}
添加线程评论。


### 返回

[ThreadedComment](/cells/python-net/zh/aspose.cells/threadedcomment) 对象索引。


```python
def add_threaded_comment(self, cell_name, text, author):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| cell_name | str |单元格的名称。|
| text | str |评论正文|
| author | [ThreadedCommentAuthor](/cells/python-net/zh/aspose.cells/threadedcommentauthor) |此线程评论的用户。|


##  add_threaded_comment(row, column, text, author) {#int-int-str-ThreadedCommentAuthor}
添加线程评论。


### 返回

[ThreadedComment](/cells/python-net/zh/aspose.cells/threadedcomment) 对象索引。


```python
def add_threaded_comment(self, row, column, text, author):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| row | int | Cell 行索引。|
| column | int | Cell 列索引。|
| text | str |评论正文|
| author | [ThreadedCommentAuthor](/cells/python-net/zh/aspose.cells/threadedcommentauthor) |此线程评论的用户。|



### 也可以看看
* 模块 [aspose.cells](../../)
* 类 [CommentCollection](/cells/python-net/zh/aspose.cells/commentcollection)
* 类 [ThreadedComment](/cells/python-net/zh/aspose.cells/threadedcomment)
