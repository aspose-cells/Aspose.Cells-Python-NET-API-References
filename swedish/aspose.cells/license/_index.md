---
title: License klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1020
url: /sv/aspose.cells/license/
is_root: false
---
##  License klass
Tillhandahåller metoder för att licensiera komponenten.



Typen License avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [__init__](/cells/python-net/sv/aspose.cells/license/__init__/#) | Initierar en ny instans av den här klassen.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [set_license](/cells/python-net/sv/aspose.cells/license/set_license/#str) | Licensierar komponenten.|
| [set_license](/cells/python-net/sv/aspose.cells/license/set_license/#io.RawIOBase) | Licensierar komponenten.|



###  Exempel

I det här exemplet kommer ett försök att göras att hitta en licensfil med namnet MyLicense.lic
 i mappen som innehåller


komponenten, i mappen som innehåller den anropande församlingen,
i mappen för postförsamlingen och sedan i de inbäddade resurserna för den anropande församlingen.

```python
from aspose.cells import License

license = License()
license.set_license("MyLicense.lic")

```

###  Se även
* modul [`aspose.cells`](..)
