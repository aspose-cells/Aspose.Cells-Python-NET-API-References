---
title: add_area Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells/validation/add_area/
is_root: false
---
##  add_area(self, cell_area) {#aspose.cells.CellArea}
Wendet die Validierung auf den Bereich an.



```python

def add_area(self, cell_area):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/de/aspose.cells/cellarea) | Die Gegend.|
###  Bemerkungen

Es entspricht der Verwendung von [`Validation.add_area`](/cells/python-net/de/aspose.cells/validation/add_area)
mit Überprüfung von Schnittpunkten und Kanten.

##  add_area(self, cell_area, check_intersection, check_edge) {#aspose.cells.CellArea-bool-bool}
Wendet die Validierung auf den Bereich an.



```python

def add_area(self, cell_area, check_intersection, check_edge):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/de/aspose.cells/cellarea) | Die Gegend.|
| check_intersection | bool | Überprüfen Sie, ob die Schnittmenge des angegebenen Bereichs mit vorhandenen Validierungsbereichen überprüft wird.<br/>Wenn eine Validierung in einem bestimmten Bereich (oder einem Teil davon) angewendet wurde,<br/>dann sollte zunächst die vorhandene Validierung aus dem angegebenen Bereich entfernt werden.<br/>Andernfalls kann es zu Beschädigungen der generierten Validierungen kommen.<br/>Wenn der Benutzer sicher ist, dass der hinzugefügte Bereich sich nicht mit einem vorhandenen Bereich überschneidet,<br/> Dieser Parameter kann aus Leistungsgründen auf „false“ gesetzt werden.|
| check_edge | bool | Überprüfen Sie, ob der Rand der Anwendungsbereiche dieser Validierung überprüft wird.<br/>Die internen Einstellungen der Validierung hängen vom oberen linken Bereich der angewendeten Werte ab.<br/>Wenn also der angegebene Bereich der neue obere linke Bereich der angewendeten Bereiche wird,<br/>Die internen Einstellungen sollten geändert und neu erstellt werden, da es sonst zu unerwarteten Ergebnissen kommen kann.<br/>Wenn der Benutzer sicher ist, dass der hinzugefügte Bereich nicht der obere linke ist,<br/> Dieser Parameter kann aus Leistungsgründen auf „false“ gesetzt werden.|
###  Bemerkungen

Mit dieser Methode entfernen wir alle alten Validierungen im angegebenen Bereich.
Für den oberen linken Bereich der Validierung ist zunächst die StartRow am kleinsten,
zweitens ist seine StartColumn die kleinste der Bereiche, die die gleiche kleinste StartRow haben.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Validation`](/cells/python-net/de/aspose.cells/validation)
