---
title: add Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells.charts/chartcollection/add/
is_root: false
---
##  add(self, type, upper_left_row, upper_left_column, lower_right_row, lower_right_column) {#aspose.cells.charts.ChartType-int-int-int-int}
Fügt der Sammlung ein Diagramm hinzu.


###  Kehrt zurück

[`Chart`](/cells/python-net/de/aspose.cells.charts/chart) Objektindex.


```python

def add(self, type, upper_left_row, upper_left_column, lower_right_row, lower_right_column):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| type | [`ChartType`](/cells/python-net/de/aspose.cells.charts/charttype) | Diagrammtyp|
| upper_left_row | int | Zeilenindex oben links.|
| upper_left_column | int | Index der oberen linken Spalte.|
| lower_right_row | int | Zeilenindex unten rechts|
| lower_right_column | int | Spaltenindex unten rechts|


##  add(self, type, data_range, top_row, left_column, right_row, bottom_column) {#aspose.cells.charts.ChartType-str-int-int-int-int}
Fügt der Sammlung ein Diagramm hinzu.


###  Kehrt zurück

[`Chart`](/cells/python-net/de/aspose.cells.charts/chart) Objektindex.


```python

def add(self, type, data_range, top_row, left_column, right_row, bottom_column):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| type | [`ChartType`](/cells/python-net/de/aspose.cells.charts/charttype) | Diagrammtyp|
| data_range | str | Gibt den Datenbereich des Diagramms an|
| top_row | int | Zeilenindex oben links.|
| left_column | int | Index der oberen linken Spalte.|
| right_row | int | Zeilenindex unten rechts|
| bottom_column | int | Spaltenindex unten rechts|
###  Bemerkungen

HINWEIS: Dieses Mitglied ist mittlerweile veraltet. Stattdessen
Bitte verwenden Sie die [`ChartCollection.add`](/cells/python-net/de/aspose.cells.charts/chartcollection/add)-Eigenschaft.
 Diese Eigenschaft wird 12 Monate später (ab Mai 2022) entfernt.
Aspose entschuldigt sich für etwaige Unannehmlichkeiten, die Ihnen möglicherweise entstanden sind.

##  add(self, data, data_range, is_vertical, top_row, left_column, right_row, bottom_column) {#bytes-str-bool-int-int-int-int}
Fügt ein Diagramm mit voreingestellter Vorlage hinzu.


###  Kehrt zurück

[`Chart`](/cells/python-net/de/aspose.cells.charts/chart) Objektindex.


```python

def add(self, data, data_range, is_vertical, top_row, left_column, right_row, bottom_column):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| data | bytes | Die Daten der Diagrammvorlagendatei (.crtx).|
| data_range | str | Gibt den Datenbereich des Diagramms an|
| is_vertical | bool | Gibt an, ob die Reihe aus einem Bereich von Zellenwerten zeilen- oder spaltenweise dargestellt werden soll.|
| top_row | int | Zeilenindex oben links.|
| left_column | int | Index der oberen linken Spalte.|
| right_row | int | Zeilenindex unten rechts|
| bottom_column | int | Spaltenindex unten rechts|


##  add(self, type, data_range, is_vertical, top_row, left_column, right_row, bottom_column) {#aspose.cells.charts.ChartType-str-bool-int-int-int-int}
Fügt der Sammlung ein Diagramm hinzu.


###  Kehrt zurück

[`Chart`](/cells/python-net/de/aspose.cells.charts/chart) Objektindex.


```python

def add(self, type, data_range, is_vertical, top_row, left_column, right_row, bottom_column):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| type | [`ChartType`](/cells/python-net/de/aspose.cells.charts/charttype) | Diagrammtyp|
| data_range | str | Gibt den Datenbereich des Diagramms an|
| is_vertical | bool | Gibt an, ob die Reihe aus einem Bereich von Zellenwerten zeilen- oder spaltenweise dargestellt werden soll.|
| top_row | int | Zeilenindex oben links.|
| left_column | int | Index der oberen linken Spalte.|
| right_row | int | Zeilenindex unten rechts|
| bottom_column | int | Spaltenindex unten rechts|



###  Siehe auch
* Modul [`aspose.cells.charts`](../../)
* Klasse [`Chart`](/cells/python-net/de/aspose.cells.charts/chart)
* Klasse [`ChartCollection`](/cells/python-net/de/aspose.cells.charts/chartcollection)
