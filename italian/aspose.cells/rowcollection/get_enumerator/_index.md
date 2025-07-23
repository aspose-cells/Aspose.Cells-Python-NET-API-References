---
title: Metodo get_enumerator
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 30
url: /it/aspose.cells/rowcollection/get_enumerator/
is_root: false
---
##  get_enumerator(self, reversed, sync) {#bool-bool}
Ottiene un enumeratore che scorre le righe attraverso questa raccolta


###  ritorna

L'enumeratore di riga


```python

def get_enumerator(self, reversed, sync):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| reversed | bool | se enumerare le righe in ordine inverso|
| sync | bool | se l'enumeratore restituito debba controllare la modifica della raccolta di righe<br/> e mantenersi sincronizzati con esso.|
###  Osservazioni

Se la raccolta di righe verrà modificata (da operazioni che potrebbero causare l'istanziazione di una nuova riga o
la riga esistente verrà rimossa) durante l'attraversamento con l'enumeratore,
dovrebbe essere utilizzato un enumeratore sincronizzato al posto dell'enumeratore normale in modo che la traversata possa continuare
dalla posizione subito successiva a quella percorsa dall'ultimo MoveNext().
Tuttavia, insieme al vantaggio che nessun elemento può essere saltato o attraversato ripetutamente,
lo svantaggio dell'enumeratore sincronizzato è che le prestazioni saranno un po' degradate
se confrontato con un enumeratore normale.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`RowCollection`](/cells/python-net/it/aspose.cells/rowcollection)
