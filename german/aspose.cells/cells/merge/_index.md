---
title: merge Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 780
url: /de/aspose.cells/cells/merge/
is_root: false
---
##  merge {#int-int-int-int}
Führt einen angegebenen Zellbereich zu einer einzelnen Zelle zusammen.



```python
def merge(self, first_row, first_column, total_rows, total_columns):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| first_row | int | Erste Zeile dieses Bereichs (nullbasiert)|
| first_column | int | Erste Spalte dieses Bereichs (nullbasiert)|
| total_rows | int | Anzahl der Zeilen (einsbasiert)|
| total_columns | int | Anzahl der Spalten (auf einer basierend)|
###  Bemerkungen

Referenzieren Sie die zusammengeführte Zelle über die Adresse der Zelle oben links im Bereich.

##  merge {#int-int-int-int-bool}

Führt einen angegebenen Zellbereich zu einer einzelnen Zelle zusammen.



```python
def merge(self, first_row, first_column, total_rows, total_columns, merge_conflict):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| first_row | int | Erste Zeile dieses Bereichs (nullbasiert)|
| first_column | int | Erste Spalte dieses Bereichs (nullbasiert)|
| total_rows | int | Anzahl der Zeilen (einsbasiert)|
| total_columns | int | Anzahl der Spalten (auf einer basierend)|
| merge_conflict | bool | Konflikt zwischen zusammengeführten Bereichen zusammenführen.|
###  Bemerkungen

Referenzieren Sie die zusammengeführte Zelle über die Adresse der Zelle oben links im Bereich.
Wenn mergeConflict wahr ist und der zusammengeführte Bereich mit anderen zusammengeführten Zellen in Konflikt steht,
Andere verbundene Zellen werden automatisch entfernt.

##  merge {#int-int-int-int-bool-bool}
Führt einen angegebenen Zellbereich zu einer einzelnen Zelle zusammen.



```python
def merge(self, first_row, first_column, total_rows, total_columns, check_conflict, merge_conflict):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| first_row | int | Erste Zeile dieses Bereichs (nullbasiert)|
| first_column | int | Erste Spalte dieses Bereichs (nullbasiert)|
| total_rows | int | Anzahl der Zeilen (einsbasiert)|
| total_columns | int | Anzahl der Spalten (auf einer basierend)|
| check_conflict | bool | Gibt an, ob überprüft wird, ob die zusammengeführten Zellen andere zusammengeführte Zellen überschneiden|
| merge_conflict | bool | Konflikt zwischen zusammengeführten Bereichen zusammenführen.|
###  Bemerkungen

Referenzieren Sie die zusammengeführte Zelle über die Adresse der Zelle oben links im Bereich.
Wenn mergeConflict wahr ist und der zusammengeführte Bereich mit anderen zusammengeführten Zellen in Konflikt steht,
Andere verbundene Zellen werden automatisch entfernt.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cells`](/cells/python-net/de/aspose.cells/cells)
