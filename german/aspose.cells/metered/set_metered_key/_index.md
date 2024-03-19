---
title: set_metered_key Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 60
url: /de/aspose.cells/metered/set_metered_key/
is_root: false
---
##  set_metered_key {#str-str}
Legt einen gemessenen öffentlichen und privaten Schlüssel fest.
 Wenn Sie eine gebührenpflichtige Lizenz erwerben, sollte beim Starten der Anwendung API aufgerufen werden. Normalerweise reicht dies aus.
 Wenn jedoch das Hochladen der Verbrauchsdaten immer fehlschlägt und 24 Stunden überschritten werden, wird die Lizenz auf den Evaluierungsstatus gesetzt.
Um einen solchen Fall zu vermeiden, sollten Sie regelmäßig den Lizenzstatus überprüfen. Wenn es sich um einen Teststatus handelt, rufen Sie diese erneut unter API an.



```python
def set_metered_key(self, public_key, private_key):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| public_key | str | Öffentlicher Schlüssel|
| private_key | str | Privat Schlüssel|



###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Metered`](/cells/python-net/de/aspose.cells/metered)
