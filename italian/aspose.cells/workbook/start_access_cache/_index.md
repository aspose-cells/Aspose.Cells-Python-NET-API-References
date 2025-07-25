---
title: Metodo start_access_cache
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 400
url: /it/aspose.cells/workbook/start_access_cache/
is_root: false
---
##  start_access_cache(self, opts) {#aspose.cells.AccessCacheOptions}
Avvia la sessione che utilizza le cache per accedere ai dati.



```python

def start_access_cache(self, opts):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| opts | [`AccessCacheOptions`](/cells/python-net/it/aspose.cells/accesscacheoptions) | opzioni di accesso ai dati|
###  Osservazioni

Se la cache dell'accesso ai dati specificato richiede che alcuni modelli di dati nel foglio di lavoro siano "di sola lettura",
quindi i modelli di dati corrispondenti in ogni foglio di lavoro in questa cartella di lavoro saranno considerati "di sola lettura"
e l'utente non dovrebbe modificarne nessuno.


Dopo aver completato l'accesso ai dati, [`Workbook.close_access_cache`](/cells/python-net/it/aspose.cells/workbook/close_access_cache) dovrebbe
può essere richiamato con le stesse opzioni per cancellare tutte le cache e ripristinare la modalità di accesso normale.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook)
