---
title: get_cell_style metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 330
url: /sv/aspose.cells/cells/get_cell_style/
is_root: false
---
##  get_cell_style(self, row, column) {#int-int}
Hämta stilen för den givna cellen.


###  Returnerar

stilen på den givna cellen.


```python

def get_cell_style(self, row, column):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| row | int | radindex|
| column | int | kolumn|
###  Anmärkningar

Den returnerade stilen är endast den som ärvts för cellen eller den som ärvs från cellens rad/kolumn,
inkluderar inte de egenskaper som tillämpats av andra inställningar, till exempel villkorsstyrd formatering.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cells`](/cells/python-net/sv/aspose.cells/cells)
