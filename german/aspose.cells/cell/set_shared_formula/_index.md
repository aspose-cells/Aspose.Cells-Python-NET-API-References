---
title: set_shared_formula Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 360
url: /de/aspose.cells/cell/set_shared_formula/
is_root: false
---
##  set_shared_formula(self, shared_formula, row_number, column_number) {#str-int-int}
Legt gemeinsame Formeln für einen Zellbereich fest.



```python

def set_shared_formula(self, shared_formula, row_number, column_number):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| shared_formula | str | Gemeinsame Formel.|
| row_number | int | Anzahl der Zeilen zum Ausfüllen der Formel.|
| column_number | int | Anzahl der Spalten zum Ausfüllen der Formel.|
###  Bemerkungen



##  set_shared_formula(self, shared_formula, row_number, column_number, options) {#str-int-int-aspose.cells.FormulaParseOptions}

Legt gemeinsame Formeln für einen Zellbereich fest.



```python

def set_shared_formula(self, shared_formula, row_number, column_number, options):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| shared_formula | str | Gemeinsame Formel.|
| row_number | int | Anzahl der Zeilen zum Ausfüllen der Formel.|
| column_number | int | Anzahl der Spalten zum Ausfüllen der Formel.|
| options | [`FormulaParseOptions`](/cells/python-net/de/aspose.cells/formulaparseoptions) | Optionen zum Parsen der Formel.|


##  set_shared_formula(self, shared_formula, row_number, column_number, is_r1c1, is_local) {#str-int-int-bool-bool}
Legt eine Formel für einen Zellbereich fest.



```python

def set_shared_formula(self, shared_formula, row_number, column_number, is_r1c1, is_local):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| shared_formula | str | Gemeinsame Formel.|
| row_number | int | Anzahl der Zeilen zum Ausfüllen der Formel.|
| column_number | int | Anzahl der Spalten zum Ausfüllen der Formel.|
| is_r1c1 | bool | ob die Formel die Formel R1C1 ist|
| is_local | bool | ob die Formel lokal formatiert ist|
###  Bemerkungen

HINWEIS: Diese Klasse ist mittlerweile veraltet. Stattdessen
Bitte verwenden Sie Cell.SetSharedFormula(string,int,int,FormulaParseOptions).
Diese Eigenschaft wird 12 Monate später (ab Dezember 2019) entfernt.
Aspose entschuldigt sich für etwaige Unannehmlichkeiten, die Ihnen möglicherweise entstanden sind.

##  set_shared_formula(self, shared_formula, row_number, column_number, options, values) {#str-int-int-aspose.cells.FormulaParseOptions-list}
Legt gemeinsame Formeln für einen Zellbereich fest.



```python

def set_shared_formula(self, shared_formula, row_number, column_number, options, values):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| shared_formula | str | Gemeinsame Formel.|
| row_number | int | Anzahl der Zeilen zum Ausfüllen der Formel.|
| column_number | int | Anzahl der Spalten zum Ausfüllen der Formel.|
| options | [`FormulaParseOptions`](/cells/python-net/de/aspose.cells/formulaparseoptions) | Optionen zum Parsen der Formel.|
| values | list | Werte für die Zellen mit der angegebenen gemeinsamen Formel|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cell`](/cells/python-net/de/aspose.cells/cell)
