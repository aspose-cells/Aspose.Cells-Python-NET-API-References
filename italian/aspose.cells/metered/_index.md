---
title: Metered classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 1090
url: /it/aspose.cells/metered/
is_root: false
---
##  Metered classe
Fornisce metodi per impostare la chiave misurata.



Il tipo Metered espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [__init__](/cells/python-net/it/aspose.cells/metered/__init__/#) | Inizializza una nuova istanza di questa classe.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [set_metered_key](/cells/python-net/it/aspose.cells/metered/set_metered_key/#str-str) | Imposta la chiave pubblica e privata misurata.<br/> Se acquisti una licenza a consumo, quando avvii l'applicazione, dovresti chiamare questo numero API, normalmente è sufficiente.<br/> Tuttavia, se non si riesce sempre a caricare i dati di consumo e si superano le 24 ore, la licenza verrà impostata sullo stato di valutazione,<br/> per evitare questo caso, dovresti controllare regolarmente lo stato della licenza, se è lo stato di valutazione, chiama di nuovo lo API.|
| [get_consumption_quantity](/cells/python-net/it/aspose.cells/metered/get_consumption_quantity/#) | Ottiene la dimensione del file di consumo|
| [get_consumption_credit](/cells/python-net/it/aspose.cells/metered/get_consumption_credit/#) | Ottiene credito al consumo|
| [get_product_name](/cells/python-net/it/aspose.cells/metered/get_product_name/#) | Ottiene il nome del prodotto|
| [is_metered_licensed](/cells/python-net/it/aspose.cells/metered/is_metered_licensed/#) | Controlla se il contatore è concesso in licenza|



###  Esempio

In questo esempio, verrà effettuato un tentativo di impostare la chiave pubblica e privata misurata


```python
from aspose.cells import Metered

matered = Metered()
matered.set_metered_key("PublicKey", "PrivateKey")

```

###  Guarda anche
* modulo [`aspose.cells`](..)
