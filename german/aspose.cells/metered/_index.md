---
title: Metered Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 980
url: /de/aspose.cells/metered/
is_root: false
---
##  Metered Klasse
Bietet Methoden zum Festlegen des gemessenen Schlüssels.



Der Typ Metered macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self)`](/cells/python-net/de/aspose.cells/metered/__init__/#) | Initialisiert eine neue Instanz dieser Klasse.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`set_metered_key(self, public_key, private_key)`](/cells/python-net/de/aspose.cells/metered/set_metered_key/#str-str) | Legt den gemessenen öffentlichen und privaten Schlüssel fest.<br/>Wenn Sie eine gebührenpflichtige Lizenz erwerben, sollte beim Starten der Anwendung diese API aufgerufen werden. Normalerweise reicht dies aus.<br/> Wenn jedoch das Hochladen der Verbrauchsdaten immer fehlschlägt und 24 Stunden überschreitet, wird die Lizenz auf den Evaluierungsstatus gesetzt.<br/> Um solche Fälle zu vermeiden, sollten Sie den Lizenzstatus regelmäßig überprüfen. Wenn es sich um einen Evaluierungsstatus handelt, rufen Sie erneut die Nummer API an.|
| [`get_consumption_quantity()`](/cells/python-net/de/aspose.cells/metered/get_consumption_quantity/#) | Ruft die Verbrauchsdateigröße ab|
| [`get_consumption_credit()`](/cells/python-net/de/aspose.cells/metered/get_consumption_credit/#) | Bekommt Verbrauchsguthaben|
| [`get_product_name(self)`](/cells/python-net/de/aspose.cells/metered/get_product_name/#) | Ruft den Produktnamen ab|
| [`is_metered_licensed()`](/cells/python-net/de/aspose.cells/metered/is_metered_licensed/#) | Prüfen Sie, ob Metered lizenziert ist|



###  Beispiel

In diesem Beispiel wird versucht, gemessene öffentliche und private Schlüssel festzulegen


```python
from aspose.cells import Metered

matered = Metered()
matered.set_metered_key("PublicKey", "PrivateKey")

```

###  Siehe auch
* Modul [`aspose.cells`](..)
