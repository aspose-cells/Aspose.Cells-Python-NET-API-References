---
title: set_shared_formula metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 360
url: /sv/aspose.cells/cell/set_shared_formula/
is_root: false
---
##  set_shared_formula(self, shared_formula, row_number, column_number) {#str-int-int}
Ställer in delade formler till ett cellområde.



```python

def set_shared_formula(self, shared_formula, row_number, column_number):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| shared_formula | str | Delad formel.|
| row_number | int | Antal rader att fylla i formeln.|
| column_number | int | Antal kolumner som formeln ska fyllas i.|
###  Anmärkningar



##  set_shared_formula(self, shared_formula, row_number, column_number, options) {#str-int-int-aspose.cells.FormulaParseOptions}

Ställer in delade formler till ett cellområde.



```python

def set_shared_formula(self, shared_formula, row_number, column_number, options):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| shared_formula | str | Delad formel.|
| row_number | int | Antal rader att fylla i formeln.|
| column_number | int | Antal kolumner som formeln ska fyllas i.|
| options | [`FormulaParseOptions`](/cells/python-net/sv/aspose.cells/formulaparseoptions) | Alternativ för att analysera formeln.|


##  set_shared_formula(self, shared_formula, row_number, column_number, is_r1c1, is_local) {#str-int-int-bool-bool}
Ställer in en formel för ett cellområde.



```python

def set_shared_formula(self, shared_formula, row_number, column_number, is_r1c1, is_local):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| shared_formula | str | Delad formel.|
| row_number | int | Antal rader att fylla i formeln.|
| column_number | int | Antal kolumner som formeln ska fyllas i.|
| is_r1c1 | bool | huruvida formeln är R1C1-formeln|
| is_local | bool | om formeln är språkformaterad|
###  Anmärkningar

OBS: Den här klassen är nu föråldrad. Istället,
vänligen använd Cell.SetSharedFormula(string,int,int,FormulaParseOptions).
Den här egenskapen kommer att tas bort 12 månader senare från och med december 2019.
Aspose ber om ursäkt för eventuella besvär du kan ha upplevt.

##  set_shared_formula(self, shared_formula, row_number, column_number, options, values) {#str-int-int-aspose.cells.FormulaParseOptions-list}
Ställer in delade formler till ett cellområde.



```python

def set_shared_formula(self, shared_formula, row_number, column_number, options, values):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| shared_formula | str | Delad formel.|
| row_number | int | Antal rader att fylla i formeln.|
| column_number | int | Antal kolumner som formeln ska fyllas i.|
| options | [`FormulaParseOptions`](/cells/python-net/sv/aspose.cells/formulaparseoptions) | Alternativ för att analysera formeln.|
| values | list | värden för de celler med given delad formel|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cell`](/cells/python-net/sv/aspose.cells/cell)
