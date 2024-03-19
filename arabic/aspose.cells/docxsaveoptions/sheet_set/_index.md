---
title: sheet_set عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 250
url: /ar/aspose.cells/docxsaveoptions/sheet_set/
is_root: false
---
##  sheet_set عقار

الحصول على الأوراق المراد عرضها أو تعيينها. الافتراضي هو كافة الأوراق المرئية في المصنف: [`SheetSet.visible`](/cells/python-net/ar/aspose.cells.rendering/sheetset#visible).

###  مثال

يعرض التعليمة البرمجية التالية الورقة النشطة فقط إلى pdf.

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
###  تعريف:
```python
@property
def sheet_set(self):
    ...
@sheet_set.setter
def sheet_set(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`DocxSaveOptions`](/cells/python-net/ar/aspose.cells/docxsaveoptions)
* فئة [`SheetSet`](/cells/python-net/ar/aspose.cells.rendering/sheetset)
