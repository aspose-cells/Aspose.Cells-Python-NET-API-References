---
title: look_at_type proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 90
url: /it/aspose.cells/findoptions/look_at_type/
is_root: false
---
##  look_at_type proprietà

Guarda il tipo.

###  Osservazioni

Quando [`FindOptions.regex_key`](/cells/python-net/it/aspose.cells/findoptions#regex_key) è vero e l'utente ha specificato la regola esatta per l'espressione regolare,
per motivi di prestazioni questa proprietà dovrebbe essere impostata su [`LookAtType.ENTIRE_CONTENT`](/cells/python-net/it/aspose.cells/lookattype#ENTIRE_CONTENT).
Altrimenti riorganizzeremo la chiave di ricerca per garantire che possa essere abbinata in base al tipo specifico.
Ad esempio, quando il tipo è [`LookAtType.CONTAINS`](/cells/python-net/it/aspose.cells/lookattype#CONTAINS) (questo è il valore predefinito per questa proprietà),
aggiungeremo automaticamente i caratteri jolly all'inizio e alla fine della chiave di ricerca.
In questo caso le espressioni regolari diventeranno più complesse e anche le prestazioni diminuiranno.
###  Definizione:
```python
@property
def look_at_type(self):
    ...
@look_at_type.setter
def look_at_type(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`FindOptions`](/cells/python-net/it/aspose.cells/findoptions)
* classe [`LookAtType`](/cells/python-net/it/aspose.cells/lookattype)
