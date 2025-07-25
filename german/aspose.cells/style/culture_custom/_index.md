---
title: culture_custom Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 170
url: /de/aspose.cells/style/culture_custom/
is_root: false
---
##  culture_custom Eigentum

Ruft die kulturabhängige Musterzeichenfolge für das Zahlenformat ab und legt sie fest.
Wenn für dieses Objekt kein Zahlenformat festgelegt wurde, wird null zurückgegeben.
Wenn das Zahlenformat integriert ist, wird die Musterzeichenfolge zurückgegeben, die der integrierten Zahl entspricht.

###  Bemerkungen

Für das integrierte Zahlenformat ist sowohl der Musterinhalt (z. B. ist ein integriertes Datumsformat für einige Gebietsschemas "m/d/y",
aber für einige andere Gebietsschemas wird es zu "d/m/y") und der Formatbezeichner(wie etwa
einige Gebietsschemas verwenden ein anderes Zeichen als „y“, um den Jahresteil für die Datumsformatierung darzustellen)
sind kulturabhängig;
Für benutzerdefinierte Formate werden nur die Formatbezeichner entsprechend der Kultur geändert.
andere Teile des Formatierungsmusters werden nicht geändert.
###  Definition:
```python
@property
def culture_custom(self):
    ...
@culture_custom.setter
def culture_custom(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Style`](/cells/python-net/de/aspose.cells/style)
