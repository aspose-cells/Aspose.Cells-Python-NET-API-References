---
title: create_range Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 190
url: /de/aspose.cells/cells/create_range/
is_root: false
---
##  create_range(self, address) {#str}
Erstellt ein [`Range`](/cells/python-net/de/aspose.cells/range)-Objekt aus einer Adresse des Bereichs.


###  Kehrt zurück

Ein [`Range`](/cells/python-net/de/aspose.cells/range)-Objekt


```python

def create_range(self, address):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| address | str | Die Adresse des Bereichs.|


##  create_range(self, upper_left_cell, lower_right_cell) {#str-str}
Erstellt ein [`Range`](/cells/python-net/de/aspose.cells/range)-Objekt aus einem Zellbereich.


###  Kehrt zurück

Ein [`Range`](/cells/python-net/de/aspose.cells/range)-Objekt


```python

def create_range(self, upper_left_cell, lower_right_cell):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| upper_left_cell | str | Zellenname oben links.|
| lower_right_cell | str | Zellenname unten rechts.|


##  create_range(self, first_index, number, is_vertical) {#int-int-bool}
Erstellt ein [`Range`](/cells/python-net/de/aspose.cells/range)-Objekt aus Zellenzeilen oder Zellenspalten.


###  Kehrt zurück

Ein [`Range`](/cells/python-net/de/aspose.cells/range)-Objekt.


```python

def create_range(self, first_index, number, is_vertical):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| first_index | int | Erster Zeilenindex oder erster Spaltenindex, nullbasiert.|
| number | int | Gesamtzahl der Zeilen oder Spalten, einsbasiert.|
| is_vertical | bool | Wahr – Bereich aus Zellspalten erstellt. Falsch – Bereich aus Zellzeilen erstellt.|


##  create_range(self, first_row, first_column, total_rows, total_columns) {#int-int-int-int}
Erstellt ein [`Range`](/cells/python-net/de/aspose.cells/range)-Objekt aus einem Zellbereich.


###  Kehrt zurück

Ein [`Range`](/cells/python-net/de/aspose.cells/range)-Objekt


```python

def create_range(self, first_row, first_column, total_rows, total_columns):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| first_row | int |Erste Zeile dieses Bereichs|
| first_column | int | Erste Spalte dieses Bereichs|
| total_rows | int | Anzahl der Zeilen|
| total_columns | int | Anzahl der Spalten|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cells`](/cells/python-net/de/aspose.cells/cells)
* Klasse [`Range`](/cells/python-net/de/aspose.cells/range)
