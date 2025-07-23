---
title: طريقة get_threaded_comments
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 70
url: /ar/aspose.cells/commentcollection/get_threaded_comments/
is_root: false
---
##  get_threaded_comments(self, cell_name) {#str}
يحصل على التعليقات المترابطة حسب اسم الخلية.


###  عائدات




```python

def get_threaded_comments(self, cell_name):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| cell_name | str | اسم الخلية.|

###  مثال

```python

threadedComments2 = comments.get_threaded_comments("B2")
for i in range(len(threadedComments2)):
    tc = threadedComments2[i]
    note = tc.notes

```


##  get_threaded_comments(self, row, column) {#int-int}
يحصل على التعليقات المترابطة حسب مؤشر الصف والعمود.


###  عائدات




```python

def get_threaded_comments(self, row, column):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| row | int | مؤشر الصف.|
| column | int | فهرس العمود.|

###  مثال

```python

threadedComments1 = comments.get_threaded_comments(1, 1)
for i in range(len(threadedComments1)):
    tc = threadedComments1[i]
    note = tc.notes

```



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`CommentCollection`](/cells/python-net/ar/aspose.cells/commentcollection)
