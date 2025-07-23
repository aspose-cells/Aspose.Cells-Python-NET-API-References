---
title: Metodo set_dynamic_array_formula
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 340
url: /it/aspose.cells/cell/set_dynamic_array_formula/
is_root: false
---
##  set_dynamic_array_formula(self, array_formula, options, calculate_value) {#str-aspose.cells.FormulaParseOptions-bool}
Imposta una formula di matrice dinamica e, se possibile, fa sì che la formula si estenda alle celle adiacenti.


###  ritorna

l'intervallo entro cui dovrebbe estendersi la formula.


```python

def set_dynamic_array_formula(self, array_formula, options, calculate_value):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| array_formula | str | l'espressione della formula|
| options | [`FormulaParseOptions`](/cells/python-net/it/aspose.cells/formulaparseoptions) | opzioni per analizzare la formula.<br/> L'opzione "Analizza" verrà ignorata e la formula verrà sempre analizzata immediatamente|
| calculate_value | bool | se calcolare questa formula di matrice dinamica per le celle nell'intervallo distribuito.|
###  Osservazioni

l'intervallo restituito potrebbe non essere lo stesso di quello effettivo in cui si riversa questa formula di matrice dinamica.
Se nell'intervallo sono presenti celle non vuote, la formula verrà impostata solo per la cella corrente e contrassegnata come "#SPILL!".
Ma per questo tipo di situazione restituiamo comunque l'intervallo completo in cui dovrebbe estendersi questa formula.

##  set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value) {#str-aspose.cells.FormulaParseOptions-list-bool-bool}
Imposta una formula di matrice dinamica e, se possibile, fa sì che la formula si estenda alle celle adiacenti.


###  ritorna

l'intervallo entro cui dovrebbe estendersi la formula.


```python

def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| array_formula | str | l'espressione della formula|
| options | [`FormulaParseOptions`](/cells/python-net/it/aspose.cells/formulaparseoptions) | opzioni per analizzare la formula.<br/> L'opzione "Analizza" verrà ignorata e la formula verrà sempre analizzata immediatamente|
| values | list |valori (risultati calcolati) per quelle celle con la formula di matrice dinamica fornita|
| calculate_range | bool | Calcola l'intervallo di dispersione per questa formula di matrice dinamica.<br/>Se il parametro "values" non è nullo e questo flag è falso,<br/> quindi l'altezza dell'intervallo versato sarà valori.La lunghezza e la larghezza saranno valori[0].Length.|
| calculate_value | bool | se calcolare questa formula di matrice dinamica per quelle celle nell'intervallo travasato quando "valori" è nullo<br/> oppure l'elemento corrispondente in "valori" per una cella è nullo.|
###  Osservazioni

l'intervallo restituito potrebbe non essere lo stesso di quello effettivo in cui si riversa questa formula di matrice dinamica.
Se nell'intervallo sono presenti celle non vuote, la formula verrà impostata solo per la cella corrente e contrassegnata come "#SPILL!".
Ma per questo tipo di situazione restituiamo comunque l'intervallo completo in cui dovrebbe estendersi questa formula.

##  set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts) {#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions}
Imposta una formula di matrice dinamica e, se possibile, fa sì che la formula si estenda alle celle adiacenti.


###  ritorna

l'intervallo entro cui dovrebbe estendersi la formula.


```python

def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| array_formula | str | l'espressione della formula|
| options | [`FormulaParseOptions`](/cells/python-net/it/aspose.cells/formulaparseoptions) | opzioni per analizzare la formula.<br/> L'opzione "Analizza" verrà ignorata e la formula verrà sempre analizzata immediatamente|
| values | list |valori (risultati calcolati) per quelle celle con la formula di matrice dinamica fornita|
| calculate_range | bool | Calcola l'intervallo di dispersione per questa formula di matrice dinamica.<br/>Se il parametro "values" non è nullo e questo flag è falso,<br/> quindi l'altezza dell'intervallo versato sarà valori.La lunghezza e la larghezza saranno valori[0].Length.|
| calculate_value | bool | se calcolare questa formula di matrice dinamica per quelle celle nell'intervallo travasato quando "valori" è nullo<br/> oppure l'elemento corrispondente in "valori" per una cella è nullo.|
| copts | [`CalculationOptions`](/cells/python-net/it/aspose.cells/calculationoptions) | Opzioni per il calcolo della formula.<br/> In genere, per motivi di prestazioni, la proprietà [`CalculationOptions.recursive`](/cells/python-net/it/aspose.cells/calculationoptions#recursive) dovrebbe essere falsa.|
###  Osservazioni

l'intervallo restituito potrebbe non essere lo stesso di quello effettivo in cui si riversa questa formula di matrice dinamica.
Se nell'intervallo sono presenti celle non vuote, la formula verrà impostata solo per la cella corrente e contrassegnata come "#SPILL!".
Ma per questo tipo di situazione restituiamo comunque l'intervallo completo in cui dovrebbe estendersi questa formula.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/it/aspose.cells/cell)
