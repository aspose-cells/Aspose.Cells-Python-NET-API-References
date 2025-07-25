---
title: DigitalSignatureCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells.digitalsignatures/digitalsignaturecollection/
is_root: false
---
##  DigitalSignatureCollection classe
Fournit une collection de signatures numériques attachées à un document.



Le type DigitalSignatureCollection expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self)`](/cells/python-net/fr/aspose.cells.digitalsignatures/digitalsignaturecollection/__init__/#) | Le constructeur de DigitalSignatureCollection.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`add(self, digital_signature)`](/cells/python-net/fr/aspose.cells.digitalsignatures/digitalsignaturecollection/add/#aspose.cells.digitalsignatures.digitalsignature) | Ajoutez une signature à DigitalSignatureCollection.|



###  Exemple

L'exemple suivant montre comment valider une signature numérique.

```python
from aspose.cells import Workbook

# workbook from a signed source file
signedWorkbook = Workbook(r"signedFile.xlsx")
# wb.IsDigitallySigned is true when the workbook is signed already.
print(signedWorkbook.is_digitally_signed)
# get digitalSignature collection from workbook
existingDsc = signedWorkbook.get_digital_signature()
for existingDs in existingDsc:
    print(existingDs.comments)
    print(existingDs.sign_time)
    print(existingDs.is_valid)

```

###  Voir également
* module [`aspose.cells.digitalsignatures`](..)
