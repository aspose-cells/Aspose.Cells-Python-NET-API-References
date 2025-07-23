---
title: invariant_custom Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 260
url: /de/aspose.cells/style/invariant_custom/
is_root: false
---
##  invariant_custom Eigentum

Ruft die kulturunabhängige Musterzeichenfolge für das Zahlenformat ab.
Wenn für dieses Objekt kein Zahlenformat festgelegt wurde, wird null zurückgegeben.
Wenn das Zahlenformat integriert ist, wird die Musterzeichenfolge zurückgegeben, die der integrierten Zahl entspricht.

###  Bemerkungen

Bei integrierten Zahlenformaten ist der zurückgegebene Musterinhalt immer noch kulturabhängig.
Beispielsweise wird für einige Gebietsschemas „m/d/y“ und für andere Gebietsschemas „d/m/y“ zurückgegeben.
Der Unterschied zu [`Style.culture_custom`](/cells/python-net/de/aspose.cells/style#culture_custom) ist (das bedeutet auch kulturunabhängig):
Die Formatbezeichner und Trennzeichen bleiben standardmäßig erhalten, so wird beispielsweise '/' immer als Datums-/Uhrzeit-Trennzeichen verwendet.
und „y“ wird immer als „Jahres“-Teil verwendet, unabhängig davon, welches andere Sonderzeichen für das jeweilige Gebietsschema verwendet wird.
###  Definition:
```python
@property
def invariant_custom(self):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Style`](/cells/python-net/de/aspose.cells/style)
