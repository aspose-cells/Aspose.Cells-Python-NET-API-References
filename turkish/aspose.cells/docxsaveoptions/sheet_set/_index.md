---
title: sheet_set mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 250
url: /tr/aspose.cells/docxsaveoptions/sheet_set/
is_root: false
---
##  sheet_set mülk

Oluşturulacak sayfaları alır veya ayarlar. Varsayılan, çalışma kitabındaki tüm görünür sayfalardır: [`SheetSet.visible`](/cells/python-net/tr/aspose.cells.rendering/sheetset#visible).

###  Örnek

Aşağıdaki kod yalnızca etkin sayfayı pdf'e dönüştürür.

```python
from aspose.cells import PdfSaveOptions, Workbook
from aspose.cells.rendering import SheetSet

workbook = Workbook("Book1.xlsx")
activeSheetIndex = workbook.worksheets.active_sheet_index
pdfSaveOptions = PdfSaveOptions()
# set active sheet index to sheet set.
pdfSaveOptions.sheet_set = SheetSet([activeSheetIndex])
workbook.save("output.pdf", pdfSaveOptions)

```
###  Tanım:
```python
@property
def sheet_set(self):
    ...
@sheet_set.setter
def sheet_set(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`DocxSaveOptions`](/cells/python-net/tr/aspose.cells/docxsaveoptions)
* sınıf [`SheetSet`](/cells/python-net/tr/aspose.cells.rendering/sheetset)
