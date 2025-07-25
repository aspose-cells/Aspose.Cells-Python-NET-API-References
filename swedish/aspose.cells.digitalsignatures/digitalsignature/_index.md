---
title: DigitalSignature klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 10
url: /sv/aspose.cells.digitalsignatures/digitalsignature/
is_root: false
---
##  DigitalSignature klass
Underskrift i filen.



Typen DigitalSignature avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self, certificate, comments, sign_time)`](/cells/python-net/sv/aspose.cells.digitalsignatures/digitalsignature/__init__/#system.security.cryptography.x509certificates.x509certificate2-str-datetime) | Konstruktör av digitala signaturer. Använder .Net-implementering.|
| [`__init__(self, raw_data, password, comments, sign_time)`](/cells/python-net/sv/aspose.cells.digitalsignatures/digitalsignature/__init__/#bytes-str-str-datetime) |Konstruktör av digitalSignature. Använder hoppborgsimplementeringen.|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [certificate](/cells/python-net/sv/aspose.cells.digitalsignatures/digitalsignature/certificate) | Certifikatobjektet som användes för att signera dokumentet.|
| [comments](/cells/python-net/sv/aspose.cells.digitalsignatures/digitalsignature/comments) | Syftet med underskriften.|
| [sign_time](/cells/python-net/sv/aspose.cells.digitalsignatures/digitalsignature/sign_time) | Tidpunkten då dokumentet undertecknades.|
| [id](/cells/python-net/sv/aspose.cells.digitalsignatures/digitalsignature/id) | Anger ett GUID som kan korsrefereras med GUID:t för signaturraden som lagras i dokumentinnehållet.<br/> Standardvärdet är tomt (bara nollor) Guid.|
| [text](/cells/python-net/sv/aspose.cells.digitalsignatures/digitalsignature/text) | Anger texten för den faktiska signaturen i den digitala signaturen.<br/> Standardvärdet är Tomt.|
| [image](/cells/python-net/sv/aspose.cells.digitalsignatures/digitalsignature/image) | Anger en bild för den digitala signaturen.<br/> Standardvärdet är null.|
| [provider_id](/cells/python-net/sv/aspose.cells.digitalsignatures/digitalsignature/provider_id) | Anger klass-ID för signaturleverantören.<br/> Standardvärdet är tomt (bara nollor) Guid.|
| [is_valid](/cells/python-net/sv/aspose.cells.digitalsignatures/digitalsignature/is_valid) | Om denna digitala signatur är giltig och dokumentet inte har manipulerats,<br/> detta värde kommer att vara sant.|
| [x_ad_es_type](/cells/python-net/sv/aspose.cells.digitalsignatures/digitalsignature/x_ad_es_type) | XAdES-typ.<br/> Standardvärdet är Ingen (XAdES är avstängt).|



###  Se även
* modul [`aspose.cells.digitalsignatures`](..)
