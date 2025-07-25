---
title: page_scale fastighet
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 100
url: /sv/aspose.cells.rendering/sheetrender/page_scale/
is_root: false
---
##  page_scale fastighet

Hämtar beräknad sidskala för arket.
Returnerar den inställda skalan om [`PageSetup.zoom`](/cells/python-net/sv/aspose.cells/pagesetup#zoom) är satt. Annars returneras den beräknade skalan enligt [`PageSetup.fit_to_pages_wide`](/cells/python-net/sv/aspose.cells/pagesetup#fit_to_pages_wide) och [`PageSetup.fit_to_pages_tall`](/cells/python-net/sv/aspose.cells/pagesetup#fit_to_pages_tall).

###  Exempel

```python
from aspose.cells import Workbook
from aspose.cells.rendering import ImageOrPrintOptions, SheetRender

wb = Workbook("Book1.xlsx")
sheetRender = SheetRender(wb.worksheets[0], ImageOrPrintOptions())
# Gets calculated page scale of the sheet.
pageScale = sheetRender.page_scale

```
###  Definition:
```python
@property
def page_scale(self):
    ...
```

###  Se även
* modul [`aspose.cells.rendering`](../../)
* klass [`SheetRender`](/cells/python-net/sv/aspose.cells.rendering/sheetrender)
