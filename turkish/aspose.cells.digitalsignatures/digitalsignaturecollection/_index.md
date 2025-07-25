---
title: DigitalSignatureCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells.digitalsignatures/digitalsignaturecollection/
is_root: false
---
##  DigitalSignatureCollection sınıfı
Bir belgeye ekli dijital imzaların bir koleksiyonunu sağlar.



DigitalSignatureCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells.digitalsignatures/digitalsignaturecollection/__init__/#) | DigitalSignatureCollection'ın kurucusu.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`add(self, digital_signature)`](/cells/python-net/tr/aspose.cells.digitalsignatures/digitalsignaturecollection/add/#aspose.cells.digitalsignatures.digitalsignature) | DigitalSignatureCollection'a bir imza ekleyin.|



###  Örnek

Aşağıdaki örnek dijital imzanın nasıl doğrulanacağını göstermektedir.

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

###  Ayrıca bakınız
* modül [`aspose.cells.digitalsignatures`](..)
