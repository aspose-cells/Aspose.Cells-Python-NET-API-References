---
title: page_scale propiedad
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 100
url: /es/aspose.cells.rendering/sheetrender/page_scale/
is_root: false
---
##  page_scale propiedad

Obtiene la escala de página calculada de la hoja.
Devuelve la escala establecida si se establece [`PageSetup.zoom`](/cells/python-net/es/aspose.cells/pagesetup#zoom). En caso contrario, devuelve la escala calculada según [`PageSetup.fit_to_pages_wide`](/cells/python-net/es/aspose.cells/pagesetup#fit_to_pages_wide) y [`PageSetup.fit_to_pages_tall`](/cells/python-net/es/aspose.cells/pagesetup#fit_to_pages_tall).

###  Ejemplo

```python
from aspose.cells import Workbook
from aspose.cells.rendering import ImageOrPrintOptions, SheetRender

wb = Workbook("Book1.xlsx")
sheetRender = SheetRender(wb.worksheets[0], ImageOrPrintOptions())
# Gets calculated page scale of the sheet.
pageScale = sheetRender.page_scale

```
###  Definición:
```python
@property
def page_scale(self):
    ...
```

###  Ver también
* módulo [`aspose.cells.rendering`](../../)
* clase [`SheetRender`](/cells/python-net/es/aspose.cells.rendering/sheetrender)
