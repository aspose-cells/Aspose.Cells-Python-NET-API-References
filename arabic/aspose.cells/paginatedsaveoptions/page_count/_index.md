---
title: page_count عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 190
url: /ar/aspose.cells/paginatedsaveoptions/page_count/
is_root: false
---
##  page_count عقار

الحصول على أو تعيين عدد الصفحات المراد حفظها.

###  ملاحظات

الافتراضي هو System.Int32.MaxValue مما يعني أنه سيتم عرض جميع الصفحات.

###  مثال

يوضح المثال التالي كيفية عرض نطاق من الصفحات (3 و4) في ملف Excel Microsoft إلى PDF.

```python
from aspose.cells import PdfSaveOptions, Workbook

# Open an Excel file
wb = Workbook("Book1.xlsx")
options = PdfSaveOptions()
# Print only Page 3 and Page 4 in the output PDF
# Starting page index (0-based index)
options.page_index = 3
# Number of pages to be printed
options.page_count = 2
# Save the PDF file
wb.save("output.pdf", options)

```
###  تعريف:
```python
@property
def page_count(self):
    ...
@page_count.setter
def page_count(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`PaginatedSaveOptions`](/cells/python-net/ar/aspose.cells/paginatedsaveoptions)
