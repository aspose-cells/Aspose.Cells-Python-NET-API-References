---
title: get_cell_by_index metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 50
url: /sv/aspose.cells/row/get_cell_by_index/
is_root: false
---
##  get_cell_by_index {#int}
Hämta cellen efter specifikt index i cellsamlingen på den här raden.


###  Returnerar

Cell-objektet vid given position.


```python
def get_cell_by_index(self, index):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| index | int | Index(position) för cellen i cellsamlingen för denna rad.|
###  Anmärkningar

För att passera alla celler i sekvens utan modifiering,
att använda [`Row.get_enumerator`](/cells/python-net/sv/aspose.cells/row/get_enumerator) ger bättre prestanda än att använda den här metoden för att få cell en efter en.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Row`](/cells/python-net/sv/aspose.cells/row)
