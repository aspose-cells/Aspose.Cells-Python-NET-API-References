---
title: built_in_preference proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 30
url: /it/aspose.cells/defaultstylesettings/built_in_preference/
is_root: false
---
##  built_in_preference proprietà

Indica se la proprietà per il formato dei numeri è preferibile quando lo stile definisce sia un numero incorporato sia un modello personalizzato.
Il valore predefinito è falso, ovvero per impostazione predefinita verrà utilizzato un modello personalizzato per formattare i valori, a condizione che non sia vuoto per uno stile.

###  Osservazioni

Quando si carica una cartella di lavoro da un file modello esistente, è possibile che per uno stile siano definiti sia il numero incorporato sia il modello personalizzato.
Questa proprietà determina se utilizzare il numero predefinito o il modello personalizzato quando si formattano i valori con lo stile.
###  Definizione:
```python
@property
def built_in_preference(self):
    ...
@built_in_preference.setter
def built_in_preference(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`DefaultStyleSettings`](/cells/python-net/it/aspose.cells/defaultstylesettings)
