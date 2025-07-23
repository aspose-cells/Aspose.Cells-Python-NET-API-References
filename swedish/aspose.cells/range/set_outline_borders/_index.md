---
title: set_outline_borders metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 250
url: /sv/aspose.cells/range/set_outline_borders/
is_root: false
---
##  set_outline_borders(self, border_style, border_color) {#aspose.cells.CellBorderType-aspose.cells.CellsColor}
Ställer in konturkanterna runt ett cellområde med samma kantstil och färg.



```python

def set_outline_borders(self, border_style, border_color):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| border_style | [`CellBorderType`](/cells/python-net/sv/aspose.cells/cellbordertype) | Gränsstil.|
| border_color | [`CellsColor`](/cells/python-net/sv/aspose.cells/cellscolor) | Kantfärg.|


##  set_outline_borders(self, border_style, border_color) {#aspose.cells.CellBorderType-aspose.pydrawing.Color}
Ställer in konturkanterna runt ett cellområde med samma kantstil och färg.



```python

def set_outline_borders(self, border_style, border_color):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| border_style | [`CellBorderType`](/cells/python-net/sv/aspose.cells/cellbordertype) | Gränsstil.|
| border_color | aspose.pydrawing.Color | Kantfärg.|


##  set_outline_borders(self, border_styles, border_colors) {#list-aspose.pydrawing.Color[]}
Anger linjekanter runt ett cellområde.



```python

def set_outline_borders(self, border_styles, border_colors):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| border_styles | list | Kantformat.|
| border_colors | aspose.pydrawing.Color[] | Kantfärger.|
###  Anmärkningar

Både längden på borderStyles och borderStyles måste vara 4.
Ordningen för borderStyles och borderStyles måste vara topp, botten, vänster, höger


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Range`](/cells/python-net/sv/aspose.cells/range)
