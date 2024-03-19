---
title: page_scale mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 100
url: /tr/aspose.cells.rendering/sheetrender/page_scale/
is_root: false
---
##  page_scale mülk

Sayfanın hesaplanan sayfa ölçeğini alır.
[`PageSetup.zoom`](/cells/python-net/tr/aspose.cells/pagesetup#zoom) ayarlanmışsa ayarlanan ölçeği döndürür. Aksi halde [`PageSetup.fit_to_pages_wide`](/cells/python-net/tr/aspose.cells/pagesetup#fit_to_pages_wide) ve [`PageSetup.fit_to_pages_tall`](/cells/python-net/tr/aspose.cells/pagesetup#fit_to_pages_tall)'e göre hesaplanan ölçeği döndürür.

###  Örnek

```python
from aspose.cells import Workbook
from aspose.cells.rendering import ImageOrPrintOptions, SheetRender

wb = Workbook("Book1.xlsx")
sheetRender = SheetRender(wb.worksheets[0], ImageOrPrintOptions())
# Gets calculated page scale of the sheet.
pageScale = sheetRender.page_scale

```
###  Tanım:
```python
@property
def page_scale(self):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells.rendering`](../../)
* sınıf [`SheetRender`](/cells/python-net/tr/aspose.cells.rendering/sheetrender)
