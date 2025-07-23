---
title: License costruttore
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 10
url: /it/aspose.cells/license/__init__/
is_root: false
---
##  \_\_init\_\_(self){#}
Inizializza una nuova istanza di questa classe.



```python

def __init__(self):
    ...
```



###  Esempio

In questo esempio, verrà effettuato un tentativo di trovare un file di licenza denominato MyLicense.lic
 nella cartella che contiene


il componente, nella cartella che contiene l'assembly chiamante,
nella cartella dell'assembly di immissione e quindi nelle risorse incorporate dell'assembly chiamante.

```python
from aspose.cells import License

license = License()
license.set_license("MyLicense.lic")

```



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`License`](/cells/python-net/it/aspose.cells/license)
