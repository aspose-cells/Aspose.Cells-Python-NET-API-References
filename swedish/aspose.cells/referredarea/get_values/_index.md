---
title: get_values metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 30
url: /sv/aspose.cells/referredarea/get_values/
is_root: false
---
##  get_values(self) {#}
Får cellvärden i detta område.


###  Returnerar

Om detta område är ogiltigt, "#REF!" kommer att returneras;
Om detta område är en enskild cell, returnera sedan cellvärdeobjektet;
Annars returnera en 2D-array för alla värden i detta område.


```python

def get_values(self):
    ...
```




##  get_values(self, calculate_formulas) {#bool}
Får cellvärden i detta område.


###  Returnerar

Om detta område är ogiltigt, "#REF!" kommer att returneras;
Om detta område är en enskild cell, returnera sedan cellvärdeobjektet;
Annars returnera en 2D-array för alla värden i detta område.


```python

def get_values(self, calculate_formulas):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| calculate_formulas | bool | Om det finns några formler i detta intervall som inte har beräknats,<br/> denna flagga anger om dessa formler ska beräknas rekursivt|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`ReferredArea`](/cells/python-net/sv/aspose.cells/referredarea)
