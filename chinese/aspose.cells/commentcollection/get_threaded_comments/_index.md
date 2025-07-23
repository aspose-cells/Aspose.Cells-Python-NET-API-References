---
title: get_threaded_comments方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 70
url: /zh/aspose.cells/commentcollection/get_threaded_comments/
is_root: false
---
##  get_threaded_comments(self, cell_name) {#str}
根据单元格名称获取线程注意事项。


### 返回




```python

def get_threaded_comments(self, cell_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| cell_name | str |单元格的名称。|

### 例子

```python

threadedComments2 = comments.get_threaded_comments("B2")
for i in range(len(threadedComments2)):
    tc = threadedComments2[i]
    note = tc.notes

```


##  get_threaded_comments(self, row, column) {#int-int}
按行和列索引获取线程注意事项。


### 返回




```python

def get_threaded_comments(self, row, column):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| row | int |行索引。|
| column | int |列索引。|

### 例子

```python

threadedComments1 = comments.get_threaded_comments(1, 1)
for i in range(len(threadedComments1)):
    tc = threadedComments1[i]
    note = tc.notes

```



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`CommentCollection`](/cells/python-net/zh/aspose.cells/commentcollection)
