---
title: Metodo set_formula
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 340
url: /it/aspose.cells/cell/set_formula/
is_root: false
---
##  set_formula {#str-any}
Imposta la formula e il valore (risultato calcolato) della formula.



```python
def set_formula(self, formula, value):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| formula | str | La formula.|
| value | any |Il valore (risultato calcolato) della formula.|


##  set_formula {#str-aspose.cells.FormulaParseOptions-any}
Imposta la formula e il valore (risultato calcolato) della formula.



```python
def set_formula(self, formula, options, value):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| formula | str | La formula.|
| options | [`FormulaParseOptions`](/cells/python-net/it/aspose.cells/formulaparseoptions) | Opzioni per l'analisi della formula.|
| value | any |Il valore (risultato calcolato) della formula.|


##  set_formula {#str-bool-bool-any}
Imposta la formula e il valore della formula.



```python
def set_formula(self, formula, is_r1c1, is_local, value):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| formula | str | La formula.|
| is_r1c1 | bool | Se la formula è la formula R1C1.|
| is_local | bool | Indica se la formula è formattata in base alle impostazioni locali.|
| value | any | Il valore della formula.|
###  Osservazioni

NOTA: questa classe è ora obsoleta. Invece,
si prega di utilizzare Cell.SetFormula(stringa,FormulaParseOptions,oggetto).
Questa proprietà verrà rimossa 12 mesi dopo a partire da dicembre 2019.
Aspose si scusa per eventuali disagi riscontrati.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/it/aspose.cells/cell)
