---
title: SignatureLine clase
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 610
url: /es/aspose.cells.drawing/signatureline/
is_root: false
---
##  SignatureLine clase
Representa la línea de firma.



El tipo SignatureLine expone los siguientes miembros:

###  Constructores
| Constructor| Descripción|
| :- | :- |
| [`__init__(self)`](/cells/python-net/es/aspose.cells.drawing/signatureline/__init__/#) | Construye una nueva instancia de SignatureLine|


###  Propiedades
| Propiedad| Descripción|
| :- | :- |
| [id](/cells/python-net/es/aspose.cells.drawing/signatureline/id) | Obtiene o establece el identificador para esta línea de firma.|
| [provider_id](/cells/python-net/es/aspose.cells.drawing/signatureline/provider_id) | Obtiene o establece el identificador del proveedor de firma.|
| [signer](/cells/python-net/es/aspose.cells.drawing/signatureline/signer) | Obtiene o establece el firmante.|
| [title](/cells/python-net/es/aspose.cells.drawing/signatureline/title) | Obtiene o establece el título del cantante.|
| [email](/cells/python-net/es/aspose.cells.drawing/signatureline/email) | Obtiene o establece el correo electrónico del cantante.|
| [is_line](/cells/python-net/es/aspose.cells.drawing/signatureline/is_line) | Indica si es una línea de firma.|
| [allow_comments](/cells/python-net/es/aspose.cells.drawing/signatureline/allow_comments) | Indica si se pueden adjuntar comentarios.|
| [show_signed_date](/cells/python-net/es/aspose.cells.drawing/signatureline/show_signed_date) | Indica si se muestra la fecha de firma.|
| [instructions](/cells/python-net/es/aspose.cells.drawing/signatureline/instructions) | Obtiene o establece el texto que se muestra al usuario en el momento de firmar.|
| [signature_line_type](/cells/python-net/es/aspose.cells.drawing/signatureline/signature_line_type) | Obtiene o establece el tipo de firma.<br/>Predeterminado: cuando se establece el valor predeterminado, el valor de ProviderId correspondiente se fija en {0000000000-0000-0000-0000-0000000000}.<br/>Sello: cuando el valor es Sello, el valor de ProviderId correspondiente suele ser {000CD6A4-0000-0000-C000-000000000046}.<br/> Personalizado: cuando el valor es Personalizado, el valor ProviderId correspondiente generalmente debe ser establecido por el usuario. Debe obtenerse de la documentación enviada con el proveedor.|



###  Ejemplo

```python
from aspose.cells import Workbook
from aspose.cells.drawing import SignatureLine

# Instantiating a Workbook object
workbook = Workbook()
worksheet = workbook.worksheets[0]
#  Create signature line object
s = SignatureLine()
s.signer = "Simon"
s.title = "Development"
s.email = "simon@aspose.com"
s.instructions = "Sign to confirm the excel content."
#  Adds a Signature Line to the worksheet.
signatureLine = worksheet.shapes.add_signature_line(0, 0, s)
# do your business
# Save the excel file.
workbook.save("result.xlsx")

```

###  Ver también
* módulo [`aspose.cells.drawing`](..)
