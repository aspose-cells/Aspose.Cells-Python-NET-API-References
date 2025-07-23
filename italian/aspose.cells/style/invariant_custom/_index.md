---
title: invariant_custom proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 260
url: /it/aspose.cells/style/invariant_custom/
is_root: false
---
##  invariant_custom proprietà

Ottiene la stringa modello indipendente dalla cultura per il formato numerico.
Se non è stato impostato alcun formato numerico per questo oggetto, verrà restituito null.
Se il formato numerico è incorporato, verrà restituita la stringa modello corrispondente al numero incorporato.

###  Osservazioni

Per i formati numerici incorporati, il contenuto del modello restituito dipende ancora dalla cultura,
ad esempio, per alcune impostazioni locali restituisce "m/g/y" e per altre impostazioni locali restituisce "g/m/y".
La differenza rispetto a [`Style.culture_custom`](/cells/python-net/it/aspose.cells/style#culture_custom) è (questo è anche il significato di "indipendente dalla cultura"):
gli specificatori di formato e i separatori vengono mantenuti come standard, ad esempio '/' verrà sempre utilizzato come separatore di data e ora
e "y" verrà sempre utilizzato come parte dell'"anno", indipendentemente dall'altro carattere speciale utilizzato per le impostazioni locali specifiche.
###  Definizione:
```python
@property
def invariant_custom(self):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Style`](/cells/python-net/it/aspose.cells/style)
