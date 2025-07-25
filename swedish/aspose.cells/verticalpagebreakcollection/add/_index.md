---
title: add metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells/verticalpagebreakcollection/add/
is_root: false
---
##  add(self, column) {#int}
Lägger till en vertikal sidbrytning i samlingen.


###  Returnerar

[`VerticalPageBreak`](/cells/python-net/sv/aspose.cells/verticalpagebreak) objektindex.


```python

def add(self, column):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| column | int | Kolumnindex Cell, nollbaserat.|
###  Anmärkningar

Sidbrytning läggs till längst upp till vänster i cellen.
Vänligen ange en horisontell sidbrytning och en vertikal sidbrytning samtidigt.

##  add(self, cell_name) {#str}
Lägger till en vertikal sidbrytning i samlingen.


###  Returnerar

[`VerticalPageBreak`](/cells/python-net/sv/aspose.cells/verticalpagebreak) objektindex.


```python

def add(self, cell_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| cell_name | str | Cell namn.|
###  Anmärkningar

Sidbrytning läggs till längst upp till vänster i cellen.
Vänligen ange en horisontell sidbrytning och en vertikal sidbrytning samtidigt.

##  add(self, row, column) {#int-int}
Lägger till en vertikal sidbrytning i samlingen.


###  Returnerar

[`VerticalPageBreak`](/cells/python-net/sv/aspose.cells/verticalpagebreak) objektindex.


```python

def add(self, row, column):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| row | int | Cell radindex, nollbaserat.|
| column | int | Kolumnindex Cell, nollbaserat.|
###  Anmärkningar

Sidbrytning läggs till längst upp till vänster i cellen.
Vänligen ange en horisontell sidbrytning och en vertikal sidbrytning samtidigt.

##  add(self, start_row, end_row, column) {#int-int-int}
Lägger till en vertikal sidbrytning i samlingen.


###  Returnerar

[`VerticalPageBreak`](/cells/python-net/sv/aspose.cells/verticalpagebreak) objektindex.


```python

def add(self, start_row, end_row, column):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| start_row | int | Startradsindex, nollbaserat.|
| end_row | int | Index för slutrad, nollbaserat.|
| column | int | Kolumnindex, nollbaserat.|
###  Anmärkningar

Den här metoden används för att add skapa en vertikal sidbrytning inom ett utskriftsområde.


###  Se även

* modul [`aspose.cells`](../../)
* klass [`VerticalPageBreak`](/cells/python-net/sv/aspose.cells/verticalpagebreak)
* klass [`VerticalPageBreakCollection`](/cells/python-net/sv/aspose.cells/verticalpagebreakcollection)
