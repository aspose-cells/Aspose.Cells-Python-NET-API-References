---
title: get_threaded_comments yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 70
url: /tr/aspose.cells/commentcollection/get_threaded_comments/
is_root: false
---
##  get_threaded_comments(self, cell_name) {#str}
Hücre adına göre iş parçacıklı yorumları alır.


###  İadeler




```python

def get_threaded_comments(self, cell_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| cell_name | str | Hücrenin adı.|

###  Örnek

```python

threadedComments2 = comments.get_threaded_comments("B2")
for i in range(len(threadedComments2)):
    tc = threadedComments2[i]
    note = tc.notes

```


##  get_threaded_comments(self, row, column) {#int-int}
Satır ve sütun indeksine göre iş parçacıklı yorumları alır.


###  İadeler




```python

def get_threaded_comments(self, row, column):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| row | int | Satır dizini.|
| column | int | Sütun dizini.|

###  Örnek

```python

threadedComments1 = comments.get_threaded_comments(1, 1)
for i in range(len(threadedComments1)):
    tc = threadedComments1[i]
    note = tc.notes

```



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`CommentCollection`](/cells/python-net/tr/aspose.cells/commentcollection)
