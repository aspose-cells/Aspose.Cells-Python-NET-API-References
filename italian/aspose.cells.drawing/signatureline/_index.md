---
title: SignatureLine classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 610
url: /it/aspose.cells.drawing/signatureline/
is_root: false
---
##  SignatureLine classe
Rappresenta la riga della firma.



Il tipo SignatureLine espone i seguenti membri:

###  Costruttori
| Costruttore| Descrizione|
| :- | :- |
| [`__init__(self)`](/cells/python-net/it/aspose.cells.drawing/signatureline/__init__/#) | Costruisce una nuova istanza di SignatureLine|


###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [id](/cells/python-net/it/aspose.cells.drawing/signatureline/id) | Ottiene o imposta l'identificatore per questa riga della firma.|
| [provider_id](/cells/python-net/it/aspose.cells.drawing/signatureline/provider_id) | Ottiene o imposta l'ID del fornitore della firma.|
| [signer](/cells/python-net/it/aspose.cells.drawing/signatureline/signer) | Ottiene o imposta il firmatario.|
| [title](/cells/python-net/it/aspose.cells.drawing/signatureline/title) | Ottiene o imposta il titolo del cantante.|
| [email](/cells/python-net/it/aspose.cells.drawing/signatureline/email) | Ottiene o imposta l'email del cantante.|
| [is_line](/cells/python-net/it/aspose.cells.drawing/signatureline/is_line) | Indica se si tratta di una riga di firma.|
| [allow_comments](/cells/python-net/it/aspose.cells.drawing/signatureline/allow_comments) | Indica se è possibile allegare commenti.|
| [show_signed_date](/cells/python-net/it/aspose.cells.drawing/signatureline/show_signed_date) | Indica se mostrare la data della firma.|
| [instructions](/cells/python-net/it/aspose.cells.drawing/signatureline/instructions) | Ottiene o imposta il testo mostrato all'utente al momento della firma.|
| [signature_line_type](/cells/python-net/it/aspose.cells.drawing/signatureline/signature_line_type) | Ottiene o imposta il tipo di firma.<br/>Predefinito: quando viene impostato il valore predefinito, il valore ProviderId corrispondente è fissato su {0000000000-0000-0000-0000-0000000000}.<br/>Timbro - Quando il valore è Timbro, il valore ProviderId corrispondente è solitamente {000CD6A4-0000-0000-C000-000000000046}.<br/> Personalizzato: quando il valore è Personalizzato, in genere il valore ProviderId corrispondente deve essere impostato dall'utente. Dovrebbe essere reperito nella documentazione fornita con il provider.|



###  Esempio

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

###  Guarda anche
* modulo [`aspose.cells.drawing`](..)
