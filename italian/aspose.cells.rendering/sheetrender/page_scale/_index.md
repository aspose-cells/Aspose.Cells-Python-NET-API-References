---
title: page_scale proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 100
url: /it/aspose.cells.rendering/sheetrender/page_scale/
is_root: false
---
##  page_scale proprietà

Ottiene la scala di pagina calcolata del foglio.
Restituisce la scala impostata se è impostato [`PageSetup.zoom`](/cells/python-net/it/aspose.cells/pagesetup#zoom). In caso contrario, restituisce la scala calcolata in base a [`PageSetup.fit_to_pages_wide`](/cells/python-net/it/aspose.cells/pagesetup#fit_to_pages_wide) e [`PageSetup.fit_to_pages_tall`](/cells/python-net/it/aspose.cells/pagesetup#fit_to_pages_tall).

###  Esempio

```python
from aspose.cells import Workbook
from aspose.cells.rendering import ImageOrPrintOptions, SheetRender

wb = Workbook("Book1.xlsx")
sheetRender = SheetRender(wb.worksheets[0], ImageOrPrintOptions())
# Gets calculated page scale of the sheet.
pageScale = sheetRender.page_scale

```
###  Definizione:
```python
@property
def page_scale(self):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.rendering`](../../)
* classe [`SheetRender`](/cells/python-net/it/aspose.cells.rendering/sheetrender)
