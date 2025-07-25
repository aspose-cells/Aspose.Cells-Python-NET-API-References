---
title: number_category_type Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 700
url: /de/aspose.cells/cell/number_category_type/
is_root: false
---
##  number_category_type Eigentum

Stellt den Kategorietyp der Zahlenformatierung dieser Zelle dar.

###  Bemerkungen

Wenn das Formatierungsmuster einer Zelle mit bedingten Formatierungsmustern kombiniert wird,
dann entspricht der zurückgegebene Typ dem Teil, der für den aktuellen Wert dieser Zelle verwendet wird.
Wenn das Formatierungsmuster für diese Zelle beispielsweise "#,##0;(#,##0);"-";@" ist,
Wenn der Zellenwert dann numerisch und nicht 0 ist, ist der zurückgegebene Typ [`NumberCategoryType.NUMBER`](/cells/python-net/de/aspose.cells/numbercategorytype#NUMBER).
Wenn der Zellenwert 0 oder kein numerischer Wert ist, lautet der zurückgegebene Typ [`NumberCategoryType.TEXT`](/cells/python-net/de/aspose.cells/numbercategorytype#TEXT).
###  Definition:
```python
@property
def number_category_type(self):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`Cell`](/cells/python-net/de/aspose.cells/cell)
* Klasse [`NumberCategoryType`](/cells/python-net/de/aspose.cells/numbercategorytype)
