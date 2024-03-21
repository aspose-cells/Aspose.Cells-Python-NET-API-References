---
title: Metodo set_array_formula
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 310
url: /it/aspose.cells/cell/set_array_formula/
is_root: false
---
##  set_array_formula {#str-int-int}
Imposta una formula di matrice (formula di matrice legacy inserita tramite CTRL+MAIUSC+INVIO in ms Excel) su un intervallo di celle.



```python
def set_array_formula(self, array_formula, row_number, column_number):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| array_formula | str | Formula matriciale.|
| row_number | int | Numero di righe per popolare il risultato della formula di matrice.|
| column_number | int | Numero di colonne per popolare il risultato della formula di matrice.|


##  set_array_formula {#str-int-int-aspose.cells.FormulaParseOptions}
Imposta una formula di matrice su un intervallo di celle.



```python
def set_array_formula(self, array_formula, row_number, column_number, options):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| array_formula | str | Formula matriciale.|
| row_number | int | Numero di righe per popolare il risultato della formula di matrice.|
| column_number | int | Numero di colonne per popolare il risultato della formula di matrice.|
| options | [`FormulaParseOptions`](/cells/python-net/it/aspose.cells/formulaparseoptions) | Opzioni per l'analisi della formula.|


##  set_array_formula {#str-int-int-bool-bool}
Imposta una formula di matrice su un intervallo di celle.



```python
def set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| array_formula | str | Formula matriciale.|
| row_number | int | Numero di righe per popolare il risultato della formula di matrice.|
| column_number | int | Numero di colonne per popolare il risultato della formula di matrice.|
| is_r1c1 | bool | se la formula è la formula R1C1|
| is_local | bool | se la formula è formattata in base alle impostazioni locali|
###  Osservazioni

NOTA: questa classe è ora obsoleta. Invece,
si prega di utilizzare Cell.SetArrayFormula(string,int,int,FormulaParseOptions).
Questa proprietà verrà rimossa 12 mesi dopo a partire da dicembre 2019.
Aspose si scusa per eventuali disagi riscontrati.

##  set_array_formula {#str-int-int-aspose.cells.FormulaParseOptions-list}
Imposta una formula di matrice su un intervallo di celle.



```python
def set_array_formula(self, array_formula, row_number, column_number, options, values):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| array_formula | str | Formula matriciale.|
| row_number | int | Numero di righe per popolare il risultato della formula di matrice.|
| column_number | int | Numero di colonne per popolare il risultato della formula di matrice.|
| options | [`FormulaParseOptions`](/cells/python-net/it/aspose.cells/formulaparseoptions) | Opzioni per l'analisi della formula.|
| values | list | valori per quelle celle con una determinata formula di matrice|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/it/aspose.cells/cell)
