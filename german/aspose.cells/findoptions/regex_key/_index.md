---
title: regex_key Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 110
url: /de/aspose.cells/findoptions/regex_key/
is_root: false
---
##  regex_key Eigentum

Gibt an, ob der gesuchte Schlüssel ein regulärer Ausdruck ist.
Wenn wahr, wird der gesuchte Schlüssel als regulärer Ausdruck genommen und analysiert.
Andernfalls wird der Schlüssel gemäß den Regeln in MS Excel analysiert.

###  Bemerkungen

Obwohl der Suchschlüssel als regulärer Ausdruck angegeben wurde,
Es kann gemäß der Angabe [`FindOptions.look_at_type`](/cells/python-net/de/aspose.cells/findoptions#look_at_type) umgestaltet werden.
Wenn der Typ beispielsweise [`LookAtType.CONTAINS`](/cells/python-net/de/aspose.cells/lookattype#CONTAINS) ist (das ist der Standardwert für diese Option),
Platzhalter werden automatisch am Anfang und Ende des Suchschlüssels hinzugefügt, um sicherzustellen, dass die Übereinstimmung
als "enthält" markiert. In diesem Fall werden die regulären Ausdrücke komplexer
und die Leistung wird ebenfalls abnehmen.
Aus Leistungsgründen ist es nicht erforderlich, die Regel für den regulären Ausdruck genau festzulegen.
Verwenden Sie [`FindOptions.look_at_type`](/cells/python-net/de/aspose.cells/findoptions#look_at_type) als zusätzliche Einschränkung und der Benutzer kann es als [`LookAtType.ENTIRE_CONTENT`](/cells/python-net/de/aspose.cells/lookattype#ENTIRE_CONTENT) festlegen
um eine bessere Leistung zu erzielen.
###  Definition:
```python
@property
def regex_key(self):
    ...
@regex_key.setter
def regex_key(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells`](../../)
* Klasse [`FindOptions`](/cells/python-net/de/aspose.cells/findoptions)
