---
title: Metodo get_array_mode_parameters
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells/customfunctiondefinition/get_array_mode_parameters/
is_root: false
---
##  get_array_mode_parameters(self, function_name) {#str}
Ottiene gli indici dei parametri della funzione personalizzata specificata che devono essere calcolati in modalità array.


###  ritorna

Indici dei parametri che devono essere calcolati in modalità array per una determinata funzione personalizzata.
Il valore predefinito è null, non esiste alcun parametro che debba essere calcolato in modalità array per la funzione personalizzata.


```python

def get_array_mode_parameters(self, function_name):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| function_name | str | Nome della funzione personalizzata.|
###  Osservazioni

Per un'espressione che deve essere calcolata, prendendo come esempio A:A+B:B:
Generalmente in modalità valore verrà calcolato un singolo valore in base alla base di celle corrente.
Ma in modalità array, tutti i valori di A1+B1, A2+B2, A3+B3,... verranno calcolati e utilizzati per il calcolo.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`CustomFunctionDefinition`](/cells/python-net/it/aspose.cells/customfunctiondefinition)
