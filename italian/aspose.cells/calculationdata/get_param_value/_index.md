---
title: Metodo get_param_value
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 30
url: /it/aspose.cells/calculationdata/get_param_value/
is_root: false
---
##  get_param_value(self, index) {#int}
Ottiene l'oggetto valore rappresentato del parametro in corrispondenza dell'indice specificato.


###  ritorna

Il valore calcolato del parametro.


```python

def get_param_value(self, index):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| index | int | L'indice del parametro (basato su 0)|
###  Osservazioni

Per un parametro:

Se è un valore semplice, restituisce il valore semplice stesso;


Se è un riferimento, restituisce l'oggetto ReferredArea;


Se fa riferimento a set di dati con più valori, restituisce un array di oggetti;



Se si tratta di un tipo di espressione che deve essere calcolata, verrà calcolata in modalità valore
generalmente verrà restituito un singolo valore in base alla base di celle corrente. Ad esempio,
se un parametro della formula di D2 è A:A+B:B, allora verrà calcolato e restituito A2+B2.
Tuttavia, se questo parametro è stato specificato come modalità array
(da [`Workbook.update_custom_function_definition`](/cells/python-net/it/aspose.cells/workbook/update_custom_function_definition)
o [`FormulaParseOptions.custom_function_definition`](/cells/python-net/it/aspose.cells/formulaparseoptions#custom_function_definition)),
quindi verrà restituito un array(object[][]) i cui elementi sono A1+B1,A2+B2,....


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`CalculationData`](/cells/python-net/it/aspose.cells/calculationdata)
