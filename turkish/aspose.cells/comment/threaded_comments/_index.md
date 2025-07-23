---
title: threaded_comments mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 230
url: /tr/aspose.cells/comment/threaded_comments/
is_root: false
---
##  threaded_comments mülk

Konulu yorumların listesini alır;

###  Örnek

```python

threadedComments = comment1.threaded_comments
for i in range(len(threadedComments)):
    tc = threadedComments[i]
    note = tc.notes

```
###  Tanım:
```python
@property
def threaded_comments(self):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Comment`](/cells/python-net/tr/aspose.cells/comment)
* sınıf [`ThreadedCommentCollection`](/cells/python-net/tr/aspose.cells/threadedcommentcollection)
