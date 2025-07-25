---
title: set_array_formula Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 320
url: /de/aspose.cells/cell/set_array_formula/
is_root: false
---
##  set_array_formula(self, array_formula, row_number, column_number) {#str-int-int}
Legt eine Arrayformel (alte Arrayformel, die in MS Excel über STRG+UMSCHALT+EINGABE eingegeben wurde) für einen Zellbereich fest.



```python

def set_array_formula(self, array_formula, row_number, column_number):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| array_formula | str | Array-Formel.|
| row_number | int | Anzahl der Zeilen, in die das Ergebnis der Arrayformel eingefügt werden soll.|
| column_number | int | Anzahl der Spalten, in die das Ergebnis der Arrayformel eingefügt werden soll.|


##  set_array_formula(self, array_formula, row_number, column_number, options) {#str-int-int-aspose.cells.FormulaParseOptions}
Legt eine Matrixformel für einen Zellbereich fest.



```python

def set_array_formula(self, array_formula, row_number, column_number, options):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| array_formula | str | Array-Formel.|
| row_number | int | Anzahl der Zeilen, in die das Ergebnis der Arrayformel eingefügt werden soll.|
| column_number | int | Anzahl der Spalten, in die das Ergebnis der Arrayformel eingefügt werden soll.|
| options | [`FormulaParseOptions`](/cells/python-net/de/aspose.cells/formulaparseoptions) | Optionen zum Parsen der Formel.|


##  set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local) {#str-int-int-bool-bool}
Legt eine Matrixformel für einen Zellbereich fest.



```python

def set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| array_formula | str | Array-Formel.|
| row_number | int | Anzahl der Zeilen, in die das Ergebnis der Arrayformel eingefügt werden soll.|
| column_number | int | Anzahl der Spalten, in die das Ergebnis der Arrayformel eingefügt werden soll.|
| is_r1c1 | bool | ob die Formel die Formel R1C1 ist|
| is_local | bool | ob die Formel lokal formatiert ist|
###  Bemerkungen

HINWEIS: Diese Klasse ist mittlerweile veraltet. Stattdessen
Bitte verwenden Sie Cell.SetArrayFormula(string,int,int,FormulaParseOptions).
Diese Eigenschaft wird 12 Monate später (ab Dezember 2019) entfernt.
Aspose entschuldigt sich für etwaige Unannehmlichkeiten, die Ihnen möglicherweise entstanden sind.

##  set_array_formula(self, array_formula, row_number, column_number, options, values) {#str-int-int-aspose.cells.FormulaParseOptions-list}
Legt eine Matrixformel für einen Zellbereich fest.



```python

def set_array_formula(self, array_formula, row_number, column_number, options, values):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| array_formula | str | Array-Formel.|
| row_number | int | Anzahl der Zeilen, in die das Ergebnis der Arrayformel eingefügt werden soll.|
| column_number | int | Anzahl der Spalten, in die das Ergebnis der Arrayformel eingefügt werden soll.|
| options | [`FormulaParseOptions`](/cells/python-net/de/aspose.cells/formulaparseoptions) | Optionen zum Parsen der Formel.|
| values | list | Werte für die Zellen mit der angegebenen Array-Formel|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cell`](/cells/python-net/de/aspose.cells/cell)
