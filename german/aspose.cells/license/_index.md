---
title: License Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 930
url: /de/aspose.cells/license/
is_root: false
---
##  License Klasse
Bietet Methoden zum Lizenzieren der Komponente.



Der Typ License macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self)`](/cells/python-net/de/aspose.cells/license/__init__/#) | Initialisiert eine neue Instanz dieser Klasse.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`set_license(self, license_name)`](/cells/python-net/de/aspose.cells/license/set_license/#str) | Lizenziert die Komponente.|
| [`set_license(self, stream)`](/cells/python-net/de/aspose.cells/license/set_license/#io.rawiobase) | Lizenziert die Komponente.|



###  Beispiel

In diesem Beispiel wird versucht, eine Lizenzdatei mit dem Namen MyLicense.lic zu finden
 in dem Ordner, der enthält


die Komponente, in dem Ordner, der die aufrufende Assembly enthält,
im Ordner der Einstiegsassembly und dann in den eingebetteten Ressourcen der aufrufenden Assembly.

```python
from aspose.cells import License

license = License()
license.set_license("MyLicense.lic")

```

###  Siehe auch
* Modul [`aspose.cells`](..)
