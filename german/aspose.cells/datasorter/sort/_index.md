---
title: sort Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 50
url: /de/aspose.cells/datasorter/sort/
is_root: false
---
##  sort(self) {#}
Sortieren Sie die Daten im Bereich.


###  Kehrt zurück

die ursprünglichen Indizes (absolute Position, z. B. Spalte A ist 0, B ist 1, ...) der sortierten Zeilen/Spalten.
Wenn durch diesen Sortiervorgang keine Zeilen/Spalten verschoben werden müssen, wird null zurückgegeben.


```python

def sort(self):
    ...
```




##  sort(self, cells, area) {#aspose.cells.Cells-aspose.cells.CellArea}
Sortieren Sie die Daten des Bereichs.


###  Kehrt zurück

die ursprünglichen Indizes (absolute Position, z. B. Spalte A ist 0, B ist 1, ...) der sortierten Zeilen/Spalten.
Wenn durch diesen Sortiervorgang keine Zeilen/Spalten verschoben werden müssen, wird null zurückgegeben.


```python

def sort(self, cells, area):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| cells | [`Cells`](/cells/python-net/de/aspose.cells/cells) | Die Zellen enthalten den Datenbereich.|
| area | [`CellArea`](/cells/python-net/de/aspose.cells/cellarea) | Der zu sortierende Bereich|


##  sort(self, cells, start_row, start_column, end_row, end_column) {#aspose.cells.Cells-int-int-int-int}
Sortiert die Daten des Bereichs.


###  Kehrt zurück

die ursprünglichen Indizes (absolute Position, z. B. Spalte A ist 0, B ist 1, ...) der sortierten Zeilen/Spalten.
Wenn durch diesen Sortiervorgang keine Zeilen/Spalten verschoben werden müssen, wird null zurückgegeben.


```python

def sort(self, cells, start_row, start_column, end_row, end_column):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| cells | [`Cells`](/cells/python-net/de/aspose.cells/cells) | Die Zellen enthalten den Datenbereich.|
| start_row | int | Die Startreihe des Bereichs.|
| start_column | int | Die Startspalte des Bereichs.|
| end_row | int | Die letzte Reihe des Bereichs.|
| end_column | int | Die Endspalte des Bereichs.|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`DataSorter`](/cells/python-net/de/aspose.cells/datasorter)
