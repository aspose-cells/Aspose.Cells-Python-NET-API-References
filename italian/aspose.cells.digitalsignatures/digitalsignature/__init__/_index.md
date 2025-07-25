---
title: DigitalSignature costruttore
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 10
url: /it/aspose.cells.digitalsignatures/digitalsignature/__init__/
is_root: false
---
##  \_\_init\_\_(self, certificato, commenti, sign_time){#System.Security.Cryptography.X509Certificates.X509Certificate2-str-DateTime}
Costruttore di digitalSignature. Utilizza l'implementazione .Net.



```python

def __init__(self, certificate, comments, sign_time):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| certificate | System.Security.Cryptography.X509Certificates.X509Certificate2 | Oggetto certificato utilizzato per firmare il documento.|
| comments | str | Lo scopo della firma.|
| sign_time | DateTime | Ora UTC in cui il documento è stato firmato.|


## \_\_init\_\_(self, dati_grezzi, password, commenti, sign_time){#bytes-str-str-DateTime}
Costruttore di digitalSignature. Utilizza l'implementazione Bouncy Castle.



```python

def __init__(self, raw_data, password, comments, sign_time):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| raw_data | bytes | Un array di byte contenente dati da un certificato X.509.|
| password | str | Password richiesta per accedere ai dati del certificato X.509.|
| comments | str | Lo scopo della firma.|
| sign_time | DateTime | Ora UTC in cui il documento è stato firmato.|



###  Guarda anche
* modulo [`aspose.cells.digitalsignatures`](../../)
* classe [`DigitalSignature`](/cells/python-net/it/aspose.cells.digitalsignatures/digitalsignature)
