---
title: Metodo get_param_value_in_array_mode
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 40
url: /it/aspose.cells/calculationdata/get_param_value_in_array_mode/
is_root: false
---
##  get_param_value_in_array_mode {#int-int-int}
Ottiene i valori del parametro in corrispondenza dell'indice specificato.
Se il parametro è una sorta di espressione che deve essere calcolata,
quindi verrà calcolato in modalità array.


###  ritorna

Un array che contiene tutti gli elementi rappresentati dal parametro specificato.


```python
def get_param_value_in_array_mode(self, index, max_row_count, max_column_count):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| index | int | L'indice del parametro (in base 0)|
| max_row_count | int | Il limite del conteggio delle righe per la matrice restituita.<br/> Se non è positivo o è maggiore del conteggio delle righe effettivo, verrà utilizzato il conteggio delle righe effettivo.|
| max_column_count | int | Il limite del conteggio delle colonne per la matrice restituita.<br/> Se non è positivo o è maggiore del conteggio effettivo delle righe, verrà utilizzato il conteggio effettivo delle colonne.|
###  Osservazioni

Per un'espressione che deve essere calcolata, prendendo A:A+B:B come esempio:
In modalità valore verrà calcolato su un singolo valore in base alla base di cella corrente.
Ma in modalità array, tutti i valori di A1+B1,A2+B2,A3+B3,... verranno calcolati e utilizzati per costruire l'array restituito.
E per questo tipo di situazione, è meglio specificare il limite per il conteggio di righe/colonne
(come secondo [`Cells.max_data_row`](/cells/python-net/it/aspose.cells/cells#max_data_row) e [`Cells.max_data_column`](/cells/python-net/it/aspose.cells/cells#max_data_column)),
in caso contrario, l'array di grandi dimensioni restituito potrebbe aumentare il costo della memoria con una grande quantità di dati inutili.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`CalculationData`](/cells/python-net/it/aspose.cells/calculationdata)
