---
title: Metodo get_leafs
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 160
url: /it/aspose.cells/cell/get_leafs/
is_root: false
---
##  get_leafs(self) {#}
Ottieni tutte le celle che fanno riferimento direttamente a questa cella e che devono essere aggiornate quando questa cella viene modificata.


###  ritorna

Enumeratore per enumerare tutti i dipendenti (Cell)


```python

def get_leafs(self):
    ...
```


###  Osservazioni

NOTA: questa classe è ora obsoleta. Invece,
utilizzare Cell.GetDependentsInCalculation(bool) per ottenere tutti i dipendenti nella catena di calcolo.
Questa proprietà verrà rimossa 12 mesi dopo, a partire da maggio 2022.
Aspose si scusa per ogni eventuale disagio arrecato.

##  get_leafs(self, recursive) {#bool}
Ottieni tutte le celle che verranno aggiornate quando questa cella viene modificata.


###  ritorna

Enumeratore per enumerare tutti i dipendenti (Cell)


```python

def get_leafs(self, recursive):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| recursive | bool | Se restituisce le foglie che non fanno riferimento direttamente a questa cella<br/> ma riferimento ad altre foglie di questa cellula|
###  Osservazioni

NOTA: questa classe è ora obsoleta. Invece,
utilizzare Cell.GetDependentsInCalculation(bool) per ottenere tutti i dipendenti nella catena di calcolo.
Questa proprietà verrà rimossa 12 mesi dopo, a partire da maggio 2022.
Aspose si scusa per ogni eventuale disagio arrecato.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/it/aspose.cells/cell)
