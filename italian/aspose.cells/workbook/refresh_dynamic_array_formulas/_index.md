---
title: Metodo refresh_dynamic_array_formulas
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 290
url: /it/aspose.cells/workbook/refresh_dynamic_array_formulas/
is_root: false
---
##  refresh_dynamic_array_formulas(self, calculate) {#bool}
Aggiorna le formule di matrice dinamica (si riversa in un nuovo intervallo di celle adiacenti in base ai dati correnti)
Le altre formule nella cartella di lavoro non verranno calcolate in modo ricorsivo, anche se utilizzate da formule di matrice dinamica.



```python

def refresh_dynamic_array_formulas(self, calculate):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| calculate | bool | Calcola e aggiorna i valori delle celle per quelle formule di matrice dinamica|


##  refresh_dynamic_array_formulas(self, calculate, copts) {#bool-aspose.cells.CalculationOptions}
Aggiorna le formule di matrice dinamica (si riversa in un nuovo intervallo di celle adiacenti in base ai dati correnti)



```python

def refresh_dynamic_array_formulas(self, calculate, copts):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| calculate | bool | Calcola e aggiorna i valori delle celle per quelle formule di matrice dinamica|
| copts | [`CalculationOptions`](/cells/python-net/it/aspose.cells/calculationoptions) | Le opzioni per il calcolo delle formule|
###  Osservazioni

Per motivi di prestazioni, non aggiorniamo automaticamente tutte le formule di array dinamici
quando la formula stessa o i dati a cui fa riferimento cambiano.
Quindi l'utente deve chiamare manualmente questo metodo dopo quelle operazioni che possono influenzare le formule di array dinamici,
come l'importazione/impostazione di valori di celle, l'inserimento/eliminazione di righe/colonne/intervalli, ecc.

Per la maggior parte delle formule con funzioni, il calcolo dell'intervallo di fuoriuscita richiede anche il calcolo della formula,
quindi in generale è preferibile il valore vero per il flag "calcola".
Se la formula è semplice, come un riferimento a un intervallo o a un array (ad esempio "=C1:E5", "={1,2;3,4}", ...),
funzione semplice su un intervallo o array (ad esempio "=ABS(C1:E5)", "=1+{1,2;3,4}", ...),
e tutte le formule verranno calcolate in seguito (ad esempio da [`Workbook.calculate_formula`](/cells/python-net/it/aspose.cells/workbook/calculate_formula)),
quindi utilizzando un valore falso per il flag "calcola" è possibile evitare il calcolo duplicato a vantaggio delle prestazioni.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook)
