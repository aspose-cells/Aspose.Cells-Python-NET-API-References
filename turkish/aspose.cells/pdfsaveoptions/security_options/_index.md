---
title: security_options mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 440
url: /tr/aspose.cells/pdfsaveoptions/security_options/
is_root: false
---
##  security_options mülk

Xls2pdf sonucunda güvenliğe ihtiyaç duyulduğunda bu seçeneği ayarlayın.

###  Örnek

Aşağıdaki kod çıktı pdf'i için yüksek çözünürlüklü yazdırma iznini ayarlar.

```python
from aspose.cells import PdfSaveOptions, Workbook
from aspose.cells.rendering.pdfsecurity import PdfSecurityOptions

wb = Workbook()
wb.worksheets[0].cells.get("A1").value = "Aspose"
pdfSaveOptions = PdfSaveOptions()
pdfSecurityOptions = PdfSecurityOptions()
# set owner password
pdfSecurityOptions.owner_password = "YourOwnerPassword"
# set user password
pdfSecurityOptions.user_password = "YourUserPassword"
# set print permisson
pdfSecurityOptions.print_permission = True
# set high resolution for print
pdfSecurityOptions.full_quality_print_permission = True
pdfSaveOptions.security_options = pdfSecurityOptions
wb.save("output.pdf", pdfSaveOptions)

```
###  Tanım:
```python
@property
def security_options(self):
    ...
@security_options.setter
def security_options(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`PdfSaveOptions`](/cells/python-net/tr/aspose.cells/pdfsaveoptions)
* sınıf [`PdfSecurityOptions`](/cells/python-net/tr/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions)
