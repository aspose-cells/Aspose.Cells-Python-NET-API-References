---
title: add metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells/commentcollection/add/
is_root: false
---
##  add(self, cell_name) {#str}
Lägger till en kommentar till samlingen.


###  Returnerar

[`Comment`](/cells/python-net/sv/aspose.cells/comment) objektindex.


```python

def add(self, cell_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| cell_name | str | Cell namn.|

###  Exempel

```python

commentIndex2 = comments.add("B2")
comment2 = comments[commentIndex2]
comment2.note = "Second note."
comment2.font.name = "Times New Roman"

```


##  add(self, row, column) {#int-int}
Lägger till en kommentar till samlingen.


###  Returnerar

[`Comment`](/cells/python-net/sv/aspose.cells/comment) objektindex.


```python

def add(self, row, column):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| row | int | Cell radindex.|
| column | int | Kolumnindex Cell.|

###  Exempel

```python

commentIndex1 = comments.add(0, 0)
comment1 = comments[commentIndex1]
comment1.note = "First note."
comment1.font.name = "Times New Roman"

```



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Comment`](/cells/python-net/sv/aspose.cells/comment)
* klass [`CommentCollection`](/cells/python-net/sv/aspose.cells/commentcollection)
