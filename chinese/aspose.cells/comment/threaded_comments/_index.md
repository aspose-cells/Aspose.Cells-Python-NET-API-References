---
title: threaded_comments属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 230
url: /zh/aspose.cells/comment/threaded_comments/
is_root: false
---
## threaded_comments属性

获取线索评论列表；

### 例子

```python

threadedComments = comment1.threaded_comments
for i in range(len(threadedComments)):
    tc = threadedComments[i]
    note = tc.notes

```
### 定义：
```python
@property
def threaded_comments(self):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Comment`](/cells/python-net/zh/aspose.cells/comment)
* 类 [`ThreadedCommentCollection`](/cells/python-net/zh/aspose.cells/threadedcommentcollection)
