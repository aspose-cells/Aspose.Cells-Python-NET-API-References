---
title: add_copy Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 30
url: /de/aspose.cells/worksheetcollection/add_copy/
is_root: false
---
##  add_copy {#str}
Fügt der Sammlung ein Arbeitsblatt hinzu und kopiert Daten aus einem vorhandenen Arbeitsblatt.


###  Kehrt zurück

[`Worksheet`](/cells/python-net/de/aspose.cells/worksheet) Objektindex.


```python
def add_copy(self, sheet_name):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| sheet_name | str | Name des Quellarbeitsblatts.|
###  Ausnahmen
| Ausnahme| Beschreibung|
| :- | :- |
| [`CellsException`](/cells/python-net/de/aspose.cells/cellsexception) | Gibt einen ungültigen Arbeitsblattnamen an.|




##  add_copy {#int}
Fügt der Sammlung ein Arbeitsblatt hinzu und kopiert Daten aus einem vorhandenen Arbeitsblatt.


###  Kehrt zurück

[`Worksheet`](/cells/python-net/de/aspose.cells/worksheet) Objektindex.


```python
def add_copy(self, sheet_index):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| sheet_index | int | Index des Quellarbeitsblatts.|


##  add_copy {#list-list}
Kopieren Sie eine Gruppe von Arbeitsblättern.



```python
def add_copy(self, source, dest_sheet_names):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| source | list | Die Quellarbeitsblätter.|
| dest_sheet_names | list | Die Namen der kopierten Blätter.|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`CellsException`](/cells/python-net/de/aspose.cells/cellsexception)
* Klasse [`Worksheet`](/cells/python-net/de/aspose.cells/worksheet)
* Klasse [`WorksheetCollection`](/cells/python-net/de/aspose.cells/worksheetcollection)
