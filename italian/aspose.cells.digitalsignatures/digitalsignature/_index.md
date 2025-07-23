---
title: DigitalSignature classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 10
url: /it/aspose.cells.digitalsignatures/digitalsignature/
is_root: false
---
##  DigitalSignature classe
Firma nel file.



Il tipo DigitalSignature espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self, certificate, comments, sign_time)`](/cells/python-net/it/aspose.cells.digitalsignatures/digitalsignature/__init__/#system.security.cryptography.x509certificates.x509certificate2-str-datetime) | Costruttore di digitalSignature. Utilizza l'implementazione .Net.|
| [`__init__(self, raw_data, password, comments, sign_time)`](/cells/python-net/it/aspose.cells.digitalsignatures/digitalsignature/__init__/#bytes-str-str-datetime) |Costruttore di digitalSignature. Utilizza l'implementazione Bouncy Castle.|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [certificate](/cells/python-net/it/aspose.cells.digitalsignatures/digitalsignature/certificate) | Oggetto certificato utilizzato per firmare il documento.|
| [comments](/cells/python-net/it/aspose.cells.digitalsignatures/digitalsignature/comments) | Lo scopo della firma.|
| [sign_time](/cells/python-net/it/aspose.cells.digitalsignatures/digitalsignature/sign_time) | Ora in cui il documento è stato firmato.|
| [id](/cells/python-net/it/aspose.cells.digitalsignatures/digitalsignature/id) | Specifica un GUID che può essere confrontato con il GUID della riga della firma memorizzata nel contenuto del documento.<br/> Il valore predefinito è Vuoto (tutti zeri) Guid.|
| [text](/cells/python-net/it/aspose.cells.digitalsignatures/digitalsignature/text) | Specifica il testo della firma effettiva nella firma digitale.<br/> Il valore predefinito è Vuoto.|
| [image](/cells/python-net/it/aspose.cells.digitalsignatures/digitalsignature/image) | Specifica un'immagine per la firma digitale.<br/> Il valore predefinito è null.|
| [provider_id](/cells/python-net/it/aspose.cells.digitalsignatures/digitalsignature/provider_id) | Specifica l'ID di classe del fornitore della firma.<br/> Il valore predefinito è Vuoto (tutti zeri) Guid.|
| [is_valid](/cells/python-net/it/aspose.cells.digitalsignatures/digitalsignature/is_valid) | Se questa firma digitale è valida e il documento non è stato manomesso,<br/> questo valore sarà vero.|
| [x_ad_es_type](/cells/python-net/it/aspose.cells.digitalsignatures/digitalsignature/x_ad_es_type) | Tipo XAdES.<br/> Il valore predefinito è Nessuno (XAdES è disattivato).|



###  Guarda anche
* modulo [`aspose.cells.digitalsignatures`](..)
