---
title: set_array_formula Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 310
url: /de/aspose.cells/cell/set_array_formula/
is_root: false
---
##  set_array_formula {#str-int-int}
Legt eine Array-Formel (ältere Array-Formel, eingegeben über STRG+UMSCHALT+EINGABETASTE in MS Excel) auf einen Zellbereich fest.



```python
def set_array_formula(self, array_formula, row_number, column_number):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| array_formula | str | Array-Formel.|
| row_number | int | Anzahl der Zeilen, die mit dem Ergebnis der Array-Formel gefüllt werden sollen.|
| column_number | int | Anzahl der Spalten, die mit dem Ergebnis der Array-Formel gefüllt werden sollen.|


##  set_array_formula {#str-int-int-aspose.cells.FormulaParseOptions}
Legt eine Array-Formel auf einen Zellbereich fest.



```python
def set_array_formula(self, array_formula, row_number, column_number, options):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| array_formula | str | Array-Formel.|
| row_number | int | Anzahl der Zeilen, die mit dem Ergebnis der Array-Formel gefüllt werden sollen.|
| column_number | int | Anzahl der Spalten, die mit dem Ergebnis der Array-Formel gefüllt werden sollen.|
| options | [`FormulaParseOptions`](/cells/python-net/de/aspose.cells/formulaparseoptions) | Optionen zum Parsen der Formel.|


##  set_array_formula {#str-int-int-bool-bool}
Legt eine Array-Formel auf einen Zellbereich fest.



```python
def set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| array_formula | str | Array-Formel.|
| row_number | int | Anzahl der Zeilen, die mit dem Ergebnis der Array-Formel gefüllt werden sollen.|
| column_number | int | Anzahl der Spalten, die mit dem Ergebnis der Array-Formel gefüllt werden sollen.|
| is_r1c1 | bool | ob die Formel eine R1C1-Formel ist|
| is_local | bool | ob die Formel gebietsschemaformatiert ist|
###  Bemerkungen

HINWEIS: Diese Klasse ist mittlerweile veraltet. Stattdessen,
Bitte verwenden Sie Cell.SetArrayFormula(string,int,int,FormulaParseOptions).
Diese Eigenschaft wird seit Dezember 2019 12 Monate später entfernt.
Aspose entschuldigt sich für etwaige Unannehmlichkeiten.

##  set_array_formula {#str-int-int-aspose.cells.FormulaParseOptions-list}
Legt eine Array-Formel auf einen Zellbereich fest.



```python
def set_array_formula(self, array_formula, row_number, column_number, options, values):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| array_formula | str | Array-Formel.|
| row_number | int | Anzahl der Zeilen, die mit dem Ergebnis der Array-Formel gefüllt werden sollen.|
| column_number | int | Anzahl der Spalten, die mit dem Ergebnis der Array-Formel gefüllt werden sollen.|
| options | [`FormulaParseOptions`](/cells/python-net/de/aspose.cells/formulaparseoptions) | Optionen zum Parsen der Formel.|
| values | list | Werte für die Zellen mit der angegebenen Array-Formel|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cell`](/cells/python-net/de/aspose.cells/cell)
