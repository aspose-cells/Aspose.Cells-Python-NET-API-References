---
title: DigitalSignatureCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells.digitalsignatures/digitalsignaturecollection/
is_root: false
---
##  DigitalSignatureCollection klass
Tillhandahåller en samling digitala signaturer som är bifogade till ett dokument.



Typen DigitalSignatureCollection avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self)`](/cells/python-net/sv/aspose.cells.digitalsignatures/digitalsignaturecollection/__init__/#) | Konstruktören av DigitalSignatureCollection.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`add(self, digital_signature)`](/cells/python-net/sv/aspose.cells.digitalsignatures/digitalsignaturecollection/add/#aspose.cells.digitalsignatures.digitalsignature) | Lägg till en signatur i DigitalSignatureCollection.|



###  Exempel

Följande exempel visar hur man validerar en digital signatur.

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

###  Se även
* modul [`aspose.cells.digitalsignatures`](..)
