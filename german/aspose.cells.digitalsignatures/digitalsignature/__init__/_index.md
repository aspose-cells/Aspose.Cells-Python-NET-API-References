---
title: DigitalSignature Konstruktor
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 10
url: /de/aspose.cells.digitalsignatures/digitalsignature/__init__/
is_root: false
---
##  \_\_init\_\_(selbst, Zertifikat, Kommentare, Signierzeit){#System.Security.Cryptography.X509Certificates.X509Certificate2-str-DateTime}
Konstruktor der digitalen Signatur. Verwendet die .Net-Implementierung.



```python

def __init__(self, certificate, comments, sign_time):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| certificate | System.Security.Cryptography.X509Certificates.X509Certificate2 | Zertifikatsobjekt, das zum Signieren des Dokuments verwendet wurde.|
| comments | str | Der Zweck der Unterschrift.|
| sign_time | DateTime | Die UTC-Zeit, zu der das Dokument signiert wurde.|


## \_\_init\_\_(selbst, Rohdaten, Passwort, Kommentare, Signierzeit){#bytes-str-str-DateTime}
Konstruktor von digitalSignature. Verwendet die Bouncy Castle-Implementierung.



```python

def __init__(self, raw_data, password, comments, sign_time):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| raw_data | bytes | Ein Byte-Array, das Daten aus einem X.509-Zertifikat enthält.|
| password | str | Das für den Zugriff auf die X.509-Zertifikatsdaten erforderliche Kennwort.|
| comments | str | Der Zweck der Unterschrift.|
| sign_time | DateTime | Die UTC-Zeit, zu der das Dokument signiert wurde.|



###  Siehe auch
* Modul [`aspose.cells.digitalsignatures`](../../)
* Klasse [`DigitalSignature`](/cells/python-net/de/aspose.cells.digitalsignatures/digitalsignature)
