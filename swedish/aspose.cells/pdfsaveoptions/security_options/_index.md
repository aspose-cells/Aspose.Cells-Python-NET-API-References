---
title: security_options fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 440
url: /sv/aspose.cells/pdfsaveoptions/security_options/
is_root: false
---
##  security_options fastighet

Ställ in dessa alternativ när säkerhet behövs i xls2pdf-resultatet.

###  Exempel

Följande kod anger utskriftsbehörighet med hög upplösning för den utgående pdf-filen.

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
###  Definition:
```python
@property
def security_options(self):
    ...
@security_options.setter
def security_options(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`PdfSaveOptions`](/cells/python-net/sv/aspose.cells/pdfsaveoptions)
* klass [`PdfSecurityOptions`](/cells/python-net/sv/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions)
