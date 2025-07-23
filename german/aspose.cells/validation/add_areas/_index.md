---
title: add_areas Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 30
url: /de/aspose.cells/validation/add_areas/
is_root: false
---
##  add_areas(self, areas, check_intersection, check_edge) {#list-bool-bool}
Wendet die Validierung auf angegebene Bereiche an.



```python

def add_areas(self, areas, check_intersection, check_edge):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| areas | list | Die Bereiche.|
| check_intersection | bool | Überprüfen Sie, ob die Schnittmenge des angegebenen Bereichs mit vorhandenen Validierungsbereichen überprüft wird.<br/>Wenn eine Validierung in einem bestimmten Bereich (oder einem Teil davon) angewendet wurde,<br/>dann sollte zunächst die vorhandene Validierung aus dem angegebenen Bereich entfernt werden.<br/>Andernfalls kann es zu Beschädigungen der generierten Validierungen kommen.<br/>Wenn der Benutzer sicher ist, dass alle hinzugefügten Bereiche sich nicht mit einem vorhandenen Bereich überschneiden,<br/> Dieser Parameter kann aus Leistungsgründen auf „false“ gesetzt werden.|
| check_edge | bool | Überprüfen Sie, ob der Rand der Anwendungsbereiche dieser Validierung überprüft wird.<br/>Die internen Einstellungen der Validierung hängen vom oberen linken Bereich der angewendeten Werte ab.<br/>Wenn also einer der angegebenen Bereiche der neue obere linke Bereich der angewendeten Bereiche wird,<br/>Die internen Einstellungen sollten geändert und neu erstellt werden, da es sonst zu unerwarteten Ergebnissen kommen kann.<br/>Wenn der Benutzer sicher ist, dass keiner dieser hinzugefügten Bereiche oben links ist,<br/> Dieser Parameter kann aus Leistungsgründen auf „false“ gesetzt werden.|
###  Bemerkungen

Mit dieser Methode entfernen wir alle alten Validierungen im angegebenen Bereich.
Für den oberen linken Bereich der Validierung ist zunächst die StartRow am kleinsten,
zweitens ist seine StartColumn die kleinste der Bereiche, die die gleiche kleinste StartRow haben.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Validation`](/cells/python-net/de/aspose.cells/validation)
