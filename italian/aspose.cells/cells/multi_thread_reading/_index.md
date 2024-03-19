---
title: multi_thread_reading proprietà
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 1190
url: /it/aspose.cells/cells/multi_thread_reading/
is_root: false
---
##  multi_thread_reading proprietà

Ottiene o imposta se il modello dati delle celle deve supportare la lettura multi-thread.
Il valore predefinito di questa proprietà è false.

###  Osservazioni

Se sono presenti più thread per leggere contemporaneamente gli oggetti Row/Cell in questa raccolta,
questa proprietà deve essere impostata come true, altrimenti potrebbero essere prodotti risultati imprevisti.
Il supporto della lettura multi-thread potrebbe ridurre le prestazioni per l'accesso agli oggetti Row/Cell da questa raccolta.
Tieni presente che alcune funzionalità non supportano la lettura multi-thread,
come i valori di formattazione (per [`Cell.string_value`](/cells/python-net/it/aspose.cells/cell#string_value), [`Cell.display_string_value`](/cells/python-net/it/aspose.cells/cell#display_string_value), .ecc.).
Pertanto, anche con questa proprietà impostata su true, tali API potrebbero comunque fornire risultati imprevisti per la lettura multi-thread.
###  Definizione:
```python
@property
def multi_thread_reading(self):
    ...
@multi_thread_reading.setter
def multi_thread_reading(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cells`](/cells/python-net/it/aspose.cells/cells)
