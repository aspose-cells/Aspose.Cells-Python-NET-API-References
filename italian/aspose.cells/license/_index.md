---
title: License classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 1020
url: /it/aspose.cells/license/
is_root: false
---
##  License classe
Fornisce metodi per concedere in licenza il componente.



Il tipo License espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [__init__](/cells/python-net/it/aspose.cells/license/__init__/#) | Inizializza una nuova istanza di questa classe.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [set_license](/cells/python-net/it/aspose.cells/license/set_license/#str) | Concede in licenza il componente.|
| [set_license](/cells/python-net/it/aspose.cells/license/set_license/#io.RawIOBase) | Concede in licenza il componente.|



###  Esempio

In questo esempio, verrà effettuato un tentativo di trovare un file di licenza denominato MyLicense.lic
 nella cartella che contiene


il componente, nella cartella che contiene l'assembly chiamante,
nella cartella dell'assembly in ingresso e poi nelle risorse embedded dell'assembly chiamante.

```python
from aspose.cells import License

license = License()
license.set_license("MyLicense.lic")

```

###  Guarda anche
* modulo [`aspose.cells`](..)
