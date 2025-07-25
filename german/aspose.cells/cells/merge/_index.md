---
title: merge Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 800
url: /de/aspose.cells/cells/merge/
is_root: false
---
##  merge(self, first_row, first_column, total_rows, total_columns) {#int-int-int-int}
Fügt einen angegebenen Zellbereich zu einer einzigen Zelle zusammen.



```python

def merge(self, first_row, first_column, total_rows, total_columns):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| first_row | int | Erste Zeile dieses Bereichs (nullbasiert)|
| first_column | int | Erste Spalte dieses Bereichs (nullbasiert)|
| total_rows | int |Anzahl der Zeilen (einsbasiert)|
| total_columns | int | Anzahl der Spalten (einseitig)|
###  Bemerkungen

Referenzieren Sie die zusammengeführte Zelle über die Adresse der oberen linken Zelle im Bereich.

##  merge(self, first_row, first_column, total_rows, total_columns, merge_conflict) {#int-int-int-int-bool}

Fügt einen angegebenen Zellbereich zu einer einzigen Zelle zusammen.



```python

def merge(self, first_row, first_column, total_rows, total_columns, merge_conflict):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| first_row | int | Erste Zeile dieses Bereichs (nullbasiert)|
| first_column | int | Erste Spalte dieses Bereichs (nullbasiert)|
| total_rows | int |Anzahl der Zeilen (einsbasiert)|
| total_columns | int | Anzahl der Spalten (einseitig)|
| merge_conflict | bool | Konflikte bei der Zusammenführung zusammengeführter Bereiche beheben.|
###  Bemerkungen

Referenzieren Sie die zusammengeführte Zelle über die Adresse der oberen linken Zelle im Bereich.
Wenn mergeConflict wahr ist und der zusammengeführte Bereich mit anderen zusammengeführten Zellen in Konflikt steht,
andere verbundene Zellen werden automatisch entfernt.

##  merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict) {#int-int-int-int-bool-bool}
Fügt einen angegebenen Zellbereich zu einer einzigen Zelle zusammen.



```python

def merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| first_row | int | Erste Zeile dieses Bereichs (nullbasiert)|
| first_column | int | Erste Spalte dieses Bereichs (nullbasiert)|
| total_rows | int |Anzahl der Zeilen (einsbasiert)|
| total_columns | int | Anzahl der Spalten (einseitig)|
| check_conflict | bool | Gibt an, ob die zusammengeführten Zellen andere zusammengeführte Zellen schneiden|
| merge_conflict | bool | Konflikte bei der Zusammenführung zusammengeführter Bereiche beheben.|
###  Bemerkungen

Referenzieren Sie die zusammengeführte Zelle über die Adresse der oberen linken Zelle im Bereich.
Wenn mergeConflict wahr ist und der zusammengeführte Bereich mit anderen zusammengeführten Zellen in Konflikt steht,
andere verbundene Zellen werden automatisch entfernt.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cells`](/cells/python-net/de/aspose.cells/cells)
