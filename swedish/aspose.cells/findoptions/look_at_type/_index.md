---
title: look_at_type fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 90
url: /sv/aspose.cells/findoptions/look_at_type/
is_root: false
---
##  look_at_type fastighet

Titta på typen.

###  Anmärkningar

När [`FindOptions.regex_key`](/cells/python-net/sv/aspose.cells/findoptions#regex_key) är sant och användaren har angett den exakta regeln för regexen,
Av prestandahänsyn bör den här egenskapen anges som [`LookAtType.ENTIRE_CONTENT`](/cells/python-net/sv/aspose.cells/lookattype#ENTIRE_CONTENT).
Annars kommer vi att omstrukturera söknyckeln för att säkerställa att den kan matchas enligt den specifika typen.
Till exempel, när typen är [`LookAtType.CONTAINS`](/cells/python-net/sv/aspose.cells/lookattype#CONTAINS) (detta är standardvärdet för den här egenskapen),
Vi lägger automatiskt till jokertecken i början och slutet av söknyckeln.
I det här fallet blir de reguljära uttrycken mer komplexa och prestandan minskar också.
###  Definition:
```python
@property
def look_at_type(self):
    ...
@look_at_type.setter
def look_at_type(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`FindOptions`](/cells/python-net/sv/aspose.cells/findoptions)
* klass [`LookAtType`](/cells/python-net/sv/aspose.cells/lookattype)
