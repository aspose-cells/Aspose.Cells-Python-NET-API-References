---
title: get_formula2 metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 30
url: /sv/aspose.cells/formatcondition/get_formula2/
is_root: false
---
##  get_formula2(self, is_r1c1, is_local) {#bool-bool}
Hämtar värdet eller uttrycket som är associerat med detta formatvillkor.


###  Returnerar

Värdet eller uttrycket som är associerat med detta formatvillkor.


```python

def get_formula2(self, is_r1c1, is_local):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| is_r1c1 | bool | Om formeln behöver formateras som R1C1.|
| is_local | bool | Om formeln behöver formateras efter språkinställning.|


##  get_formula2(self, row, column) {#int-int}
Hämtar formeln för cellens villkorsstyrda formatering.


###  Returnerar

Formeln.


```python

def get_formula2(self, row, column):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| row | int | Radindexet.|
| column | int | Kolumnindexet.|


##  get_formula2(self, is_r1c1, is_local, row, column) {#bool-bool-int-int}
Hämtar värdet eller uttrycket för cellens villkorsstyrda formatering.


###  Returnerar

Värdet eller uttrycket som är associerat med cellens villkorsstyrda formatering.


```python

def get_formula2(self, is_r1c1, is_local, row, column):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| is_r1c1 | bool | Om formeln behöver formateras som R1C1.|
| is_local | bool | Om formeln behöver formateras efter språkinställning.|
| row | int | Radindexet.|
| column | int | Kolumnindexet.|
###  Anmärkningar

Den angivna cellen måste innehålla denna villkorsstyrda formatering, annars returneras null.


###  Se även

* modul [`aspose.cells`](../../)
* klass [`FormatCondition`](/cells/python-net/sv/aspose.cells/formatcondition)
