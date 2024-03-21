---
title: printing_page_type عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 250
url: /ar/aspose.cells/pptxsaveoptions/printing_page_type/
is_root: false
---
##  printing_page_type عقار

يشير إلى الصفحات التي لن تتم طباعتها.

###  ملاحظات

إذا كان المحتوى الموجود في الورقة متناثرًا، فستكون هناك بعض الصفحات فارغة تمامًا في ملف PDF الناتج.
إذا كنت لا تريد هذه الصفحات الفارغة، فيمكنك استخدام هذا الخيار لحذفها.

###  مثال

يحذف التعليمة البرمجية التالية الصفحات الفارغة أو الصفحات التي تحتوي فقط على بعض محتوى النمط مثل خلفية الخلية والحدود.

```python
from aspose.cells import PdfSaveOptions, PrintingPageType, Workbook

wb = Workbook("Book1.xlsx")
pdfSaveOptions = PdfSaveOptions()
# ignore blank pages
pdfSaveOptions.printing_page_type = PrintingPageType.IGNORE_BLANK
wb.save("output_ignore_blank_page.pdf", pdfSaveOptions)
# ignore blank pages and pages which only contains some style content like cell background
pdfSaveOptions.printing_page_type = PrintingPageType.IGNORE_STYLE
wb.save("output_ignore_blank_and_style_page.pdf", pdfSaveOptions)

```
###  تعريف:
```python
@property
def printing_page_type(self):
    ...
@printing_page_type.setter
def printing_page_type(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`PptxSaveOptions`](/cells/python-net/ar/aspose.cells/pptxsaveoptions)
* فئة [`PrintingPageType`](/cells/python-net/ar/aspose.cells/printingpagetype)
