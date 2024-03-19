---
title: get_cell_by_index Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 50
url: /de/aspose.cells/row/get_cell_by_index/
is_root: false
---
##  get_cell_by_index {#int}
Rufen Sie die Zelle nach einem bestimmten Index in der Zellsammlung dieser Zeile ab.


###  Kehrt zurück

Das Objekt Cell an der angegebenen Position.


```python
def get_cell_by_index(self, index):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| index | int | Der Index (Position) der Zelle in der Zellsammlung dieser Zeile.|
###  Bemerkungen

Um alle Zellen nacheinander ohne Änderung zu durchlaufen,
Die Verwendung von [`Row.get_enumerator`](/cells/python-net/de/aspose.cells/row/get_enumerator) führt zu einer besseren Leistung als die Verwendung dieser Methode zum Abrufen einer Zelle nach der anderen.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Row`](/cells/python-net/de/aspose.cells/row)
