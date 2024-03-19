---
title: HorizontalPageBreak صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 780
url: /ar/aspose.cells/horizontalpagebreak/
is_root: false
---
##  HorizontalPageBreak صف
يقوم بتغليف الكائن الذي يمثل فاصل الصفحات الأفقي.



يكشف النوع HorizontalPageBreak عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [start_column](/cells/python-net/ar/aspose.cells/horizontalpagebreak/start_column) | الحصول على فهرس عمود البداية لفاصل الصفحات الأفقي هذا.|
| [end_column](/cells/python-net/ar/aspose.cells/horizontalpagebreak/end_column) | الحصول على فهرس عمود النهاية لفاصل الصفحات الأفقي هذا.|
| [row](/cells/python-net/ar/aspose.cells/horizontalpagebreak/row) | يحصل على فهرس الصف القائم على الصفر.|



###  مثال

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Add a page break at cell Y30
Index = worksheet.horizontal_page_breaks.add("Y30")
# get the newly added horizontal page break
hPageBreak = worksheet.horizontal_page_breaks[Index]

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
