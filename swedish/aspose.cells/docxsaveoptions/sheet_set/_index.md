---
title: sheet_set fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 250
url: /sv/aspose.cells/docxsaveoptions/sheet_set/
is_root: false
---
##  sheet_set fastighet

Hämtar eller ställer in arken att rendera. Standard är alla synliga ark i arbetsboken: [`SheetSet.visible`](/cells/python-net/sv/aspose.cells.rendering/sheetset#visible).

###  Exempel

Följande kod återger endast aktivt ark till pdf.

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
###  Definition:
```python
@property
def sheet_set(self):
    ...
@sheet_set.setter
def sheet_set(self, value):
    ...
```

###  Se även
* modul [`aspose.cells`](../../)
* klass [`DocxSaveOptions`](/cells/python-net/sv/aspose.cells/docxsaveoptions)
* klass [`SheetSet`](/cells/python-net/sv/aspose.cells.rendering/sheetset)
