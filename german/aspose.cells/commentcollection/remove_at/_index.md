---
title: remove_at Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 100
url: /de/aspose.cells/commentcollection/remove_at/
is_root: false
---
##  remove_at(self, cell_name) {#str}
Entfernt den Kommentar der jeweiligen Zelle.



```python

def remove_at(self, cell_name):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| cell_name | str | Der Name der Zelle, die einen Kommentar enthält.|

###  Beispiel

```python

comments.remove_at("B2")

```


##  remove_at(self, row, column) {#int-int}
Entfernt den Kommentar der jeweiligen Zelle.



```python

def remove_at(self, row, column):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| row | int | Der Zeilenindex.|
| column | int | der Spaltenindex.|

###  Beispiel

```python

comments.remove_at(1, 1)

```



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`CommentCollection`](/cells/python-net/de/aspose.cells/commentcollection)
