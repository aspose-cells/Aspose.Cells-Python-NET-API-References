---
title: set_formula Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 340
url: /de/aspose.cells/cell/set_formula/
is_root: false
---
##  set_formula {#str-any}
Legen Sie die Formel und den Wert (berechnetes Ergebnis) der Formel fest.



```python
def set_formula(self, formula, value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| formula | str | Die Formel.|
| value | any |Der Wert (berechnetes Ergebnis) der Formel.|


##  set_formula {#str-aspose.cells.FormulaParseOptions-any}
Legen Sie die Formel und den Wert (berechnetes Ergebnis) der Formel fest.



```python
def set_formula(self, formula, options, value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| formula | str | Die Formel.|
| options | [`FormulaParseOptions`](/cells/python-net/de/aspose.cells/formulaparseoptions) | Optionen zum Parsen der Formel.|
| value | any |Der Wert (berechnetes Ergebnis) der Formel.|


##  set_formula {#str-bool-bool-any}
Legen Sie die Formel und den Wert der Formel fest.



```python
def set_formula(self, formula, is_r1c1, is_local, value):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| formula | str | Die Formel.|
| is_r1c1 | bool | Ob die Formel eine R1C1-Formel ist.|
| is_local | bool | Ob die Formel gebietsschemaformatiert ist.|
| value | any | Der Wert der Formel.|
###  Bemerkungen

HINWEIS: Diese Klasse ist mittlerweile veraltet. Stattdessen,
Bitte verwenden Sie Cell.SetFormula(string,FormulaParseOptions,object).
Diese Eigenschaft wird seit Dezember 2019 12 Monate später entfernt.
Aspose entschuldigt sich für etwaige Unannehmlichkeiten.


###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cell`](/cells/python-net/de/aspose.cells/cell)
