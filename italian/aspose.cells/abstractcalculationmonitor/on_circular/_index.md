---
title: Metodo on_circular
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 40
url: /it/aspose.cells/abstractcalculationmonitor/on_circular/
is_root: false
---
##  on_circular {#collections.abc.Iterator}
Implementa questo metodo per fare affari quando calcoli formule con riferimenti circolari.


###  ritorna

Indica se il motore della formula deve calcolare tali celle in modo circolare dopo questa chiamata.
True per consentire al motore delle formule di continuare a eseguire i calcoli per loro.
False per consentire al motore delle formule di contrassegnare semplicemente le celle come Calcolate.


```python
def on_circular(self, circular_cells_data):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| circular_cells_data | collections.abc.Iterator | IEnumerator con [`CalculationCell`](/cells/python-net/it/aspose.cells/calculationcell) elementi che rappresentano le celle che<br/> dipendono da riferimenti circolari.|
###  Osservazioni

Nell'implementazione l'utente può anche impostare il valore atteso come risultato calcolato
per parte/tutte quelle celle in modo che il motore della formula non le calcolerà in modo ricorsivo.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`AbstractCalculationMonitor`](/cells/python-net/it/aspose.cells/abstractcalculationmonitor)
* classe [`CalculationCell`](/cells/python-net/it/aspose.cells/calculationcell)
