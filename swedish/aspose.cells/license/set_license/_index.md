---
title: set_license metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells/license/set_license/
is_root: false
---
##  set_license(self, license_name) {#str}
Licensierar komponenten.



```python

def set_license(self, license_name):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| license_name | str |  |
###  Anmärkningar

Försöker hitta licensen på följande platser:


1. Explicit sökväg.


2. Mappen som innehåller komponentsammansättningen Aspose.


3. Mappen som innehåller klientens anropande sammansättning.


4. Mappen som innehåller postens (startup) sammansättning.


5. En inbäddad resurs i klientens anropande sammansättning.


**Notera:**Försöker bara hitta licensen på dessa platser i .NET Compact Framework:


1. Explicit sökväg.


2. En inbäddad resurs i klientens anropande sammansättning.
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
Kan vara ett fullständigt eller kort filnamn eller namnet på en inbäddad resurs.
Använd en tom sträng för att växla till utvärderingsläge.


##  set_license(self, stream) {#io.RawIOBase}
Licensierar komponenten.



```python

def set_license(self, stream):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| stream | io.RawIOBase |En stream som innehåller licensen.|
###  Anmärkningar

Använd den här metoden för att ladda en licens från en stream.
###  Exempel


```python
from aspose.cells import License

license = License()
license.set_license(myStream)

```



###  Se även
* modul [`aspose.cells`](../../)
* klass [`License`](/cells/python-net/sv/aspose.cells/license)
