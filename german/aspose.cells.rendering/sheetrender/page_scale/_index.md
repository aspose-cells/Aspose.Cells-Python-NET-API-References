---
title: page_scale Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 90
url: /de/aspose.cells.rendering/sheetrender/page_scale/
is_root: false
---
##  page_scale Eigentum

Ruft den berechneten Seitenmaßstab des Blatts ab.
Gibt die eingestellte Skala zurück, wenn [PageSetup.zoom](/cells/python-net/de/aspose.cells/pagesetup#zoom) eingestellt ist. Gibt andernfalls die berechnete Skala gemäß [PageSetup.fit_to_pages_wide](/cells/python-net/de/aspose.cells/pagesetup#fit_to_pages_wide) und [PageSetup.fit_to_pages_tall](/cells/python-net/de/aspose.cells/pagesetup#fit_to_pages_tall) zurück.

###  Beispiel

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

###  Siehe auch
* Modul [aspose.cells.rendering](../../)
* Klasse [SheetRender](/cells/python-net/de/aspose.cells.rendering/sheetrender)
