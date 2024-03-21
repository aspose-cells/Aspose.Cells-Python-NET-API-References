---
title: set_formula metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 340
url: /sv/aspose.cells/cell/set_formula/
is_root: false
---
##  set_formula {#str-any}
Ställ in formeln och värdet (beräknat resultat) för formeln.



```python
def set_formula(self, formula, value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula | str | Formeln.|
| value | any |Värdet (beräknat resultat) av formeln.|


##  set_formula {#str-aspose.cells.FormulaParseOptions-any}
Ställ in formeln och värdet (beräknat resultat) för formeln.



```python
def set_formula(self, formula, options, value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula | str | Formeln.|
| options | [`FormulaParseOptions`](/cells/python-net/sv/aspose.cells/formulaparseoptions) | Alternativ för att analysera formeln.|
| value | any |Värdet (beräknat resultat) av formeln.|


##  set_formula {#str-bool-bool-any}
Ställ in formeln och värdet på formeln.



```python
def set_formula(self, formula, is_r1c1, is_local, value):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| formula | str | Formeln.|
| is_r1c1 | bool | Om formeln är R1C1-formel.|
| is_local | bool | Om formeln är språkformaterad.|
| value | any | Formelns värde.|
###  Anmärkningar

OBS: Denna klass är nu föråldrad. Istället,
använd Cell.SetFormula(sträng,FormulaParseOptions,objekt).
Den här egenskapen kommer att tas bort 12 månader senare sedan december 2019.
Aspose ber om ursäkt för eventuella besvär du kan ha upplevt.


###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cell`](/cells/python-net/sv/aspose.cells/cell)
