---
title: culture_custom proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 170
url: /it/aspose.cells/style/culture_custom/
is_root: false
---
##  culture_custom proprietà

Ottiene e imposta la stringa modello dipendente dalla cultura per il formato numerico.
Se non è stato impostato alcun formato numerico per questo oggetto, verrà restituito null.
Se il formato numerico è incorporato, verrà restituita la stringa modello corrispondente al numero incorporato.

###  Osservazioni

Per il formato numerico incorporato, sia il contenuto del modello (ad esempio, un formato di data incorporato è "m/g/a" per alcune impostazioni locali,
ma per alcune altre impostazioni locali diventa "g/m/a") e lo specificatore di formato (ad esempio,
(alcune impostazioni locali utilizzano un carattere diverso da "y" per rappresentare la parte dell'anno nella formattazione della data)
dipendono dalla cultura;
Per il formato personalizzato specificato dall'utente, solo gli specificatori di formato vengono modificati in base alla cultura,
altre parti del modello di formattazione non verranno modificate.
###  Definizione:
```python
@property
def culture_custom(self):
    ...
@culture_custom.setter
def culture_custom(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Style`](/cells/python-net/it/aspose.cells/style)
