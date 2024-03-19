---
title: page_scale عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 100
url: /ar/aspose.cells.rendering/sheetrender/page_scale/
is_root: false
---
##  page_scale عقار

يحصل على مقياس الصفحة المحسوب للورقة.
يُرجع المقياس المحدد إذا تم ضبط [`PageSetup.zoom`](/cells/python-net/ar/aspose.cells/pagesetup#zoom). وبخلاف ذلك، يتم إرجاع المقياس المحسوب وفقًا لـ [`PageSetup.fit_to_pages_wide`](/cells/python-net/ar/aspose.cells/pagesetup#fit_to_pages_wide) و[`PageSetup.fit_to_pages_tall`](/cells/python-net/ar/aspose.cells/pagesetup#fit_to_pages_tall).

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
* الوحدة [`aspose.cells.rendering`](../../)
* فئة [`SheetRender`](/cells/python-net/ar/aspose.cells.rendering/sheetrender)
