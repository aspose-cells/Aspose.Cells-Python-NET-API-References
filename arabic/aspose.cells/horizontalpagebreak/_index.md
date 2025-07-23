---
title: HorizontalPageBreak صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 760
url: /ar/aspose.cells/horizontalpagebreak/
is_root: false
---
##  HorizontalPageBreak صف
يغلف الكائن الذي يمثل فاصل الصفحة الأفقي.



يكشف النوع HorizontalPageBreak عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [start_column](/cells/python-net/ar/aspose.cells/horizontalpagebreak/start_column) | يحصل على فهرس عمود البداية لكسر الصفحة الأفقية هذه.|
| [end_column](/cells/python-net/ar/aspose.cells/horizontalpagebreak/end_column) | يحصل على فهرس العمود النهائي لكسر الصفحة الأفقية هذه.|
| [row](/cells/python-net/ar/aspose.cells/horizontalpagebreak/row) |يحصل على مؤشر الصف المستند إلى الصفر.|



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
