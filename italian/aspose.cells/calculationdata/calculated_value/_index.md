---
title: calculated_value proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 60
url: /it/aspose.cells/calculationdata/calculated_value/
is_root: false
---
##  calculated_value proprietà

Ottiene o imposta il valore calcolato per questa funzione.

###  Osservazioni

L'utente deve impostare questa proprietà nel suo motore di calcolo personalizzato per le funzioni supportate dal motore,
e il valore impostato verrà restituito quando si otterrà questa proprietà in un secondo momento.
Il valore impostato può essere di tipi possibili di [`Cell.value`](/cells/python-net/it/aspose.cells/cell#value),
o un array di questo tipo di valori, oppure un Intervallo, un Nome, un'Area di Riferimento.
Ottenere questa proprietà prima di impostare il valore farà sì che la funzione venga calcolata
dal motore di calcolo predefinito di Aspose.Cells e quindi il valore calcolato sarà
verrà restituito (in genere dovrebbe essere #NAME? per le funzioni definite dall'utente).
###  Definizione:
```python
@property
def calculated_value(self):
    ...
@calculated_value.setter
def calculated_value(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`CalculationData`](/cells/python-net/it/aspose.cells/calculationdata)
