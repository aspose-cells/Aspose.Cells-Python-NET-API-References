---
title: Metodo get_enumerator
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 70
url: /it/aspose.cells/row/get_enumerator/
is_root: false
---
##  get_enumerator(self, reversed, sync) {#bool-bool}
Ottiene un enumeratore che scorre le celle attraverso questa riga.


###  ritorna

L'enumeratore di celle


```python

def get_enumerator(self, reversed, sync):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| reversed | bool |se enumerare le celle in ordine inverso|
| sync | bool | se l'enumeratore restituito deve controllare la modifica delle celle in questa riga<br/> e mantenersi sincronizzati con esso.|
###  Osservazioni

Se la riga verrà modificata (da operazioni che potrebbero causare l'istanziazione del nuovo Cell o
esistente Cell da rimuovere) durante la traversata con l'enumeratore,
dovrebbe essere utilizzato un enumeratore sincronizzato al posto dell'enumeratore normale in modo che la traversata possa continuare
dalla posizione subito successiva a quella percorsa dall'ultimo MoveNext().
Tuttavia, insieme al vantaggio che nessun elemento può essere saltato o attraversato ripetutamente,
lo svantaggio dell'enumeratore sincronizzato è che le prestazioni saranno un po' degradate
se confrontato con un enumeratore normale.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Row`](/cells/python-net/it/aspose.cells/row)
