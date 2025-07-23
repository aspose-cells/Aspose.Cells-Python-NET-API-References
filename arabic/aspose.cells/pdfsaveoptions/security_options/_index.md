---
title: security_options عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 440
url: /ar/aspose.cells/pdfsaveoptions/security_options/
is_root: false
---
##  security_options عقار

قم بتعيين هذه الخيارات، عندما تكون هناك حاجة للأمان في نتيجة xls2pdf.

###  مثال

يقوم الكود التالي بتعيين أذونات الطباعة عالية الدقة لملف pdf الناتج.

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
###  تعريف:
```python
@property
def security_options(self):
    ...
@security_options.setter
def security_options(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`PdfSaveOptions`](/cells/python-net/ar/aspose.cells/pdfsaveoptions)
* فئة [`PdfSecurityOptions`](/cells/python-net/ar/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions)
