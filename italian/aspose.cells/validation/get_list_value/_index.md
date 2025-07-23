---
title: Metodo get_list_value
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 70
url: /it/aspose.cells/validation/get_list_value/
is_root: false
---
##  get_list_value(self, row, column) {#int-int}
Ottieni il valore per l'elenco della convalida per la cella specificata.


###  ritorna

Valore per produrre l'elenco di questa convalida per la cella specificata.
Se l'elenco fa riferimento a un intervallo, il valore restituito sarà un oggetto [`ReferredArea`](/cells/python-net/it/aspose.cells/referredarea);
In caso contrario, il valore restituito potrebbe essere null, object[] o un semplice oggetto.


```python

def get_list_value(self, row, column):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| row | int | Indice di riga.|
| column | int | L'indice della colonna.|
###  Osservazioni

Solo per la convalida il cui tipo è Elenco ed è stato applicato alla cella specificata,
in caso contrario verrà restituito null.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`ReferredArea`](/cells/python-net/it/aspose.cells/referredarea)
* classe [`Validation`](/cells/python-net/it/aspose.cells/validation)
