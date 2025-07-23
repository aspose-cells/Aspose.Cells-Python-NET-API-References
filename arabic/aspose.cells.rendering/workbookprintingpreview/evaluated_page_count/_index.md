---
title: evaluated_page_count عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 30
url: /ar/aspose.cells.rendering/workbookprintingpreview/evaluated_page_count/
is_root: false
---
##  evaluated_page_count عقار

تقييم إجمالي عدد الصفحات في هذا المصنف

###  مثال

يُظهر الكود التالي أسرع طريقة للحصول على عدد الصفحات في مصنف.

```python
from aspose.cells import Workbook
from aspose.cells.rendering import ImageOrPrintOptions, WorkbookPrintingPreview

workbook = Workbook("Book1.xlsx")
workbookPrintingPreview = WorkbookPrintingPreview(workbook, ImageOrPrintOptions())
# fastest way to get page count especailly when there are massive data in workbook.
print(workbookPrintingPreview.evaluated_page_count)

```
###  تعريف:
```python
@property
def evaluated_page_count(self):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells.rendering`](../../)
* فئة [`WorkbookPrintingPreview`](/cells/python-net/ar/aspose.cells.rendering/workbookprintingpreview)
