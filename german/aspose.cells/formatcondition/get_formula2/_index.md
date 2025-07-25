---
title: get_formula2 Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 30
url: /de/aspose.cells/formatcondition/get_formula2/
is_root: false
---
##  get_formula2(self, is_r1c1, is_local) {#bool-bool}
Ruft den Wert oder Ausdruck ab, der dieser Formatbedingung zugeordnet ist.


###  Kehrt zurück

Der mit dieser Formatbedingung verknüpfte Wert oder Ausdruck.


```python

def get_formula2(self, is_r1c1, is_local):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| is_r1c1 | bool | Ob die Formel als R1C1 formatiert werden muss.|
| is_local | bool | Ob die Formel nach Gebietsschema formatiert werden muss.|


##  get_formula2(self, row, column) {#int-int}
Ruft die Formel der bedingten Formatierung der Zelle ab.


###  Kehrt zurück

Die Formel.


```python

def get_formula2(self, row, column):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| row | int | Der Zeilenindex.|
| column | int | Der Spaltenindex.|


##  get_formula2(self, is_r1c1, is_local, row, column) {#bool-bool-int-int}
Ruft den Wert oder Ausdruck der bedingten Formatierung der Zelle ab.


###  Kehrt zurück

Der Wert oder Ausdruck, der mit der bedingten Formatierung der Zelle verknüpft ist.


```python

def get_formula2(self, is_r1c1, is_local, row, column):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| is_r1c1 | bool | Ob die Formel als R1C1 formatiert werden muss.|
| is_local | bool | Ob die Formel nach Gebietsschema formatiert werden muss.|
| row | int | Der Zeilenindex.|
| column | int | Der Spaltenindex.|
###  Bemerkungen

Die angegebene Zelle muss in dieser bedingten Formatierung enthalten sein, andernfalls wird null zurückgegeben.


###  Siehe auch

* Modul [`aspose.cells`](../../)
* Klasse [`FormatCondition`](/cells/python-net/de/aspose.cells/formatcondition)
