---
title: Metodo start_access_cache
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 300
url: /it/aspose.cells/worksheet/start_access_cache/
is_root: false
---
##  start_access_cache {#aspose.cells.AccessCacheOptions}
Avvia la sessione che utilizza le cache per accedere ai dati in questo foglio di lavoro.



```python
def start_access_cache(self, opts):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| opts | [`AccessCacheOptions`](/cells/python-net/it/aspose.cells/accesscacheoptions) | opzioni di accesso ai dati|
###  Osservazioni

Dopo aver terminato l'accesso ai dati, [`Worksheet.close_access_cache`](/cells/python-net/it/aspose.cells/worksheet/close_access_cache) dovrebbe
essere richiamato con le stesse opzioni per cancellare tutte le cache e ripristinare la normale modalità di accesso.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Worksheet`](/cells/python-net/it/aspose.cells/worksheet)
