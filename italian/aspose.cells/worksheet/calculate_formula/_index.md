---
title: Metodo calculate_formula
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 90
url: /it/aspose.cells/worksheet/calculate_formula/
is_root: false
---
##  calculate_formula {#str}
Calcola una formula.


###  ritorna

Risultato della formula calcolata.


```python
def calculate_formula(self, formula):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| formula | str | Formula da calcolare.|


##  calculate_formula {#str-aspose.cells.CalculationOptions}
Calcola direttamente un'espressione di formula.


###  ritorna

Risultato calcolato della formula data.
L'oggetto restituito può essere dei possibili tipi [`Cell.value`](/cells/python-net/it/aspose.cells/cell#value) o ReferredArea.


```python
def calculate_formula(self, formula, opts):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| formula | str | Formula da calcolare.|
| opts | [`CalculationOptions`](/cells/python-net/it/aspose.cells/calculationoptions) | Opzioni per il calcolo della formula|
###  Osservazioni

La formula verrà calcolata proprio come è stata impostata sulla cella A1.
E la formula verrà presa come formula normale.
Se è necessario che la formula venga calcolata come formula di matrice e per ottenere una matrice per il risultato calcolato,
si prega di utilizzare invece [`Worksheet.calculate_array_formula`](/cells/python-net/it/aspose.cells/worksheet/calculate_array_formula).

##  calculate_formula {#aspose.cells.CalculationOptions-bool}
Calcola tutte le formule in questo foglio di lavoro.



```python
def calculate_formula(self, options, recursive):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| options | [`CalculationOptions`](/cells/python-net/it/aspose.cells/calculationoptions) | Opzioni per il calcolo|
| recursive | bool | Vero significa che se le celle del foglio di lavoro dipendono dalle celle di altri fogli di lavoro,<br/>verranno calcolate anche le celle dipendenti in altri fogli di lavoro.<br/> Falso significa che tutte le formule nel foglio di lavoro sono state calcolate e i valori sono corretti.|


##  calculate_formula {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-aspose.cells.CalculationData}
Calcola direttamente un'espressione di formula.


###  ritorna

Risultato calcolato della formula data.
L'oggetto restituito può essere dei possibili tipi [`Cell.value`](/cells/python-net/it/aspose.cells/cell#value) o ReferredArea.


```python
def calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| formula | str | Formula da calcolare.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/it/aspose.cells/formulaparseoptions) | Opzioni per l'analisi della formula.|
| c_opts | [`CalculationOptions`](/cells/python-net/it/aspose.cells/calculationoptions) | Opzioni per il calcolo della formula.|
| base_cell_row | int | L'indice di riga della cella base.|
| base_cell_column | int | L'indice della colonna della cella base.|
| calculation_data | [`CalculationData`](/cells/python-net/it/aspose.cells/calculationdata) | I dati di calcolo. È usato per la situazione<br/>l'utente deve calcolare alcune formule statiche durante l'implementazione del motore di calcolo personalizzato.<br/>Per questo tipo di situazione, l'utente deve specificarlo con i dati di calcolo forniti<br/> per [`AbstractCalculationEngine.calculate`](/cells/python-net/it/aspose.cells/abstractcalculationengine/calculate).|
###  Osservazioni

La formula verrà calcolata proprio come se fosse stata impostata sulla cella base specificata.
la formula verrà presa come formula normale. Se è necessario che la formula venga calcolata come formula di matrice
e per ottenere un array per il risultato calcolato, utilizzare
[`Worksheet.calculate_array_formula`](/cells/python-net/it/aspose.cells/worksheet/calculate_array_formula) invece.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Worksheet`](/cells/python-net/it/aspose.cells/worksheet)
