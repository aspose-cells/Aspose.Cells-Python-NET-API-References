---
title: License klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 930
url: /sv/aspose.cells/license/
is_root: false
---
##  License klass
Tillhandahåller metoder för att licensiera komponenten.



Typen License avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self)`](/cells/python-net/sv/aspose.cells/license/__init__/#) | Initierar en ny instans av den här klassen.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`set_license(self, license_name)`](/cells/python-net/sv/aspose.cells/license/set_license/#str) | Licensierar komponenten.|
| [`set_license(self, stream)`](/cells/python-net/sv/aspose.cells/license/set_license/#io.rawiobase) | Licensierar komponenten.|



###  Exempel

I det här exemplet kommer ett försök att hitta en licensfil med namnet MyLicense.lic att göras.
 i mappen som innehåller


komponenten, i mappen som innehåller den anropande assemblyn,
i mappen för postsammansättningen och sedan i de inbäddade resurserna i den anropande sammansättningen.

```python
from aspose.cells import License

license = License()
license.set_license("MyLicense.lic")

```

###  Se även
* modul [`aspose.cells`](..)
