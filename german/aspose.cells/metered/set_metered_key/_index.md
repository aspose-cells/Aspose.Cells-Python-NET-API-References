---
title: set_metered_key Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 60
url: /de/aspose.cells/metered/set_metered_key/
is_root: false
---
##  set_metered_key(self, public_key, private_key) {#str-str}
Legt den gemessenen öffentlichen und privaten Schlüssel fest.
Wenn Sie eine gebührenpflichtige Lizenz erwerben, sollte beim Starten der Anwendung diese API aufgerufen werden. Normalerweise reicht dies aus.
 Wenn jedoch das Hochladen der Verbrauchsdaten immer fehlschlägt und 24 Stunden überschreitet, wird die Lizenz auf den Evaluierungsstatus gesetzt.
Um solche Fälle zu vermeiden, sollten Sie den Lizenzstatus regelmäßig überprüfen. Wenn es sich um einen Evaluierungsstatus handelt, rufen Sie erneut die Nummer API an.



```python

def set_metered_key(self, public_key, private_key):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| public_key | str | öffentlicher Schlüssel|
| private_key | str | privater Schlüssel|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Metered`](/cells/python-net/de/aspose.cells/metered)
