---
title: DigitalSignature konstruktör
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 10
url: /sv/aspose.cells.digitalsignatures/digitalsignature/__init__/
is_root: false
---
##  \_\_init\_\_(själv, certifikat, kommentarer, signeringstid){#System.Security.Cryptography.X509Certificates.X509Certificate2-str-DateTime}
Konstruktör av digitala signaturer. Använder .Net-implementering.



```python

def __init__(self, certificate, comments, sign_time):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| certificate | System.Security.Cryptography.X509Certificates.X509Certificate2 | Certifikatobjektet som användes för att signera dokumentet.|
| comments | str | Syftet med underskriften.|
| sign_time | DateTime | UTC-tiden då dokumentet undertecknades.|


## \_\_init\_\_(self, rådata, lösenord, kommentarer, signeringstid){#bytes-str-str-DateTime}
Konstruktör av digitalSignature. Använder hoppborgsimplementeringen.



```python

def __init__(self, raw_data, password, comments, sign_time):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| raw_data | bytes | En byte-array som innehåller data från ett X.509-certifikat.|
| password | str | Lösenordet som krävs för att komma åt X.509-certifikatdata.|
| comments | str | Syftet med underskriften.|
| sign_time | DateTime | UTC-tiden då dokumentet undertecknades.|



###  Se även
* modul [`aspose.cells.digitalsignatures`](../../)
* klass [`DigitalSignature`](/cells/python-net/sv/aspose.cells.digitalsignatures/digitalsignature)
