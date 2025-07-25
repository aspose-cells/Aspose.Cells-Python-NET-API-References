---
title: get_cell_display_style Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 320
url: /de/aspose.cells/cells/get_cell_display_style/
is_root: false
---
##  get_cell_display_style(self, row, column) {#int-int}
Ruft den Anzeigestil der angegebenen Zelle ab.


###  Kehrt zurück

der Anzeigestil der angegebenen Zelle.


```python

def get_cell_display_style(self, row, column):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| row | int | Zeilenindex der angegebenen Zelle|
| column | int | Spalte der angegebenen Zelle|
###  Bemerkungen

Gleiches gilt für [`Cell.get_display_style`](/cells/python-net/de/aspose.cells/cell/get_display_style),
und dasselbe mit der Verwendung von [`BorderType.SIDE_BORDERS`](/cells/python-net/de/aspose.cells/bordertype#SIDE_BORDERS)
für [`Cells.get_cell_display_style`](/cells/python-net/de/aspose.cells/cells/get_cell_display_style).

##  get_cell_display_style(self, row, column, adjacent_borders) {#int-int-aspose.cells.BorderType}
Ruft den Anzeigestil der angegebenen Zelle ab.


###  Kehrt zurück

der Anzeigestil der angegebenen Zelle.


```python

def get_cell_display_style(self, row, column, adjacent_borders):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| row | int | Zeilenindex der angegebenen Zelle|
| column | int | Spalte der angegebenen Zelle|
| adjacent_borders | [`BorderType`](/cells/python-net/de/aspose.cells/bordertype) | Gibt an, welche Grenzen überprüft und entsprechend den Grenzen benachbarter Zellen angepasst werden müssen.<br/>Bitte beachten Sie die Beschreibung für den gleichen Parameter von<br/>[`Cell.get_display_style`](/cells/python-net/aspose.cells/cell/get_display_style). |
###  Bemerkungen

Wenn die Zelle auch von anderen Einstellungen wie bedingter Formatierung, Listenobjekten usw. betroffen ist,
dann kann der Anzeigestil von [`Cells.get_cell_style`](/cells/python-net/de/aspose.cells/cells/get_cell_style) abweichen.
Und da diese Einstellungen auch auf leere (nicht vorhandene) Zellen angewendet werden können,
Mit dieser Methode können Sie die Instanziierung dieser leeren Zellen vermeiden
Die Leistung ist also besser, als wenn man die Instanz Cell von Cells erhält
und rufen Sie dann [`Cell.get_display_style`](/cells/python-net/de/aspose.cells/cell/get_display_style) an.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cells`](/cells/python-net/de/aspose.cells/cells)
