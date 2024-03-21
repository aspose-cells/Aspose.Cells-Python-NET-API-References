---
title: set_array_formula metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 310
url: /sv/aspose.cells/cell/set_array_formula/
is_root: false
---
##  set_array_formula {#str-int-int}
Ställer in en matrisformel (äldre matrisformel inmatad via CTRL+SHIFT+ENTER i ms excel) till ett cellintervall.



```python
def set_array_formula(self, array_formula, row_number, column_number):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| array_formula | str | Matrisformel.|
| row_number | int | Antal rader som ska fyllas i resultatet av matrisformeln.|
| column_number | int | Antal kolumner som ska fyllas i resultatet av matrisformeln.|


##  set_array_formula {#str-int-int-aspose.cells.FormulaParseOptions}
Ställer in en matrisformel till ett cellintervall.



```python
def set_array_formula(self, array_formula, row_number, column_number, options):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| array_formula | str | Matrisformel.|
| row_number | int | Antal rader som ska fyllas i resultatet av matrisformeln.|
| column_number | int | Antal kolumner som ska fyllas i resultatet av matrisformeln.|
| options | [`FormulaParseOptions`](/cells/python-net/sv/aspose.cells/formulaparseoptions) | Alternativ för att analysera formeln.|


##  set_array_formula {#str-int-int-bool-bool}
Ställer in en matrisformel till ett cellintervall.



```python
def set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| array_formula | str | Matrisformel.|
| row_number | int | Antal rader som ska fyllas i resultatet av matrisformeln.|
| column_number | int | Antal kolumner som ska fyllas i resultatet av matrisformeln.|
| is_r1c1 | bool | om formeln är R1C1-formel|
| is_local | bool | om formeln är språkformaterad|
###  Anmärkningar

OBS: Denna klass är nu föråldrad. Istället,
använd Cell.SetArrayFormula(string,int,int,FormulaParseOptions).
Den här egenskapen kommer att tas bort 12 månader senare sedan december 2019.
Aspose ber om ursäkt för eventuella besvär du kan ha upplevt.

##  set_array_formula {#str-int-int-aspose.cells.FormulaParseOptions-list}
Ställer in en matrisformel till ett cellintervall.



```python
def set_array_formula(self, array_formula, row_number, column_number, options, values):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| array_formula | str | Matrisformel.|
| row_number | int | Antal rader som ska fyllas i resultatet av matrisformeln.|
| column_number | int | Antal kolumner som ska fyllas i resultatet av matrisformeln.|
| options | [`FormulaParseOptions`](/cells/python-net/sv/aspose.cells/formulaparseoptions) | Alternativ för att analysera formeln.|
| values | list | värden för dessa celler med en given matrisformel|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cell`](/cells/python-net/sv/aspose.cells/cell)
