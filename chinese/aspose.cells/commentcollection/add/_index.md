---
title: add方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells/commentcollection/add/
is_root: false
---
##  add(self, cell_name) {#str}
向集合中添加注意事项。


### 返回

[`Comment`](/cells/python-net/zh/aspose.cells/comment) 对象索引。


```python

def add(self, cell_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| cell_name | str | Cell 名称。|

### 例子

```python

commentIndex2 = comments.add("B2")
comment2 = comments[commentIndex2]
comment2.note = "Second note."
comment2.font.name = "Times New Roman"

```


##  add(self, row, column) {#int-int}
向集合中添加注意事项。


### 返回

[`Comment`](/cells/python-net/zh/aspose.cells/comment) 对象索引。


```python

def add(self, row, column):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| row | int | Cell 行索引。|
| column | int | Cell 列索引。|

### 例子

```python

commentIndex1 = comments.add(0, 0)
comment1 = comments[commentIndex1]
comment1.note = "First note."
comment1.font.name = "Times New Roman"

```



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Comment`](/cells/python-net/zh/aspose.cells/comment)
* 类 [`CommentCollection`](/cells/python-net/zh/aspose.cells/commentcollection)
