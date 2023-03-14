---
title: get_formula1 metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells/formatcondition/get_formula1/
is_root: false
---
##  get_formula1(is_r1c1, is_local) {#bool-bool}
Hämtar värdet eller uttrycket som är kopplat till detta formatvillkor.


###  Returnerar

Värdet eller uttrycket som är associerat med detta formatvillkor.


```python
def get_formula1(self, is_r1c1, is_local):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| is_r1c1 | bool | Om formeln behöver formateras som R1C1.|
| is_local | bool | Huruvida formeln behöver formateras efter språk.|


##  get_formula1(row, column) {#int-int}
Hämtar formeln för den villkorliga formateringen av cellen.


###  Returnerar

Formeln.


```python
def get_formula1(self, row, column):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| row | int | Radindex.|
| column | int | Kolumnindex.|


##  get_formula1(is_r1c1, is_local, row, column) {#bool-bool-int-int}
Hämtar värdet eller uttrycket för den villkorliga formateringen av cellen.


###  Returnerar

Värdet eller uttrycket som är associerat med den villkorliga formateringen av cellen.


```python
def get_formula1(self, is_r1c1, is_local, row, column):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| is_r1c1 | bool | Om formeln behöver formateras som R1C1.|
| is_local | bool | Huruvida formeln behöver formateras efter språk.|
| row | int | Radindex.|
| column | int | Kolumnindex.|
###  Anmärkningar

Den givna cellen måste innehållas av denna villkorliga formatering, annars kommer null att returneras.


###  Se även

* modul [aspose.cells](../../)
* klass [FormatCondition](/cells/python-net/sv/aspose.cells/formatcondition)
