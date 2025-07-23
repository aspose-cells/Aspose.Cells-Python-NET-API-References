---
title: multi_thread_reading proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1220
url: /it/aspose.cells/cells/multi_thread_reading/
is_root: false
---
##  multi_thread_reading proprietà

Ottiene o imposta se il modello di dati delle celle deve supportare la lettura multi-thread.
Il valore predefinito di questa proprietà è false.

###  Osservazioni

Se ci sono più thread che leggono contemporaneamente gli oggetti Row/Cell in questa raccolta,
questa proprietà dovrebbe essere impostata su true, altrimenti potrebbero essere prodotti risultati inaspettati.
Il supporto della lettura Multi-Thread potrebbe ridurre le prestazioni di accesso agli oggetti Row/Cell da questa raccolta.
Si prega di notare che alcune funzionalità non supportano la lettura Multi-Thread,
come la formattazione dei valori (per [`Cell.string_value`](/cells/python-net/it/aspose.cells/cell#string_value), [`Cell.display_string_value`](/cells/python-net/it/aspose.cells/cell#display_string_value), ecc.).
Quindi, anche impostando questa proprietà su true, tali API potrebbero comunque produrre risultati inattesi per la lettura Multi-Thread.
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
