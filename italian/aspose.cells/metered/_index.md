---
title: Metered classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 980
url: /it/aspose.cells/metered/
is_root: false
---
##  Metered classe
Fornisce metodi per impostare la chiave misurata.



Il tipo Metered espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self)`](/cells/python-net/it/aspose.cells/metered/__init__/#) | Inizializza una nuova istanza di questa classe.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`set_metered_key(self, public_key, private_key)`](/cells/python-net/it/aspose.cells/metered/set_metered_key/#str-str) | Imposta la chiave pubblica e privata misurata.<br/>Se si acquista una licenza a consumo, all'avvio della richiesta è necessario chiamare il numero API; solitamente è sufficiente.<br/> Tuttavia, se non si riesce a caricare sempre i dati di consumo e si superano le 24 ore, la licenza verrà impostata sullo stato di valutazione,<br/> Per evitare casi del genere, dovresti controllare regolarmente lo stato della licenza; se è in stato di valutazione, chiama nuovamente lo API.|
| [`get_consumption_quantity()`](/cells/python-net/it/aspose.cells/metered/get_consumption_quantity/#) | Ottiene la dimensione del file di consumo|
| [`get_consumption_credit()`](/cells/python-net/it/aspose.cells/metered/get_consumption_credit/#) | Ottiene credito al consumo|
| [`get_product_name(self)`](/cells/python-net/it/aspose.cells/metered/get_product_name/#) | Ottiene il nome del prodotto|
| [`is_metered_licensed()`](/cells/python-net/it/aspose.cells/metered/is_metered_licensed/#) | Controllare se il contatore è concesso in licenza|



###  Esempio

In questo esempio, verrà effettuato un tentativo di impostare una chiave pubblica e privata misurata


```python
from aspose.cells import Metered

matered = Metered()
matered.set_metered_key("PublicKey", "PrivateKey")

```

###  Guarda anche
* modulo [`aspose.cells`](..)
