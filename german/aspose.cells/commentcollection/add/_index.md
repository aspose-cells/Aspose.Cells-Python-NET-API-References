---
title: add Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells/commentcollection/add/
is_root: false
---
##  add(self, cell_name) {#str}
Fügt der Sammlung einen Kommentar hinzu.


###  Kehrt zurück

[`Comment`](/cells/python-net/de/aspose.cells/comment) Objektindex.


```python

def add(self, cell_name):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| cell_name | str | Cell Name.|

###  Beispiel

```python

commentIndex2 = comments.add("B2")
comment2 = comments[commentIndex2]
comment2.note = "Second note."
comment2.font.name = "Times New Roman"

```


##  add(self, row, column) {#int-int}
Fügt der Sammlung einen Kommentar hinzu.


###  Kehrt zurück

[`Comment`](/cells/python-net/de/aspose.cells/comment) Objektindex.


```python

def add(self, row, column):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| row | int | Cell Zeilenindex.|
| column | int | Cell Spaltenindex.|

###  Beispiel

```python

commentIndex1 = comments.add(0, 0)
comment1 = comments[commentIndex1]
comment1.note = "First note."
comment1.font.name = "Times New Roman"

```



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Comment`](/cells/python-net/de/aspose.cells/comment)
* Klasse [`CommentCollection`](/cells/python-net/de/aspose.cells/commentcollection)
