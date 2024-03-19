---
title: VerticalPageBreak صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1630
url: /ar/aspose.cells/verticalpagebreak/
is_root: false
---
##  VerticalPageBreak صف
يقوم بتغليف الكائن الذي يمثل فاصل الصفحات العمودي.



يكشف النوع VerticalPageBreak عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [start_row](/cells/python-net/ar/aspose.cells/verticalpagebreak/start_row) | الحصول على فهرس صف البداية لفاصل الصفحات العمودي.|
| [end_row](/cells/python-net/ar/aspose.cells/verticalpagebreak/end_row) | الحصول على فهرس صف النهاية لفاصل الصفحات العمودي.|
| [column](/cells/python-net/ar/aspose.cells/verticalpagebreak/column) | الحصول على فهرس العمود لفاصل الصفحات العمودي.|



###  مثال

```python
from aspose.cells import Workbook

excel = Workbook()
# Add a pagebreak at G5
excel.worksheets[0].horizontal_page_breaks.add("G5")
excel.worksheets[0].vertical_page_breaks.add("G5")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
