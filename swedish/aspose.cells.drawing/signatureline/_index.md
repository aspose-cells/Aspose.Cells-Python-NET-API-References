---
title: SignatureLine klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 610
url: /sv/aspose.cells.drawing/signatureline/
is_root: false
---
##  SignatureLine klass
Representera signaturraden.



Typen SignatureLine avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self)`](/cells/python-net/sv/aspose.cells.drawing/signatureline/__init__/#) | Konstruerar en ny instans av SignatureLine|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [id](/cells/python-net/sv/aspose.cells.drawing/signatureline/id) | Hämtar eller ställer in identifierare för denna signaturrad.|
| [provider_id](/cells/python-net/sv/aspose.cells.drawing/signatureline/provider_id) | Hämtar eller anger ID:t för signaturleverantören.|
| [signer](/cells/python-net/sv/aspose.cells.drawing/signatureline/signer) | Hämtar eller anger signeraren.|
| [title](/cells/python-net/sv/aspose.cells.drawing/signatureline/title) | Hämtar eller fastställer titeln sångare.|
| [email](/cells/python-net/sv/aspose.cells.drawing/signatureline/email) | Hämtar eller ställer in sångarens e-postadress.|
| [is_line](/cells/python-net/sv/aspose.cells.drawing/signatureline/is_line) | Anger om det är en signaturrad.|
| [allow_comments](/cells/python-net/sv/aspose.cells.drawing/signatureline/allow_comments) | Anger om kommentarer kan bifogas.|
| [show_signed_date](/cells/python-net/sv/aspose.cells.drawing/signatureline/show_signed_date) | Anger om signeringsdatum visas.|
| [instructions](/cells/python-net/sv/aspose.cells.drawing/signatureline/instructions) | Hämtar eller ställer in texten som visas för användaren vid signeringstillfället.|
| [signature_line_type](/cells/python-net/sv/aspose.cells.drawing/signatureline/signature_line_type) | Hämtar eller anger signaturtypen.<br/>Standard – När standardvärdet är inställt är motsvarande ProviderId-värde fastställt till {0000000000-0000-0000-0000-000000000}.<br/>Stämpel – När värdet är Stämpel är motsvarande ProviderId-värde vanligtvis {000CD6A4-0000-0000-C000-000000000046}.<br/> Anpassad – När värdet är Anpassad måste motsvarande ProviderId-värde vanligtvis anges av användaren. Det bör hämtas från dokumentationen som medföljer leverantören.|



###  Exempel

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

###  Se även
* modul [`aspose.cells.drawing`](..)
