---
title: refer_to_sheet_with_same_name proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 90
url: /it/aspose.cells/copyoptions/refer_to_sheet_with_same_name/
is_root: false
---
##  refer_to_sheet_with_same_name proprietà

In MS Excel, quando si copiano formule che fanno riferimento ad altri fogli di lavoro mentre si copia un foglio di lavoro in un altro,
le formule copiate devono fare riferimento alla cartella di lavoro di origine.
Tuttavia, in alcune situazioni l'utente potrebbe aver bisogno che le formule copiate facciano riferimento a fogli di lavoro con lo stesso nome
nella stessa cartella di lavoro, ad esempio quando tali fogli di lavoro sono stati copiati prima di questa operazione di copia,
allora questa proprietà dovrebbe essere mantenuta come vera.

###  Osservazioni

Il valore predefinito è vero.
###  Definizione:
```python
@property
def refer_to_sheet_with_same_name(self):
    ...
@refer_to_sheet_with_same_name.setter
def refer_to_sheet_with_same_name(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`CopyOptions`](/cells/python-net/it/aspose.cells/copyoptions)
