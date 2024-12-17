﻿---
title: sheet_set property
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 270
url: /aspose.cells/docxsaveoptions/sheet_set/
is_root: false
---

## sheet_set property


Gets or sets the sheets to render. Default is all visible sheets in the workbook: [`SheetSet.visible`](/cells/python-net/aspose.cells.rendering/sheetset#visible).

### Example 


The following code only renders active sheet to pdf.

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
### Definition:
```python
@property
def sheet_set(self):
    ...
@sheet_set.setter
def sheet_set(self, value):
    ...
```

### See Also
* module [`aspose.cells`](../../)
* class [`DocxSaveOptions`](/cells/python-net/aspose.cells/docxsaveoptions)
* class [`SheetSet`](/cells/python-net/aspose.cells.rendering/sheetset)
