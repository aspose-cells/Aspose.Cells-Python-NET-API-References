---
title: page_scale الملكية
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 90
url: /ar/aspose.cells.rendering/sheetrender/page_scale/
is_root: false
---
##  page_scale الملكية

يحصل على مقياس الصفحة المحسوب للورقة.
إرجاع المقياس المحدد إذا تم تعيين [PageSetup.zoom](/cells/python-net/ar/aspose.cells/pagesetup#zoom). وإلا ، تُرجع المقياس المحسوب وفقًا لـ [PageSetup.fit_to_pages_wide](/cells/python-net/ar/aspose.cells/pagesetup#fit_to_pages_wide) و [PageSetup.fit_to_pages_tall](/cells/python-net/ar/aspose.cells/pagesetup#fit_to_pages_tall).

###  مثال

```python
from aspose.cells import Workbook
from aspose.cells.rendering import ImageOrPrintOptions, SheetRender

wb = Workbook("Book1.xlsx")
sheetRender = SheetRender(wb.worksheets[0], ImageOrPrintOptions())
# Gets calculated page scale of the sheet.
pageScale = sheetRender.page_scale

```
###  تعريف:
```python
@property
def page_scale(self):
    ...
```

###  أنظر أيضا
* وحدة [aspose.cells.rendering](../../)
* فئة [SheetRender](/cells/python-net/ar/aspose.cells.rendering/sheetrender)
