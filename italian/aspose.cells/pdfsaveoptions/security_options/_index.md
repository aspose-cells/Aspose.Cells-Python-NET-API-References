---
title: security_options proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 440
url: /it/aspose.cells/pdfsaveoptions/security_options/
is_root: false
---
##  security_options proprietà

Impostare questa opzione quando è necessaria la sicurezza nel risultato xls2pdf.

###  Esempio

Il seguente codice imposta i permessi di stampa ad alta risoluzione per il PDF di output.

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
###  Definizione:
```python
@property
def security_options(self):
    ...
@security_options.setter
def security_options(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`PdfSaveOptions`](/cells/python-net/it/aspose.cells/pdfsaveoptions)
* classe [`PdfSecurityOptions`](/cells/python-net/it/aspose.cells.rendering.pdfsecurity/pdfsecurityoptions)
