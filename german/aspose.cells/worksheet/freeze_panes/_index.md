---
title: freeze_panes Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 140
url: /de/aspose.cells/worksheet/freeze_panes/
is_root: false
---
##  freeze_panes(self, cell_name, freezed_rows, freezed_columns) {#str-int-int}
Friert Bereiche an der angegebenen Zelle im Arbeitsblatt ein.



```python

def freeze_panes(self, cell_name, freezed_rows, freezed_columns):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| cell_name | str | Cell Name.|
| freezed_rows | int | Anzahl der sichtbaren Zeilen im oberen Bereich, nicht mehr als der Zeilenindex.|
| freezed_columns | int | Anzahl der sichtbaren Spalten im linken Bereich, nicht mehr als der Spaltenindex.|
###  Bemerkungen

Zeilenindex und Spaltenindex können nicht alle Null sein. Anzahl der Zeilen und Anzahl der Spalten
können auch nicht alle Null sein.

##  freeze_panes(self, row, column, freezed_rows, freezed_columns) {#int-int-int-int}
Friert Bereiche an der angegebenen Zelle im Arbeitsblatt ein.



```python

def freeze_panes(self, row, column, freezed_rows, freezed_columns):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| row | int | Zeilenindex.|
| column | int | Spaltenindex.|
| freezed_rows | int | Anzahl der sichtbaren Zeilen im oberen Bereich, nicht mehr als der Zeilenindex.|
| freezed_columns | int | Anzahl der sichtbaren Spalten im linken Bereich, nicht mehr als der Spaltenindex.|
###  Bemerkungen

Zeilenindex und Spaltenindex können nicht alle Null sein. Anzahl der Zeilen und Anzahl der Spalten
können auch nicht alle Null sein.


Die ersten beiden Parameter geben die eingefrorene Position an und die letzten beiden Parameter geben den eingefrorenen Bereich im linken oberen Fensterbereich an.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Worksheet`](/cells/python-net/de/aspose.cells/worksheet)
