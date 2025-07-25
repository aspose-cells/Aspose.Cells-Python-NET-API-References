---
title: License Konstruktor
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 10
url: /de/aspose.cells/license/__init__/
is_root: false
---
##  \_\_init\_\_(selbst){#}
Initialisiert eine neue Instanz dieser Klasse.



```python

def __init__(self):
    ...
```



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
* Modul [`aspose.cells`](../../)
* Klasse [`License`](/cells/python-net/de/aspose.cells/license)
