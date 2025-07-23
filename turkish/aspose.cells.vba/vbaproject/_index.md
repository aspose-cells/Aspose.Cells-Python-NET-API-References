---
title: VbaProject sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 30
url: /tr/aspose.cells.vba/vbaproject/
is_root: false
---
##  VbaProject sınıfı
VBA projesini temsil eder.



VbaProject türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [is_valid_signed](/cells/python-net/tr/aspose.cells.vba/vbaproject/is_valid_signed) | VBA projesinin imzasının geçerli olup olmadığını belirtir.|
| [cert_raw_data](/cells/python-net/tr/aspose.cells.vba/vbaproject/cert_raw_data) | Bu VBA projesi imzalanmışsa sertifika ham verilerini alır.|
| [encoding](/cells/python-net/tr/aspose.cells.vba/vbaproject/encoding) |VBA projesinin kodlamasını alır ve ayarlar.|
| [name](/cells/python-net/tr/aspose.cells.vba/vbaproject/name) | VBA projesinin adını alır ve ayarlar.|
| [is_signed](/cells/python-net/tr/aspose.cells.vba/vbaproject/is_signed) | VBAcode'un imzalı olup olmadığını belirtir.|
| [is_protected](/cells/python-net/tr/aspose.cells.vba/vbaproject/is_protected) | Bu VBA projesinin korunup korunmadığını gösterir.|
| [islocked_for_viewing](/cells/python-net/tr/aspose.cells.vba/vbaproject/islocked_for_viewing) | Bu VBA projesinin görüntülenmeye kilitli olup olmadığını belirtir.|
| [modules](/cells/python-net/tr/aspose.cells.vba/vbaproject/modules) | [`VbaModule`](/cells/python-net/tr/aspose.cells.vba/vbamodule) nesnesinin tamamını alır.|
| [references](/cells/python-net/tr/aspose.cells.vba/vbaproject/references) | VBA projesinin tüm referanslarını alır.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`sign(self, digital_signature)`](/cells/python-net/tr/aspose.cells.vba/vbaproject/sign/#aspose.cells.digitalsignatures.digitalsignature) | Bu VBA projesini DigitalSignature ile imzalayın|
| [`protect(self, islocked_for_viewing, password)`](/cells/python-net/tr/aspose.cells.vba/vbaproject/protect/#bool-str) | Bu VBA projesini korur veya korumasını kaldırır.|
| [`copy(self, source)`](/cells/python-net/tr/aspose.cells.vba/vbaproject/copy/#aspose.cells.vba.vbaproject) | VBA projesini diğer dosyadan kopyala.|
| [`validate_password(self, password)`](/cells/python-net/tr/aspose.cells.vba/vbaproject/validate_password/#str) | Koruma şifresini doğrular.|



###  Örnek

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  Ayrıca bakınız
* modül [`aspose.cells.vba`](..)
* sınıf [`VbaModule`](/cells/python-net/tr/aspose.cells.vba/vbamodule)
