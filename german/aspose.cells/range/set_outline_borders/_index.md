---
title: set_outline_borders Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 200
url: /de/aspose.cells/range/set_outline_borders/
is_root: false
---
##  set_outline_borders {#aspose.cells.CellBorderType-aspose.cells.CellsColor}
Legt die Umrissränder um einen Bereich von Zellen mit demselben Rahmenstil und derselben Farbe fest.



```python
def set_outline_borders(self, border_style, border_color):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| border_style | [`CellBorderType`](/cells/python-net/de/aspose.cells/cellbordertype) | Grenzstil.|
| border_color | [`CellsColor`](/cells/python-net/de/aspose.cells/cellscolor) | Randfarbe.|


##  set_outline_borders {#aspose.cells.CellBorderType-aspose.pydrawing.Color}
Legt die Umrissränder um einen Bereich von Zellen mit demselben Rahmenstil und derselben Farbe fest.



```python
def set_outline_borders(self, border_style, border_color):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| border_style | [`CellBorderType`](/cells/python-net/de/aspose.cells/cellbordertype) | Grenzstil.|
| border_color | aspose.pydrawing.Color | Randfarbe.|


##  set_outline_borders {#list-aspose.pydrawing.Color[]}
Legt Linienränder um einen Bereich von Zellen fest.



```python
def set_outline_borders(self, border_styles, border_colors):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| border_styles | list |Randstile.|
| border_colors | aspose.pydrawing.Color[] | Randfarben.|
###  Bemerkungen

Sowohl die Länge von borderStyles als auch von borderStyles muss 4 betragen.
Die Reihenfolge von borderStyles und borderStyles muss oben, unten, links und rechts sein


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Range`](/cells/python-net/de/aspose.cells/range)
