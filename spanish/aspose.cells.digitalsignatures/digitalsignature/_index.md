---
title: DigitalSignature clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 10
url: /es/aspose.cells.digitalsignatures/digitalsignature/
is_root: false
---
##  DigitalSignature clase
Firma en archivo.



El tipo DigitalSignature expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self, certificate, comments, sign_time)`](/cells/python-net/es/aspose.cells.digitalsignatures/digitalsignature/__init__/#system.security.cryptography.x509certificates.x509certificate2-str-datetime) | Constructor de firma digital. Implementado en .NET.|
| [`__init__(self, raw_data, password, comments, sign_time)`](/cells/python-net/es/aspose.cells.digitalsignatures/digitalsignature/__init__/#bytes-str-str-datetime) |Constructor de firma digital. Utiliza la implementación de Bouncy Castle.|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [certificate](/cells/python-net/es/aspose.cells.digitalsignatures/digitalsignature/certificate) | Objeto de certificado que se utilizó para firmar el documento.|
| [comments](/cells/python-net/es/aspose.cells.digitalsignatures/digitalsignature/comments) | El propósito de la firma.|
| [sign_time](/cells/python-net/es/aspose.cells.digitalsignatures/digitalsignature/sign_time) | El momento en que se firmó el documento.|
| [id](/cells/python-net/es/aspose.cells.digitalsignatures/digitalsignature/id) | Especifica un GUID que puede compararse con el GUID de la línea de firma almacenada en el contenido del documento.<br/> El valor predeterminado es Vacío (todos ceros) Guid.|
| [text](/cells/python-net/es/aspose.cells.digitalsignatures/digitalsignature/text) | Especifica el texto de la firma real en la firma digital.<br/> El valor predeterminado es vacío.|
| [image](/cells/python-net/es/aspose.cells.digitalsignatures/digitalsignature/image) | Especifica una imagen para la firma digital.<br/> El valor predeterminado es nulo.|
| [provider_id](/cells/python-net/es/aspose.cells.digitalsignatures/digitalsignature/provider_id) | Especifica el ID de clase del proveedor de firma.<br/> El valor predeterminado es Vacío (todos ceros) Guid.|
| [is_valid](/cells/python-net/es/aspose.cells.digitalsignatures/digitalsignature/is_valid) | Si esta firma digital es válida y el documento no ha sido alterado,<br/> Este valor será verdadero.|
| [x_ad_es_type](/cells/python-net/es/aspose.cells.digitalsignatures/digitalsignature/x_ad_es_type) | Tipo XAdES.<br/> El valor predeterminado es Ninguno (XAdES está desactivado).|



###  Ver también
* módulo [`aspose.cells.digitalsignatures`](..)
