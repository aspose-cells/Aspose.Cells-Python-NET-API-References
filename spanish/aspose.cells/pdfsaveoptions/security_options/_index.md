---
title: security_options propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 390
url: /es/aspose.cells/pdfsaveoptions/security_options/
is_root: false
---
##  security_options propiedad

Establezca estas opciones, cuando se necesite seguridad en el resultado xls2pdf.

###  Ejemplo

El siguiente código establece el permiso de impresión de alta resolución para el pdf de salida.

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
###  Definición:
```python
@property
def security_options(self):
    ...
@security_options.setter
def security_options(self, value):
    ...
```

###  Ver también
* módulo [aspose.cells](../../)
* clase [PdfSaveOptions](/cells/python-net/es/aspose.cells/pdfsaveoptions)
* clase [PdfSecurityOptions](/cells/python-net/es/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions)
