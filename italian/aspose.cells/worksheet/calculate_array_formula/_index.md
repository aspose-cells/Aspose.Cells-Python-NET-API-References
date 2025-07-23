---
title: Metodo calculate_array_formula
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 80
url: /it/aspose.cells/worksheet/calculate_array_formula/
is_root: false
---
##  calculate_array_formula(self, formula, opts) {#str-aspose.cells.CalculationOptions}
Calcola una formula come formula matriciale.



```python

def calculate_array_formula(self, formula, opts):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| formula | str | Formula da calcolare.|
| opts | [`CalculationOptions`](/cells/python-net/it/aspose.cells/calculationoptions) | Opzioni per il calcolo della formula|


##  calculate_array_formula(self, formula, opts, max_row_count, max_column_count) {#str-aspose.cells.CalculationOptions-int-int}
Calcola una formula come formula matriciale.


###  ritorna

Risultato della formula calcolata.


```python

def calculate_array_formula(self, formula, opts, max_row_count, max_column_count):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| formula | str | Formula da calcolare.|
| opts | [`CalculationOptions`](/cells/python-net/it/aspose.cells/calculationoptions) | Opzioni per il calcolo della formula|
| max_row_count | int | il numero massimo di righe dei dati risultanti.<br/> Se non è positivo o è maggiore del conteggio effettivo delle righe, verrà utilizzato il conteggio effettivo delle righe.|
| max_column_count | int | il numero massimo di colonne dei dati risultanti.<br/> Se non è positivo o è maggiore del conteggio effettivo delle righe, verrà utilizzato il conteggio effettivo delle colonne.|
###  Osservazioni

La formula verrà considerata come una formula di matrice dinamica per calcolare la dimensione e il risultato.
La dimensione massima specificata dall'utente viene utilizzata nei casi in cui il risultato calcolato è un set di dati di grandi dimensioni
(ad esempio, il risultato calcolato può corrispondere a un'intera riga o colonna di dati)
ma l'utente non ha bisogno di un array così grande in base ai requisiti aziendali o per considerazioni sulle prestazioni.

##  calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data) {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-int-int-aspose.cells.CalculationData}
Calcola una formula come formula matriciale.


###  ritorna

Risultato della formula calcolata.


```python

def calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| formula | str | Formula da calcolare.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/it/aspose.cells/formulaparseoptions) |Opzioni per l'analisi della formula|
| c_opts | [`CalculationOptions`](/cells/python-net/it/aspose.cells/calculationoptions) | Opzioni per il calcolo della formula|
| base_cell_row | int | Indice di riga della cella base.|
| base_cell_column | int | Indice di colonna della cella base.|
| max_row_count | int | Numero massimo di righe di dati risultanti.<br/> Se non è positivo o è maggiore del conteggio effettivo delle righe, verrà utilizzato il conteggio effettivo delle righe.|
| max_column_count | int | Numero massimo di colonne dei dati risultanti.<br/> Se non è positivo o è maggiore del conteggio effettivo delle righe, verrà utilizzato il conteggio effettivo delle colonne.|
| calculation_data | [`CalculationData`](/cells/python-net/it/aspose.cells/calculationdata) | I dati di calcolo. Vengono utilizzati per la situazione<br/>che l'utente abbia bisogno di calcolare alcune formule statiche durante l'implementazione del motore di calcolo personalizzato.<br/>Per questo tipo di situazione, l'utente deve specificarlo con i dati di calcolo forniti<br/> per Aspose.Cells.AbstractCalculationEngine.Calculate.|
###  Osservazioni

La formula verrà considerata come una formula di matrice dinamica per calcolare la dimensione e il risultato.
La dimensione massima specificata dall'utente viene utilizzata nei casi in cui il risultato calcolato è un set di dati di grandi dimensioni
(ad esempio, il risultato calcolato può corrispondere a un'intera riga o colonna di dati)
ma l'utente non ha bisogno di un array così grande in base ai requisiti aziendali o per considerazioni sulle prestazioni.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Worksheet`](/cells/python-net/it/aspose.cells/worksheet)
