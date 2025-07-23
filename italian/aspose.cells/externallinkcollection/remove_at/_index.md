---
title: Metodo remove_at
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 40
url: /it/aspose.cells/externallinkcollection/remove_at/
is_root: false
---
##  remove_at(self, index) {#int}
Rimuove il collegamento esterno specificato dalla cartella di lavoro.



```python

def remove_at(self, index):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| index | int | l'indice del collegamento esterno da rimuovere.|
###  Osservazioni

Quando si rimuove il collegamento esterno, verranno rimosse anche tutte le formule che fanno riferimento ad esso perché
i riferimenti diventano non validi.

##  remove_at(self, index, update_references_as_local) {#int-bool}
Rimuove il collegamento esterno specificato dalla cartella di lavoro.



```python

def remove_at(self, index, update_references_as_local):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| index | int | l'indice del collegamento esterno da rimuovere.|
| update_references_as_local | bool | Aggiornare tutti i riferimenti del collegamento esterno specificato al riferimento della cartella di lavoro corrente.<br/> Per maggiori dettagli su questo parametro, chiamare il numero [`ExternalLinkCollection.clear`](/cells/python-net/it/aspose.cells/externallinkcollection/clear).|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`ExternalLinkCollection`](/cells/python-net/it/aspose.cells/externallinkcollection)
