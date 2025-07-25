---
title: SignatureLine classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 610
url: /fr/aspose.cells.drawing/signatureline/
is_root: false
---
##  SignatureLine classe
Représente la ligne de signature.



Le type SignatureLine expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self)`](/cells/python-net/fr/aspose.cells.drawing/signatureline/__init__/#) | Construit une nouvelle instance de SignatureLine|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [id](/cells/python-net/fr/aspose.cells.drawing/signatureline/id) | Obtient ou définit l'identifiant de cette ligne de signature.|
| [provider_id](/cells/python-net/fr/aspose.cells.drawing/signatureline/provider_id) | Obtient ou définit l'ID du fournisseur de signature.|
| [signer](/cells/python-net/fr/aspose.cells.drawing/signatureline/signer) | Obtient ou définit le signataire.|
| [title](/cells/python-net/fr/aspose.cells.drawing/signatureline/title) | Obtient ou définit le titre du chanteur.|
| [email](/cells/python-net/fr/aspose.cells.drawing/signatureline/email) | Obtient ou définit l'e-mail du chanteur.|
| [is_line](/cells/python-net/fr/aspose.cells.drawing/signatureline/is_line) | Indique s'il s'agit d'une ligne de signature.|
| [allow_comments](/cells/python-net/fr/aspose.cells.drawing/signatureline/allow_comments) | Indique si des commentaires peuvent être joints.|
| [show_signed_date](/cells/python-net/fr/aspose.cells.drawing/signatureline/show_signed_date) | Indique si la date de signature doit être affichée.|
| [instructions](/cells/python-net/fr/aspose.cells.drawing/signatureline/instructions) | Obtient ou définit le texte affiché à l'utilisateur au moment de la signature.|
| [signature_line_type](/cells/python-net/fr/aspose.cells.drawing/signatureline/signature_line_type) | Obtient ou définit le type de signature.<br/>Par défaut - Lorsque la valeur par défaut est définie, la valeur ProviderId correspondante est fixée à {0000000000-0000-0000-0000-0000000000}.<br/>Timbre - Lorsque la valeur est Timbre, la valeur ProviderId correspondante est généralement {000CD6A4-0000-0000-C000-000000000046}.<br/> Personnalisé - Lorsque la valeur est Personnalisé, la valeur ProviderId correspondante doit généralement être définie par l'utilisateur. Elle doit être obtenue à partir de la documentation fournie avec le fournisseur.|



###  Exemple

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

###  Voir également
* module [`aspose.cells.drawing`](..)
