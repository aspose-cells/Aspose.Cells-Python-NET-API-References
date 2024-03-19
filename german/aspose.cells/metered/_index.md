---
title: Metered Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1090
url: /de/aspose.cells/metered/
is_root: false
---
##  Metered Klasse
Stellt Methoden zum Festlegen des gemessenen Schlüssels bereit.



Der Typ Metered macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [__init__](/cells/python-net/de/aspose.cells/metered/__init__/#) | Initialisiert eine neue Instanz dieser Klasse.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [set_metered_key](/cells/python-net/de/aspose.cells/metered/set_metered_key/#str-str) | Legt einen gemessenen öffentlichen und privaten Schlüssel fest.<br/> Wenn Sie eine gebührenpflichtige Lizenz erwerben, sollte beim Starten der Anwendung API aufgerufen werden. Normalerweise reicht dies aus.<br/> Wenn jedoch das Hochladen der Verbrauchsdaten immer fehlschlägt und 24 Stunden überschritten werden, wird die Lizenz auf den Evaluierungsstatus gesetzt.<br/> Um einen solchen Fall zu vermeiden, sollten Sie regelmäßig den Lizenzstatus überprüfen. Wenn es sich um einen Teststatus handelt, rufen Sie diese erneut unter API an.|
| [get_consumption_quantity](/cells/python-net/de/aspose.cells/metered/get_consumption_quantity/#) | Ermittelt die Größe der Verbrauchsdatei|
| [get_consumption_credit](/cells/python-net/de/aspose.cells/metered/get_consumption_credit/#) | Erhält eine Verbrauchsgutschrift|
| [get_product_name](/cells/python-net/de/aspose.cells/metered/get_product_name/#) | Ruft den Produktnamen ab|
| [is_metered_licensed](/cells/python-net/de/aspose.cells/metered/is_metered_licensed/#) | Prüfen Sie, ob metered lizenziert ist|



###  Beispiel

In diesem Beispiel wird versucht, einen gemessenen öffentlichen und privaten Schlüssel festzulegen


```python
from aspose.cells import Metered

matered = Metered()
matered.set_metered_key("PublicKey", "PrivateKey")

```

###  Siehe auch
* Modul [`aspose.cells`](..)
