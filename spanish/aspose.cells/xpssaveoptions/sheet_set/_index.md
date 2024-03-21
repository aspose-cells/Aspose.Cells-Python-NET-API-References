---
title: sheet_set propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 250
url: /es/aspose.cells/xpssaveoptions/sheet_set/
is_root: false
---
##  sheet_set propiedad

Obtiene o establece las hojas que se van a representar. El valor predeterminado son todas las hojas visibles del libro: [`SheetSet.visible`](/cells/python-net/es/aspose.cells.rendering/sheetset#visible).

###  Ejemplo

El siguiente código solo representa la hoja activa en pdf.

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
###  Definición:
```python
@property
def sheet_set(self):
    ...
@sheet_set.setter
def sheet_set(self, value):
    ...
```

###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`SheetSet`](/cells/python-net/es/aspose.cells.rendering/sheetset)
* clase [`XpsSaveOptions`](/cells/python-net/es/aspose.cells/xpssaveoptions)
