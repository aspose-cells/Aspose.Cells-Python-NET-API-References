---
title: Metodo refresh_dynamic_array_formulas
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 270
url: /it/aspose.cells/workbook/refresh_dynamic_array_formulas/
is_root: false
---
##  refresh_dynamic_array_formulas {#bool}
Aggiorna le formule di matrice dinamica (distribuite in un nuovo intervallo di celle vicine in base ai dati correnti)
Altre formule nella cartella di lavoro non verranno calcolate in modo ricorsivo anche se utilizzate da formule in matrice dinamica.



```python
def refresh_dynamic_array_formulas(self, calculate):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| calculate | bool | Indica se calcola e aggiorna i valori delle celle per le formule in matrice dinamica|


##  refresh_dynamic_array_formulas {#bool-aspose.cells.CalculationOptions}
Aggiorna le formule di matrice dinamica (distribuite in un nuovo intervallo di celle vicine in base ai dati correnti)



```python
def refresh_dynamic_array_formulas(self, calculate, copts):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| calculate | bool | Indica se calcola e aggiorna i valori delle celle per le formule in matrice dinamica|
| copts | [`CalculationOptions`](/cells/python-net/it/aspose.cells/calculationoptions) | Le opzioni per il calcolo delle formule|
###  Osservazioni

Per ragioni di prestazioni, non aggiorniamo automaticamente tutte le formule di matrice dinamica
quando la formula stessa o i dati a cui fa riferimento sono cambiati.
Pertanto l'utente deve chiamare manualmente questo metodo dopo quelle operazioni che possono influenzare le formule di matrice dinamica,
come importare/impostare valori di cella, inserire/eliminare righe/colonne/intervalli, ... ecc.

Per la maggior parte delle formule con funzioni, il calcolo dell'intervallo di fuoriuscita richiede anche il calcolo della formula,
quindi in generale è preferibile il valore vero per il flag "calcola".
Se la formula è semplice, ad esempio un riferimento a un intervallo o un array (ad esempio "=C1:E5", "={1,2;3,4}", ...),
funzione semplice su un intervallo o array (ad esempio "=ABS(C1:E5)", "=1+{1,2;3,4}", ...),
e tutte le formule verranno calcolate successivamente (ad esempio [`Workbook.calculate_formula`](/cells/python-net/it/aspose.cells/workbook/calculate_formula)),
quindi l'utilizzo di false vlaue per il flag "calculate" può evitare il calcolo duplicato a vantaggio delle prestazioni.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook)
