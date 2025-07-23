---
title: Metodo set_metered_key
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 60
url: /it/aspose.cells/metered/set_metered_key/
is_root: false
---
##  set_metered_key(self, public_key, private_key) {#str-str}
Imposta la chiave pubblica e privata misurata.
Se si acquista una licenza a consumo, all'avvio della richiesta è necessario chiamare il numero API; solitamente è sufficiente.
 Tuttavia, se non si riesce a caricare sempre i dati di consumo e si superano le 24 ore, la licenza verrà impostata sullo stato di valutazione,
Per evitare casi del genere, dovresti controllare regolarmente lo stato della licenza; se è in stato di valutazione, chiama nuovamente lo API.



```python

def set_metered_key(self, public_key, private_key):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| public_key | str | chiave pubblica|
| private_key | str | chiave privata|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Metered`](/cells/python-net/it/aspose.cells/metered)
