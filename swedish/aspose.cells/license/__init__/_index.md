---
title: License konstruktör
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 10
url: /sv/aspose.cells/license/__init__/
is_root: false
---
##  \_\_init\_\_(själv){#}
Initierar en ny instans av den här klassen.



```python

def __init__(self):
    ...
```



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
* modul [`aspose.cells`](../../)
* klass [`License`](/cells/python-net/sv/aspose.cells/license)
