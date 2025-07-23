---
title: set_array_formula metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 320
url: /sv/aspose.cells/cell/set_array_formula/
is_root: false
---
##  set_array_formula(self, array_formula, row_number, column_number) {#str-int-int}
Ställer in en arrayformel (en äldre arrayformel som anges via CTRL+SHIFT+ENTER i MS Excel) till ett cellområde.



```python

def set_array_formula(self, array_formula, row_number, column_number):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| array_formula | str | Arrayformel.|
| row_number | int | Antal rader som ska fyllas i resultatet av arrayformeln.|
| column_number | int | Antal kolumner som ska fyllas i resultatet av arrayformeln.|


##  set_array_formula(self, array_formula, row_number, column_number, options) {#str-int-int-aspose.cells.FormulaParseOptions}
Ställer in en matrisformel för ett cellområde.



```python

def set_array_formula(self, array_formula, row_number, column_number, options):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| array_formula | str | Arrayformel.|
| row_number | int | Antal rader som ska fyllas i resultatet av arrayformeln.|
| column_number | int | Antal kolumner som ska fyllas i resultatet av arrayformeln.|
| options | [`FormulaParseOptions`](/cells/python-net/sv/aspose.cells/formulaparseoptions) | Alternativ för att analysera formeln.|


##  set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local) {#str-int-int-bool-bool}
Ställer in en matrisformel för ett cellområde.



```python

def set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| array_formula | str | Arrayformel.|
| row_number | int | Antal rader som ska fyllas i resultatet av arrayformeln.|
| column_number | int | Antal kolumner som ska fyllas i resultatet av arrayformeln.|
| is_r1c1 | bool | huruvida formeln är R1C1-formeln|
| is_local | bool | om formeln är språkformaterad|
###  Anmärkningar

OBS: Den här klassen är nu föråldrad. Istället,
vänligen använd Cell.SetArrayFormula(string,int,int,FormulaParseOptions).
Den här egenskapen kommer att tas bort 12 månader senare från och med december 2019.
Aspose ber om ursäkt för eventuella besvär du kan ha upplevt.

##  set_array_formula(self, array_formula, row_number, column_number, options, values) {#str-int-int-aspose.cells.FormulaParseOptions-list}
Ställer in en matrisformel för ett cellområde.



```python

def set_array_formula(self, array_formula, row_number, column_number, options, values):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| array_formula | str | Arrayformel.|
| row_number | int | Antal rader som ska fyllas i resultatet av arrayformeln.|
| column_number | int | Antal kolumner som ska fyllas i resultatet av arrayformeln.|
| options | [`FormulaParseOptions`](/cells/python-net/sv/aspose.cells/formulaparseoptions) | Alternativ för att analysera formeln.|
| values | list | värden för de cellerna med given matrisformel|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cell`](/cells/python-net/sv/aspose.cells/cell)
