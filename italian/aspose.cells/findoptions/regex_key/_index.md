---
title: regex_key proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 110
url: /it/aspose.cells/findoptions/regex_key/
is_root: false
---
##  regex_key proprietà

Indica se la chiave cercata è un'espressione regolare.
Se vero, la chiave cercata verrà interpretata come espressione regolare e analizzata.
Altrimenti la chiave verrà analizzata secondo le regole di MS Excel.

###  Osservazioni

Anche se la chiave di ricerca è stata specificata come regex,
può essere rielaborato secondo quanto specificato [`FindOptions.look_at_type`](/cells/python-net/it/aspose.cells/findoptions#look_at_type).
Ad esempio, quando il tipo è [`LookAtType.CONTAINS`](/cells/python-net/it/aspose.cells/lookattype#CONTAINS) (questo è il valore predefinito per questa opzione),
i caratteri jolly verranno aggiunti automaticamente all'inizio e alla fine della chiave di ricerca per garantire che la corrispondenza sia
selezionato come "contiene". In questo caso, le espressioni regolari diventeranno più complesse
e anche le prestazioni diminuiranno.
Pertanto, per motivi di prestazioni, se l'utente ha specificato la regola esatta per l'espressione regolare, non è necessario
utilizzare [`FindOptions.look_at_type`](/cells/python-net/it/aspose.cells/findoptions#look_at_type) come vincolo aggiuntivo e l'utente può impostarlo come [`LookAtType.ENTIRE_CONTENT`](/cells/python-net/it/aspose.cells/lookattype#ENTIRE_CONTENT)
per ottenere prestazioni migliori.
###  Definizione:
```python
@property
def regex_key(self):
    ...
@regex_key.setter
def regex_key(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`FindOptions`](/cells/python-net/it/aspose.cells/findoptions)
