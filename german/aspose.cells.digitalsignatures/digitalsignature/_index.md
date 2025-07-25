---
title: DigitalSignature Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 10
url: /de/aspose.cells.digitalsignatures/digitalsignature/
is_root: false
---
##  DigitalSignature Klasse
Unterschrift in der Datei.



Der Typ DigitalSignature macht die folgenden Member verfügbar:

###  Konstrukteure
| Konstrukteur| Beschreibung|
| :- | :- |
| [`__init__(self, certificate, comments, sign_time)`](/cells/python-net/de/aspose.cells.digitalsignatures/digitalsignature/__init__/#system.security.cryptography.x509certificates.x509certificate2-str-datetime) | Konstruktor der digitalen Signatur. Verwendet die .Net-Implementierung.|
| [`__init__(self, raw_data, password, comments, sign_time)`](/cells/python-net/de/aspose.cells.digitalsignatures/digitalsignature/__init__/#bytes-str-str-datetime) |Konstruktor von digitalSignature. Verwendet die Bouncy Castle-Implementierung.|


###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [certificate](/cells/python-net/de/aspose.cells.digitalsignatures/digitalsignature/certificate) | Zertifikatsobjekt, das zum Signieren des Dokuments verwendet wurde.|
| [comments](/cells/python-net/de/aspose.cells.digitalsignatures/digitalsignature/comments) | Der Zweck der Unterschrift.|
| [sign_time](/cells/python-net/de/aspose.cells.digitalsignatures/digitalsignature/sign_time) | Der Zeitpunkt der Unterzeichnung des Dokuments.|
| [id](/cells/python-net/de/aspose.cells.digitalsignatures/digitalsignature/id) | Gibt eine GUID an, die mit der GUID der im Dokumentinhalt gespeicherten Signaturzeile abgeglichen werden kann.<br/> Der Standardwert ist eine leere GUID (nur Nullen).|
| [text](/cells/python-net/de/aspose.cells.digitalsignatures/digitalsignature/text) | Gibt den Text der tatsächlichen Signatur in der digitalen Signatur an.<br/> Der Standardwert ist „Leer“.|
| [image](/cells/python-net/de/aspose.cells.digitalsignatures/digitalsignature/image) | Gibt ein Bild für die digitale Signatur an.<br/> Der Standardwert ist null.|
| [provider_id](/cells/python-net/de/aspose.cells.digitalsignatures/digitalsignature/provider_id) | Gibt die Klassen-ID des Signaturanbieters an.<br/> Der Standardwert ist eine leere GUID (nur Nullen).|
| [is_valid](/cells/python-net/de/aspose.cells.digitalsignatures/digitalsignature/is_valid) | Wenn diese digitale Signatur gültig ist und das Dokument nicht manipuliert wurde,<br/> dieser Wert wird wahr sein.|
| [x_ad_es_type](/cells/python-net/de/aspose.cells.digitalsignatures/digitalsignature/x_ad_es_type) | XAdES-Typ.<br/> Der Standardwert ist „Keine“ (XAdES ist deaktiviert).|



###  Siehe auch
* Modul [`aspose.cells.digitalsignatures`](..)
