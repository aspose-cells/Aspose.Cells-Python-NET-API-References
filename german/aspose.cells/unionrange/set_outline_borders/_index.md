---
title: set_outline_borders Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 70
url: /de/aspose.cells/unionrange/set_outline_borders/
is_root: false
---
##  set_outline_borders(self, border_styles, border_colors) {#list-aspose.pydrawing.Color[]}
Legt Linienränder um einen Zellbereich fest.



```python

def set_outline_borders(self, border_styles, border_colors):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| border_styles | list | Rahmenstile.|
| border_colors | aspose.pydrawing.Color[] | Rahmenfarben.|
###  Bemerkungen

Sowohl die Länge von borderStyles als auch von borderStyles muss 4 betragen.
Die Reihenfolge der Rahmenarten und Rahmenstile muss oben, unten, links, rechts sein

##  set_outline_borders(self, border_style, border_color) {#aspose.cells.CellBorderType-aspose.pydrawing.Color}
Legt die Umrisse um einen Zellbereich mit demselben Rahmenstil und derselben Farbe fest.



```python

def set_outline_borders(self, border_style, border_color):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| border_style | [`CellBorderType`](/cells/python-net/de/aspose.cells/cellbordertype) | Rahmenstil.|
| border_color | aspose.pydrawing.Color | Rahmenfarbe.|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`UnionRange`](/cells/python-net/de/aspose.cells/unionrange)
