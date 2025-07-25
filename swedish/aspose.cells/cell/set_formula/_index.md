---
title: set_formula metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 350
url: /sv/aspose.cells/cell/set_formula/
is_root: false
---
##  set_formula(self, formula, value) {#str-any}
Ställ in formeln och värdet (beräknat resultat) för formeln.



```python

def set_formula(self, formula, value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula | str | Formeln.|
| value | any | Formelns värde (beräknat resultat).|


##  set_formula(self, formula, options) {#str-aspose.cells.FormulaParseOptions}
Ställ in formeln och värdet (beräknat resultat) för formeln.



```python

def set_formula(self, formula, options):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula | str | Formeln.|
| options | [`FormulaParseOptions`](/cells/python-net/sv/aspose.cells/formulaparseoptions) | Alternativ för att analysera formeln.|


##  set_formula(self, formula, options, value) {#str-aspose.cells.FormulaParseOptions-any}
Ställ in formeln och värdet (beräknat resultat) för formeln.



```python

def set_formula(self, formula, options, value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula | str | Formeln.|
| options | [`FormulaParseOptions`](/cells/python-net/sv/aspose.cells/formulaparseoptions) | Alternativ för att analysera formeln.|
| value | any | Formelns värde (beräknat resultat).|


##  set_formula(self, formula, is_r1c1, is_local, value) {#str-bool-bool-any}
Ange formeln och formelns värde.



```python

def set_formula(self, formula, is_r1c1, is_local, value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula | str | Formeln.|
| is_r1c1 | bool | Om formeln är R1C1-formeln.|
| is_local | bool | Om formeln är språkformaterad.|
| value | any | Formelns värde.|
###  Anmärkningar

OBS: Den här klassen är nu föråldrad. Istället,
vänligen använd Cell.SetFormula(string,FormulaParseOptions,object).
Den här egenskapen kommer att tas bort 12 månader senare från och med december 2019.
Aspose ber om ursäkt för eventuella besvär du kan ha upplevt.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cell`](/cells/python-net/sv/aspose.cells/cell)
