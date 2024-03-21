---
title: page_index عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 200
url: /ar/aspose.cells/paginatedsaveoptions/page_index/
is_root: false
---
##  page_index عقار

الحصول على أو تعيين الفهرس المستند إلى 0 للصفحة الأولى المراد حفظها.

###  ملاحظات

الافتراضي هو 0.

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
def page_index(self):
    ...
@page_index.setter
def page_index(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`PaginatedSaveOptions`](/cells/python-net/ar/aspose.cells/paginatedsaveoptions)
