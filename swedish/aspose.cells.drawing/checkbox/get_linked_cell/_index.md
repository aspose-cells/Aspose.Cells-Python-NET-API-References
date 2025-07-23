---
title: get_linked_cell metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 120
url: /sv/aspose.cells.drawing/checkbox/get_linked_cell/
is_root: false
---
##  get_linked_cell(self, is_r1c1, is_local) {#bool-bool}
Hämtar intervallet som är kopplat till kontrollens värde.


###  Returnerar

Intervallet som är kopplat till kontrollens värde.


```python

def get_linked_cell(self, is_r1c1, is_local):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| is_r1c1 | bool | Om formeln behöver formateras som R1C1.|
| is_local | bool | Om formeln behöver formateras efter språkinställning.|

###  Exempel

```python

# You may get results like '$A$1'
link = shape.get_linked_cell(False, False)

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`CheckBox`](/cells/python-net/sv/aspose.cells.drawing/checkbox)
