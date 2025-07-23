---
title: look_at_type Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 90
url: /de/aspose.cells/findoptions/look_at_type/
is_root: false
---
##  look_at_type Eigentum

Schauen Sie sich den Typ an.

###  Bemerkungen

Wenn [`FindOptions.regex_key`](/cells/python-net/de/aspose.cells/findoptions#regex_key) wahr ist und der Benutzer die genaue Regel für den regulären Ausdruck angegeben hat,
Aus Leistungsgründen sollte diese Eigenschaft auf [`LookAtType.ENTIRE_CONTENT`](/cells/python-net/de/aspose.cells/lookattype#ENTIRE_CONTENT) festgelegt werden.
Andernfalls werden wir den Suchschlüssel umgestalten, um sicherzustellen, dass er dem spezifischen Typ entsprechend abgeglichen werden kann.
Wenn der Typ beispielsweise [`LookAtType.CONTAINS`](/cells/python-net/de/aspose.cells/lookattype#CONTAINS) ist (das ist der Standardwert für diese Eigenschaft),
Wir fügen am Anfang und Ende des Suchschlüssels automatisch Platzhalter hinzu.
In diesem Fall werden die regulären Ausdrücke komplexer und die Leistung nimmt ebenfalls ab.
###  Definition:
```python
@property
def look_at_type(self):
    ...
@look_at_type.setter
def look_at_type(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`FindOptions`](/cells/python-net/de/aspose.cells/findoptions)
* Klasse [`LookAtType`](/cells/python-net/de/aspose.cells/lookattype)
