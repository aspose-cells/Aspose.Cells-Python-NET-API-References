---
title: Metodo set_dynamic_array_formula
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 330
url: /it/aspose.cells/cell/set_dynamic_array_formula/
is_root: false
---
##  set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-bool}
Imposta la formula di matrice dinamica e, se possibile, fa in modo che la formula si diffonda nelle celle vicine.


###  ritorna

l'intervallo in cui dovrebbe riversarsi la formula.


```python
def set_dynamic_array_formula(self, array_formula, options, calculate_value):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| array_formula | str |l'espressione della formula|
| options | [`FormulaParseOptions`](/cells/python-net/it/aspose.cells/formulaparseoptions) | opzioni per analizzare la formula.<br/> L'opzione "Analizza" verrà ignorata e la formula verrà sempre analizzata immediatamente|
| calculate_value | bool | se calcolare questa formula di matrice dinamica per le celle nell'intervallo rovesciato.|


##  set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-list-bool-bool}
Imposta la formula di matrice dinamica e, se possibile, fa in modo che la formula si diffonda nelle celle vicine.


###  ritorna

l'intervallo in cui dovrebbe riversarsi la formula.


```python
def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| array_formula | str |l'espressione della formula|
| options | [`FormulaParseOptions`](/cells/python-net/it/aspose.cells/formulaparseoptions) | opzioni per analizzare la formula.<br/> L'opzione "Analizza" verrà ignorata e la formula verrà sempre analizzata immediatamente|
| values | list | valori (risultati calcolati) per quelle celle con una determinata formula di matrice dinamica|
| calculate_range | bool | Indica se calcolare l'intervallo rovesciato per questa formula in matrice dinamica.<br/>Se il parametro "values" non è null e questo flag è false,<br/> quindi l'altezza dell'intervallo rovesciato sarà valori. Lunghezza e larghezza saranno valori[0].Lunghezza.|
| calculate_value | bool | se calcolare questa formula di matrice dinamica per le celle nell'intervallo rovesciato quando "valori" è nullo<br/> o l'elemento corrispondente in "valori" per una cella è nullo.|


##  set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions}
Imposta la formula di matrice dinamica e, se possibile, fa in modo che la formula si diffonda nelle celle vicine.


###  ritorna

l'intervallo in cui dovrebbe riversarsi la formula.


```python
def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| array_formula | str |l'espressione della formula|
| options | [`FormulaParseOptions`](/cells/python-net/it/aspose.cells/formulaparseoptions) | opzioni per analizzare la formula.<br/> L'opzione "Analizza" verrà ignorata e la formula verrà sempre analizzata immediatamente|
| values | list | valori (risultati calcolati) per quelle celle con una determinata formula di matrice dinamica|
| calculate_range | bool | Indica se calcolare l'intervallo rovesciato per questa formula in matrice dinamica.<br/>Se il parametro "values" non è null e questo flag è false,<br/> quindi l'altezza dell'intervallo rovesciato sarà valori. Lunghezza e larghezza saranno valori[0].Lunghezza.|
| calculate_value | bool | se calcolare questa formula di matrice dinamica per le celle nell'intervallo rovesciato quando "valori" è nullo<br/> o l'elemento corrispondente in "valori" per una cella è nullo.|
| copts | [`CalculationOptions`](/cells/python-net/it/aspose.cells/calculationoptions) | Le opzioni per il calcolo della formula.<br/> In genere, ai fini delle prestazioni, la proprietà [`CalculationOptions.recursive`](/cells/python-net/it/aspose.cells/calculationoptions#recursive) dovrebbe essere falsa.|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/it/aspose.cells/cell)
